# 
# FILE             $Id$
# 
# DESCRIPTION      Project makefile template.
# 
# PROJECT           Shared memory STL allocator.
# 
# AUTHOR           Michal Bukovsky <michal.bukovsky@firma.seznam.cz>
#
# LICENSE          see COPYING
# 
# Copyright (C) Seznam.cz a.s. 2007
# All Rights Reserved
# 
# HISTORY
#       2007-04-25 (bukovsky)
#                  First draft.
# 

# dir includes sources
SUBDIRS = src include

debian: debian/changelog
	dpkg-buildpackage -rfakeroot


pkgconfigdir=@libdir@/pkgconfig
pkgconfig_DATA=libshallocator.pc
