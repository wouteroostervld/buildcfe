buildcfe
========

HEADS UP: removes /var/cfengine and rebuilds it from scratch. (Please see example "build_in_jail" to build in a jail and protect your old install.)

buildcfe: builds independent cfengine3 installation with dynamic linked libmysqlclient and libxml2. (Independent from software in /usr/local).

Usage: ./buidcfe [TAG]

Drops tarball in current dir. 

Tested on freebsd.

Needs sudo to install stuff.

You can give an tag to compile otherwise head will be compiled.

Needs git, autotools, automake, sudo, bison, libtools, cmake and gmake.
