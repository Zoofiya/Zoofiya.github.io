---
layout: post
title:  "Some thoughts on robots.txt and humans.txt"
date:   2018-10-10 07:48:17 -0600
categories: jekyll update
comments: true
---

## Some thoughts on robots.txt and humans.txt

#### What is robots.txt and how have you configured It for your site?
A robots.txt is a file is afile with only a few rows of texts that tell webcrawlers that crosses path with the site which files to not access.

This text-file should be used correctly to not lock the wrong files and decrease the ranking on search engines. The robots.txt file is basically instructions for robots of how they should identify or treat yuor site. We could for example give instructions in our text-file that ads are being crawled. CSS-files and Javascript files shall not be blocked because Googlebot cannot really render It correctly which in turn could lead to complications.

Mine is simply saying that my pictures shall not be indexed in Google-images. Otherwise, any other robot is treated the same way and shall not have access to any files except the ones that include .css in the file-name. 
<br><br/>
#### What is humans.txt and how have you configured It for your site?
A humans.txt is a text-file where all contributors to the site is listed. In such a file you could expect the role of the person, name, twitter, contact and location. The date, main language and softwares used for the project are also usually found here. This text-file is often located in the head-tag on the site. These could also be found in my humans.txt for this site. After creating the file, I linked It to my head.html in a folder called includes where HTML-files such as for footer and header are located. This way my humans.txt could be found in the head-tag of the site.



<a href="http://localhost:4000/jekyll/update/2018/11/15/ssg.html" class="next">Next post</a>
