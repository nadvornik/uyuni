#
# Copyright (c) 2008--2012 Red Hat, Inc.
#
# This software is licensed to you under the GNU General Public License,
# version 2 (GPLv2). There is NO WARRANTY for this software, express or
# implied, including the implied warranties of MERCHANTABILITY or FITNESS
# FOR A PARTICULAR PURPOSE. You should have received a copy of GPLv2
# along with this software; if not, see
# http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt.
#

COMMON = ../../common/data

common :
	rm -rf common
	mkdir common
	for i in $(COMMON)/* ; do sed 's/\\n/\\\\n/g' $$i > common/$${i##*/} ; done

clean :
	rm -rf common

.PHONY : common clean
