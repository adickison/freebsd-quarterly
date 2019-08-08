## pfsync performance improvement ##

Contact: Kristof Provost, <kp@freebsd.org>

While pf itself can operate on multiple states simultaneously
(on different cores), pfsync could not. It used a single PFSYNC_LOCK.
This greatly reduced throughput on multicore systems as soon as pfsync
was loaded.

This was improved by splitting the pfsync queues into buckets, based on the
state ID. This ensures that updates for a given connection always end up
in the same bucket, allowing pfsync to still collapse multiple
updates into one, while allowing multiple cores to proceed at the same
time.
The buckets are independently locked, allowing multiple cores to proceed at once.

The number of buckets is tunable, but defaults to twice the number of cpus.
Benchmarking has shown improvement of 30 to 100% depending on hardware and setup.

During this effort several vnet-related issues were fixed as well, and a basic
pfsync test case was added.

This was committed into head in r341646, and later merged into stable/12 and stable/11.

Sponsor: Orange Business Services
