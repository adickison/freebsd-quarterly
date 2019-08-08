## FreeBSD Foundation ##

Contact: Deb Goodkin, <deb@FreeBSDFoundation.org>

The FreeBSD Foundation is a 501(c)(3) non-profit organization dedicated to supporting and promoting the FreeBSD Project and community worldwide. Funding comes from individual and corporate donations and is used to fund and manage software development projects, conferences and developer summits, and provide travel grants to FreeBSD contributors. The Foundation purchases and supports hardware to improve and maintain FreeBSD infrastructure and provides resources to improve security, quality assurance, and release engineering efforts; publishes marketing material to promote, educate, and advocate for the FreeBSD Project; facilitates collaboration between commercial vendors and FreeBSD developers; and finally, represents the FreeBSD Project in executing contracts, license agreements, and other legal arrangements that require a recognized legal entity.

Here are some highlights of what we did to help FreeBSD last quarter:

### Partnerships and Commercial User Support ###

As a 501(c)(3) non-profit, we don’t directly support commercial users, but we do work with them to understand their needs and help facilitate collaboration with the community. Last quarter, we were able to meet with a number of FreeBSD users and supporters at the October FreeBSD Developer Summit and MeetBSD conference in addition to our regular company meetings.  These in-person meetings provide the opportunity to discuss pain points, identify how they can contribute back to FreeBSD, talk about what technologies they would like to see supported, and what can be done to support FreeBSD over more of their technologies and products.

### Fundraising Efforts ###

By end of last year, we raised over $1.3M and were able to add Juniper, Netflix and Facebook and Handshake.org to our list of Foundation Partners. You can view entire list here (https://www.freebsdfoundation.org/donors/). We are still finalizing total donations, and will report the final numbers in early February. Thank you to everyone who supported our efforts in 2018. 

### OS Improvements ###

In the fourth quarter of 2018 six authors made a total of 315 commits to FreeBSD development tree that were identified as being sponsored by the FreeBSD Foundation. These included staff members Konstantin Belousov, Glen Barber, Li-Wen Hsu and Ed Maste, and grant recipients Mateusz Guzik and Mark Johnston.

Mateusz' work over the quarter consisted of identifying and fixing bottlenecks in the FreeBSD kernel and system libraries. The FreeBSD base system build, and ports built via Poudriere, were used as motivating cases.

Mark added an in-kernel Intel CPU microcode loader. This simplifies and increases the robustness of microcode updates, which is increasingly important as mitigations for speculative execution vulnerabilities are delivered in microcode.

Mark also fixed a number of issues relating to capsicum support in base system utilities, implemented a number of NUMA enhancements and bug fixes, and fixed a number of high profile kernel bugs.

Ed committed a large number of tool chain fixes to LLVM's lld linker and ELF Tool Chain components.

Along with several FreeBSD developers Ed worked on the OpenSSL 1.1.1 import in preparation for FreeBSD 12.0, including incorporating OpenSSH and ntp changes for compatibility. Ed also added build-time knobs for to enable userland retpoline and to enable BIND_NOW which
can be used as part of a vulnerability mitigation strategy.

### Continuous Integration and Quality Assurance ###

The Foundation provides a full-time staff member who is working on improving our automated testing, continuous integration, and overall quality assurance efforts.

During the fourth quarter of 2018, Foundation employee Li-Wen Hsu continuously worked on improving the project's CI infrastructure, examining the failing build and test cases, and work with other teams in the project for their testing needs. In this period, we also worked on collaboration with external projects to improve their CI on FreeBSD.

See the FreeBSD CI section of this report for more information.

### Release Engineering ###

The Foundation provides a full-time staff member to lead the release engineering efforts. This has provided timely and reliable releases over the last five years. During the fourth quarter of 2018, Glen Barber led the the FreeBSD Release Engineering team in continuing working on the 12.0-RELEASE with the official announcement sent December 11.

See the FreeBSD Release Engineering Team section of this report for more
information.

### Supporting FreeBSD Infrastructure ### 

The Foundation provides hardware and support to improve the FreeBSD infrastructure. Last quarter, we continued supporting FreeBSD hardware located around the world.

### FreeBSD Advocacy and Education ###

A large part of our efforts are dedicated to advocating for the Project. This includes promoting work being done by others with FreeBSD; producing advocacy literature to teach people about FreeBSD and help make the path to starting using FreeBSD or contributing to the Project easier; and attending and getting other FreeBSD contributors to volunteer to run FreeBSD events, staff FreeBSD tables, and give FreeBSD presentations.

The FreeBSD Foundation sponsors many conferences, events, and summits around the globe. These events can be BSD-related, open source, or technology events geared towards underrepresented groups. We support the FreeBSD-focused events to help provide a venue for sharing knowledge, to work together on projects, and to facilitate collaboration between developers and commercial users. This all helps provide a healthy ecosystem. We support the non-FreeBSD events to promote and raise awareness of FreeBSD, to increase the use of FreeBSD in different applications, and to recruit more contributors to the Project.

Some of the advocacy and education work we did last quarter includes:
* Organized, sponsored, and presented at the October 2018 FreeBSD Developers Summit in Santa Clara, CA
* Sponsored and exhibited at MeetBSD 2018 in Santa Clara, CA
* Exhibited for the first time at All Things Open in Raleigh, NC
* Exhibited  and sponsored as an Industry Partner at LISA’ 18 in Nashville, TN
* Sponsored USENIX OSDI ‘18 in Carlsbad, CA as an Industry Partner
* Held an Intro to FreeBSD workshop and a “Why You Should Contribute to FreeBSD” talk at the Rocky Mountain Celebration of Women in Computing in Lakewood, Colorado

We continued producing FreeBSD advocacy material to help people promote FreeBSD around the world. 

Read more about our conference adventures in the conference recaps and trip reports in our monthly newsletters: (https://www.freebsdfoundation.org/news-and-events/newsletter/)

We help educate the world about FreeBSD by publishing the professionally produced FreeBSD Journal. We recently announced that the FreeBSD Journal will become a Free publication with the January/February 2019 issue. (https://www.FreeBSDfoundation.org/journal/).

You can find out more about events we attended and upcoming events at (https://www.FreeBSDfoundation.org/news-and-events/).

For a look back at all of efforts in 2018, please see the year-end video at (https://www.freebsdfoundation.org/blog/thank-you-for-supporting-freebsd/).

### Legal/FreeBSD IP ###

The Foundation owns the FreeBSD trademarks, and it is our responsibility to protect them. We also provide legal support for the core team to investigate questions that arise. Last quarter, we approved 6 requests to use the Trademark. 
Go to (http://www.FreeBSDfoundation.org) to find out how we support FreeBSD and how we can help you!
