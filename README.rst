    README - General description of the linux-configs collection

    Copyright (C) 2018-2019 Angel Linares Zapater

    This program is free software; you can redistribute it and/or modify
    it under the terms of the GNU General Public License, version 2, as
    published by the Free Software Foundation. See the COPYING file.

    This program is distributed WITHOUT ANY WARRANTY; without even the
    implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

The linux-configs collection
============================

The linux-configs Collection is a set of Kconfig configuration files for
the Linux kernel. This collection tracks the stable and longterm releases
of the Linux kernel from the Linux Kernel Archives
https://www.kernel.org/category/releases.html.

The collection contains Kconfig files that have been preconfigured in order to
be used, with different architectures and with certain hardware requirements,
when a new Linux kernel is manually built.

How to use
==========

This collection is originally designed to work with the BANDIT toolkit
https://github.com/phyglos/bandit and the phyglos-kernel bundle
https://github.com/phyglos/phyglos. In this case everything is handled by
the BANDIT; only the desired kernel version needs to be selected in the
phyglos-kernel bundle configuration.

However, the Kconfig files included in this collection can be used as independent
configuration files when manually building a new Linux kernel. In order to use
these files manually just download the wanted file from the GitHub repository
https://github.com/phyglos/linux-configs or download and uncompress the package
from the FTP site ftp://phyglos.org/linux-configs and copy it as ".config" in
the kernel source tree.

Status
======

The linux-config collection is in DEVELOPMENT status. This means that the structure
of the repository and some other elements like naming conventions, etc. can still
suffer some changes.

The package is already in regular use in the phyglos-kernel bundle in the phyglos
catalog for the phy GNU/Linux operating system. Also, the individual KConfig files
can be used as a starting point when manually building a new Linux kernel for a
given configuration.

More information
================

The COPYING file contains the GNU License for this software.

The RELEASE file describes the main changes in this release.

See the documentation at https://docs.phyglos.org/linux-configs
