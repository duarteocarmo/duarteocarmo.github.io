---
title:  "Report Automation using Python, Papermill and Rclone"
date:   2019-7-29 20:43:05 +0000
categories: misc
layout: post
---

During the month of July I wrote two blog posts for the popular [Practical Business Python blog](https://pbpython.com/). The Practical Business Python blog is one of the top 20 most popular blogs on python with about [200.000 visits](https://www.similarweb.com/website/pbpython.com#overview) per month. 

The posts focus on how you can build an automation system that generates `Html` reports from excel files. The system uses python, jupyter, papermill, subprocess and Rclone. 

Here are the links to both parts:
- [Part 1: Concept presentation](https://pbpython.com/papermil-rclone-report-1.html)
- [Part 2: Architecture and final solution](https://pbpython.com/papermil-rclone-report-2.html)

These posts were featured in the [Python Bytes podcast](https://pythonbytes.fm/episodes/show/142/there-s-a-bandit-in-the-python-space) (jump to 12:39):

<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/662152787&color=%232a7ae2&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true">
</iframe>
<br/>
The architecture of the automation solution and final script follow:
<center>
<img src="/assets/img/automation/architecture.png" alt="JupyterLab" style="width:90%; box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2), 0 6px 20px 0 rgba(0, 0, 0, 0.19);">
</center>
<br/>

<script src="https://gist.github.com/duarteocarmo/e52727365f50167bc0b8f997d6321937.js"></script>
