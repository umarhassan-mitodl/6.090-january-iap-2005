---
content_type: page
description: Installation for Windows OS
draft: false
learning_resource_types:
- Tools
ocw_type: CourseSection
parent_title: Tools
parent_type: CourseSection
parent_uid: a361770f-74a5-81b1-25d8-23a9a1c629b2
title: 6.001 Scheme for Windows machines
uid: 3dcbc98e-4286-cea6-4943-f2604aac010d
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
## {{< anchor "WinNT" >}}Installation on Windows NT{{< /anchor >}}, {{< anchor "Win95" >}}Windows 95{{< /anchor >}}, {{< anchor "Win00" >}}Windows 2000{{< /anchor >}}, {{< anchor "WinXP" >}}Windows XP{{< /anchor >}}

**Warning** for Windows 95 users: in order to be able to print from Edwin you must be sure that your default printer was installed with the "Allow printing from DOS" option turned *on*.

**Disclaimer**: While it may be possible to install Scheme on Windows 98 or Windows ME, we do not support these operating systems and can only offer limited help. We believe that this Scheme will work on Windows 2000 and Windows XP, but if you experience difficulties in using these systems, please let us know. Caveat Hacker.

MIT Scheme requires two directories:

- One for holding the Scheme system itself.  This can be placed anywhere you like (but no spaces are allowed in the directory name!), and requires about 15 Megabytes of disk space.  Before downloading the installation program, be sure you have 25 Megabytes free on the disk where you plan to place MIT Scheme.
- One for holding problem sets.  This, too, can be placed anywhere you like (but no spaces are allowed in the directory name!).  Over the course of the semester you should assume that it will grow to be about 5 Megabytes (maybe).  There will be two subdirectories: `PSets` (where you will install the problem sets as they are distributed) and `Work` (where you will write your solutions).

## Installation instructions:

1. **Download** the Scheme installer, ({{% resource_link "564236b1-63e6-4445-a5c9-639ebad61df6" "EXE - 10MB" %}}), into a temporary directory of your choice. This file is about 11 megabytes long,
2. Run the install program, `win32-6001.exe`
3. The InstallWizard will ask you some questions; we suggest that you accept the default for installing the MIT Scheme system itself.
4. The installer will ask you where you want to install the applications database. This is the location that you will store problem set code and your own work, and defaults to c:\\u6001. The installer will create two subdirectories named `PSets` (to hold the problem sets in the form they are distributed) and `Work` (where you should modify the problem sets to produce your solutions).
5. You can then delete the install program.

## Installing Problem Sets:

Problem sets will be distributed as ZIP files from the 6.001 Web page. In order to install them, you will need to be able to "unzip" them on your machine. You can use the shareware program [WinZip](http://www.winzip.com/), which provides a graphical user interface as well as integration into both Netscape and Microsoft browsers.