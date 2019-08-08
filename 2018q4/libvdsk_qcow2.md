## libvdsk - QCOW2 implementation ##

Contact: Sergiu Weisz, <sergiu121@gmail.com>

Contact: Marcelo Araujo, <araujo@freebsd.org>

Contact: Mihai Carabas, <mihai@freebsd.org>

Link:	[Github - Libvdsk QCOW2 branch](https://github.com/FreeBSD-UPB/freebsd/tree/projects/bhyve_libvdsk)

New features added:

   * Extend libvdsk to make it easier to implement new formats;
   * Implement read/write/probe functionalities in order to parse QCOW2 image files;

Future tasks:

   * Add support for Copy-On-Write;
   * Add support for multiple snapshots;
   * Integrate libvdsk in bhyve

Sponsor: Matthew Grooms
