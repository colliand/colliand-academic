---
title: Web Course Platform Prototyped by Toronto Mathematician
date: 2012-02-09T19:35:49.525Z
draft: false
featured: false
authors:
  - admin
tags:
  - tools
  - edtech
categories:
  - research-tech
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---

Suppose you've recorded a one hour lecture onto video and taken digital photographs of each blackboard used during the presentation. The video and photograph files contain metadata with time stamps: we know the time when each frame of video and photograph was captured. How should these files be blended to create a browser-based environment for studying the ideas in the lecture? My colleague <a href="http://www.math.toronto.edu/~drorbn/">Dror Bar-Natan</a> has prototyped a remarkable software platform combining this data to support online courses and seminars.

The system is built atop <a href="http://www.mediawiki.org/wiki/MediaWiki">MediaWiki</a> (the software that runs Wikipedia) and allows metadata, such as  comments and photographs, to be correlated in time to an embedded video stream. Comments can be attached to each frame of video. <a rel="attachment wp-att-920" href="http://blog.math.toronto.edu/colliand/2012/02/09/web-course-platform-prototyped-by-toronto-math-professor-dror-bar-natan/dror_wclips/"><img class="alignright size-medium wp-image-920" src="http://blog.math.toronto.edu/colliand/files/2012/02/dror_wclips-300x148.png" alt="" width="300" height="148" /></a>The system enables remote audience members to participate in the seminar frame-by-frame using their power to comment. In this way, the <a href="http://katlas.math.toronto.edu/drorbn/index.php?title=WKO">wClips system</a> goes beyond playback by empowering the remote audience of the future to contribute to the past presentation.

The system was recently used to supplement <a href="http://www.math.toronto.edu/~drorbn/papers/WKO/WKO.pdf">a paper</a> Dror is co-authoring with <a href="http://www.math.toronto.edu/zsuzsi/">Zsuzsanna Dansco</a> in the <a href="http://katlas.math.toronto.edu/drorbn/index.php?title=WKO">wClips seminar</a>. Each section of the paper was discussed in detail in a seminar lecture captured on video. Each blackboard in the seminar series was photographed. Time links near the photographs move the video stream to the video time when that blackboard image was created. The sizes of the different elements can be changed by sliding the red line. In the final version of the paper, there will appear hyperlinks in each section pointing at the associated seminar presentation. Clicking on the photographs reveals another layer of comments highlighting the elements appearing on the blackboard.

Dror gave a <a href="http://katlas.math.toronto.edu/drorbn/dbnvp/wClips-120118-1.php">video introduction</a> describing how to operate the system and produced a<a href="http://katlas.math.toronto.edu/drorbn/AcademicPensieve/Classes/12-wClips/one/How_to_use_this_site.pdf"> one page guide.</a> (The lighting is not so good.)<a rel="attachment wp-att-927" href="http://blog.math.toronto.edu/colliand/2012/02/09/web-course-platform-prototyped-by-toronto-math-professor-dror-bar-natan/how_to_use_this_site-2/"><img class="alignright size-medium wp-image-927" src="http://blog.math.toronto.edu/colliand/files/2012/02/How_to_use_this_site-231x300.png" alt="" width="231" height="300" /></a> <a href="http://katlas.math.toronto.edu/drorbn/dbnvp/wClips-120118-2.php">Zsuzsanna's lecture</a> is also a nice demonstration of wClips.

The wClips system runs on a linux server using open source software so is inexpensive to deploy. Since it is based on MediaWiki, it has the potential to scale to support a massive audience. Getting the video content out of the camera and into the online course system involves some work but could be streamlined with the right scripts.