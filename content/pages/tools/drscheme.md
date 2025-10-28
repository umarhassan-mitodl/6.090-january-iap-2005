---
content_type: page
description: ''
learning_resource_types:
- Tools
ocw_type: CourseSection
parent_title: Tools
parent_type: CourseSection
parent_uid: a361770f-74a5-81b1-25d8-23a9a1c629b2
title: A Note About DrScheme
uid: 05f349d5-b4fc-8099-c797-885d2f882d3f
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

{{% resource_link "de1e1fa3-148c-4d4c-ae41-54090e4d1e7a" "DrScheme" %}} is The {{% resource_link "af235af7-6cbc-4bff-ba50-b6ea6e5cccd4" "Rice University Programming Languages Team" %}}'s graphical user interface to a Scheme system for students. A quick examination of the latest version was encouraging. And DrScheme is _free_.

DrScheme has some innovative user-interface features not found in MIT Scheme: text is color-coded, for example to highlight (in red) undefined variables; it has a syntax analysis command which, for example, can display arrows from occurrences of variables to their definitions elsewhere in the code; it has several output modes in addition to the standard one, for example an output mode which shows sharing in lists, and another output mode in which values are printed as canonical INPUT expressions -- in this mode, for example, the list value which is the result of evaluating `(cons 1 (cons (+ 2 3) '()))` prints out as `(list 1 5)`. DrScheme also has Windows menu control of most features, and error messages that are more clear than those in MIT Scheme.

To run satisfactorily, it requires at least 20MB of RAM and a 150MHZ processor. It has extensive online documentation.