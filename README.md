buildcfe
========

buildcfe: builds independent cfengine3 installation with linked libmysqlclient and libxml2. (Independent from software in /usr/local).

Usage: ./buidcfe [TAG]

Drops tarball in current dir.

Tested on freebsd.

Needs sudo to install stuff.

You can give an tag to compile otherwise head will be compiled.

Needs autotools, automake, cmake and gmake.
