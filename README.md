# Welcome to MPhil in Scientific Computing at Cambridge!

This is where I store the code for the one-year master course for scientific computing at the Univeristy of Cambridge. Hopefully the code can inspire more than just me on the internet!

Jianou Jiang

06/Oct/2020

# Overview

--

To all MPhil and 1st-year CDT students:

You will shortly receive an email giving you a username (your CRSId) and
a unique link for you to collect your password from the 'One Time
Secret' site.
You will need to give the passphrase: CSC2020
to collect the password.

This will allow you to access the Linux-based CSC network, which is set
up with all software you will need for your course.

You need to set up your computer to be able to use 'ssh' to connect to
the network; instructions for major operating systems are below.
If you are not in University or College owned accommodation, you may
need to connect to the University VPN; instructions are at
[www.uis.cam.ac.uk/vpn](http://www.uis.cam.ac.uk/vpn)

You should then try to connect to the network by: ssh
USERNAME@apollo.lsc.phy.private.cam.ac.uk (or equivalent for your OS),
and change your password by using the 'passwd' command. More information
about the Linux operating system and how to use it will be given in the
"Introduction to Linux" course.

Some information about the network can be found at:
<https://www-internal.lsc.phy.cam.ac.uk/>

and the list of available machines (you only have access to those
labelled "CSC-MPHIL"):
<https://www-internal.lsc.phy.cam.ac.uk/systems.shtml>



-----

Connection instructions
=======================

If you decide to attempt practicals on your own computer, you will need
at least the following installed (probably via your OS package manager):

g++ (C++ compiler from gcc.gnu.org/) or clang++
(<http://llvm.org/builds/>)
OpenMPI (MPI implementation from <https://www.open-mpi.org/>)
gnuplot

Linux
=====

If you already have Linux installed on your home desktop or laptop, you
can use this, although we do not guarantee to support every possible
installation. We have most experience with recent LTS versions of Ubuntu
(e.g. 18.04 or 20.04). You will need to install at least g++,
openmpi-common, and gnuplot packages.

Mac OS X
========

While Mac OS X based systems may work for some of the practicals, we
have encountered subtle incompatibilities in the past, so you may be
better off connecting to the CSC Network in the first place. However,
Mac OS X has 'ssh' installed by default, so connections should be
straightforward.
You will need to use “ssh -Y” to connect to the CSC Network to run
graphical programs.

If you want to try to use Mac OS X for the practicals, please install
HomeBrew and then the gcc and open-mpi packages.

Microsoft Windows
=================

If you can install the Windows Subsystem for Linux, then this may
provide sufficient support for some of practicals. However, there may
also be subtle inconsistencies between this and a native Linux
distribution. If this is the case, you will need to connect to the CSC
Network, via MobaXterm (or similar).

Installing WSL:
<https://docs.microsoft.com/en-us/windows/wsl/install-win10>

Installing MobaXterm: <https://mobaxterm.mobatek.net/>

If you use WSL, please ensure that the g++, openmpi-common, and gnuplot
libraries are installed.

--



