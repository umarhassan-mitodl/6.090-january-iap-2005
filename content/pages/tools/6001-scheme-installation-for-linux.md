---
content_type: page
description: Installation for Linux
draft: false
learning_resource_types:
- Tools
ocw_type: CourseSection
parent_title: Tools
parent_type: CourseSection
parent_uid: a361770f-74a5-81b1-25d8-23a9a1c629b2
title: 6.001 Scheme Installation for Linux
uid: 5a6920c9-5d40-e8fe-384e-81bc870d579b
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---
The 6.001 system has two parts:

- One part is the Scheme system itself. There are two executables installed in `/usr/local/bin`, and several data files installed in `/usr/local/lib/mit-scheme`. The system requires about 30 Megabytes of disk space. Before downloading the tar file, be sure you have enough free space on `/usr/local`. If you do not have enough space on `/usr/local` you can use symbolic links to other parts of the file system -- but you will be on your own to make sure that it all works (the lab TAs may be able to help).
- The other part is for problem sets. This can be placed anywhere you like. Over the course of the semester you should assume that it will grow to be about 5 Megabytes (maybe). There will be two subdirectories: `psets` (where you will install the problem sets as they are distributed) and `work` (where you will write your solutions).

Installation instructions:

1. Download the Scheme system ({{% resource_link "2db0db16-e1c1-4b1d-a1a2-14c799b2871d" "TAR.GZ - 11MB" %}}) - a `TAR` file, compressed with `gzip -` into a temporary directory of your choice. Let's assume that you put the file into `/tmp/gnulinux-6001.tar.gz`
2. Be sure you are logged in with root privileges. If your system does not have a directory `/usr/local`, you will need to create one. Then execute the command line:   
    `cd /usr/local; tar -xvzf /tmp/gnulinux-6001.tar.gz`
3. As part of your normal initialization (perhaps in your `.login` or `.cshrc` file) set an environment variable named `MITSCHEME\_6001\_DIRECTORY` to the directory in which you plan to store the problem sets (be sure the directory exists and has two subdirectories, named `psets` and `work`).
4. The command line to start Scheme for use in 6.001 is   
    `scheme -large -band 6001.com -edit`   
    (you might want to make an alias for that command line -- you are likely to be typing it often!)
5. If everything seems to work you can now remove the tar file:   
    `rm /tmp/gnulinux-6001.tar.gz`

**Note:** We have tested this Scheme system under RedHat Linux 5.2, 6.2, and 7.0 Other versions of Linux may need additional libraries to run this system. Ask for help if you run into problems.