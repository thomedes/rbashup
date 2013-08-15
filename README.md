rbashup
=======

Another rsync bash backup

r-bash-up => (r)sync (bash) back(up)

Synopsys
--------

*rbashup*          backup-set

Description
-----------

*rbashup* is another rsync incremental backup utility. It is inspired in 
*rsnapshot* but with some changes:

### Design objectives

 *  KISS; should work out of the box in most GNU boxes, no need to install
    nothing special

 *  Made entirely in bash

 *  It should be easy to make a "backup of the backup". This means that
    snapshots should never moved or renamed.

 *  It must be easy to know where to find and retrieve a specific version
    of a file.

Configuration
-------------

The configuration of *rbashup* is stored in an ini file. Ths file is taken from,
in order of preference:

 *  the file reported in the command line
 *  ~/.rbashup
 *  /etc/rbashup.conf

Usage
-----

Exit Values
-----------



