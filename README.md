compare_repos 
=============
This tool created for comparing two different repositories of DEB or RPM packages.
The report on outcome will show a list of update and downgrade packages.

How it works
-------
The tool is using a native libraries of 'yum' and 'apt' package managers. That has been made for accurate reproducing a switch from one package repository to another.

Requirments
-------
0. Ubuntu 14.04 or later
0. Default repository for Ubuntu distro
0. python 2.6 or later

Installation
------------
    git clone https://github.com/d1mas/compare_repos

Usage
-----
    ./compare_repos [rpm|deb] -o old_repo -n new_repo
