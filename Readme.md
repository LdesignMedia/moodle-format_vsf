Introduction
============
Progress section format.

Required version of Moodle
==========================
This version works with Moodle 3.11 version 2021051700.00 (Build: 20210517) and above within the 3.11 branch until the
next release.

Please ensure that your hardware and software complies with 'Requirements' in 'Installing Moodle' on
'docs.moodle.org/311/en/Installing_Moodle'

Installation
============
1. Ensure you have the version of Moodle as stated above in 'Installation Requirements'.  This is essential as the
   format relies on underlying core code.
2. Put Moodle in 'Maintenance Mode' on 'docs.moodle.org/en/admin/setting/maintenancemode' so that there are no 
   users using it bar you as the administrator - if you have not already done so.
3. Copy 'vsf' to '/course/format/'.
4. Login as an administrator and follow standard the 'plugin' update notification.  If needed, go to
   'Site administration' -> 'Notifications' if this does not happen.
5. Put Moodle out of Maintenance Mode.

Uninstallation
==============
1. Put Moodle in 'Maintenance Mode' so that there are no users using it bar you as the administrator.
2. Navigate to 'Dashboard -> Site administration -> Plugins -> Plugins overview'.
3. Select 'Showing additional plugins only' and find the 'Uninstall' action.
4. Follow the on screen instructions.
5. Put Moodle out of Maintenance Mode.

Usage
=====
1. When creating a new course, select the course format as 'Progress Section Format' from the list of available options.
2. To change an existing course, edit the course settings (http://docs.moodle.org/311/en/course/edit) and select the
   'Progress Section Format' from the list of available options.

Notes
=====
1. Only administrators can add, edit and remove activities and resources (whilst in the format) from the general
   section (section 0), as to prevent accidental deletion of the 'news' forum upon which the format relies.  If it is
   deleted, then a page refresh will recreate the forum but all previous posts will be lost.
2. Any title and summary that has been previously set for the general section will not be shown.

Additional classes
Section name = 'vsf-sectionname'.
Section summary = 'vsf-summary' - due to Moodle limitations, use CSS such as '.vsf-summary p' to target the text directly.
Section progress chart = 'vsf-progress'.
Section progress chart percentage = 'vsf-percentage'.
Section complete = 'vsf-section-complete'.

Version Information
===================
See Changes.md

Licenses
========

Format code
-----------

GPLv3:
This file is part of Moodle - http://moodle.org/

Moodle is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Moodle is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Moodle.  If not, see <http://www.gnu.org/licenses/>.

G J Barnard MSc. BSc(Hons)(Sndw). MBCS. CEng. CITP. PGCE.
Moodle profile: moodle.org/user/profile.php?id=442195.
Web profile   : about.me/gjbarnard
