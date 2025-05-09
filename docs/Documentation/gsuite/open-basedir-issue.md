---
title: Open Basedir Issue
excerpt: Here is the information about Open Basedir Issue
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---

<div itemprop="articleBody">
<span style={{fontSize: "x-large"}}><strong>open basedir issue</strong></span>
<span style={{fontSize: "large"}}><br />What is meant by open_basedir?</span>
The open_basedir is a function that defines the locations or paths from which PHP is authorized to access files using functions like gzopen() and fopen(). If a file or document defined by open_basedir which is outside of the paths is outside of the paths, then PHP will deny to open it in <strong>shared web hosting</strong>.<br /> 
<p dir="ltr"><strong><span style={{fontSize: "large"}}>PHP Error</span></strong></p>
<p dir="ltr"><span style={{fontSize: "large"}}><strong>Unknown:</strong> open_basedir restriction in effect. File is not within the allowed path(s)</span></p>
<p><span style={{fontSize: "large"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "large"}}>The open_basedir function defines the paths from which PHP is allowed to access files using functions. If a file is outside of the paths defined by open_basdir, PHP will refuse to open it in shared <strong>web hosting.</strong></span></p>
<p><span style={{fontSize: "large"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "large"}}>You can set open_basedir to none to remove this restriction.</span></p>
<p><span style={{fontSize: "large"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "large"}}>open_basedir limits all I/O operations in userspace PHP to a certain configurable subset of the filesystem, in particular to a number of directories and their subdirectories</span></p>
<p><span style={{fontSize: "large"}}> </span></p>
<div class="help-image-block"> </div>
<p><span style={{fontSize: "large"}}> </span></p>
<strong><span style={{fontSize: "large"}}><span style={{fontSize: "x-large", fontFamily: "georgia, palatino"}}>How to fix this issue?</span><br /><br /></span></strong>
<p dir="ltr"><span style={{fontSize: "large"}}>Step - 1 : You have an exclusive alternative to disable open_basedir in the php.ini by utilizing the following:<br /><br /> open_basedir = none <br /><br />Check and alter the open_basedir settings in your hosting account and set them to none. Search and get the open_basedir setting below the 'PHP Settings' area of your Plesk/cPanel. And lock it as 'none' from the drop-down. I have shown them in the Plesk panel picture for <strong> Windows Reseller hosting.</strong><br /><br /><br /></span></p>
<p dir="ltr"><span style={{fontSize: "large"}}></span></p>
<p><span style={{fontSize: "large"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "large"}}></span></p>
<p><span style={{fontSize: "large"}}><br /><br /></span></p>
<p dir="ltr"><span style={{fontSize: "large"}}>Step - 2 : Kindly refer below steps to enable open_basedir  from cPanel, Which is the default control panel in our <strong>Linux shared hosting</strong>.</span></p>
<p><span style={{fontSize: "large"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "large"}}></span></p>
<p><span style={{fontSize: "large"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "large"}}>Step - 3 : Click on “Switch to PHP Options”.</span></p>
<p><span style={{fontSize: "large"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "large"}}></span></p>
<p><span style={{fontSize: "large"}}><br /><br /><br /></span></p>
<div class="help-image-block"> </div>
<p><span style={{fontSize: "large"}}><br /><br /></span></p>
<p dir="ltr"><span style={{fontSize: "large"}}>Step - 4 : Click on save</span></p>
<p><span style={{fontSize: "large"}}> </span></p>
<p dir="ltr"></p>
<p dir="ltr"><span style={{fontSize: "large"}}>Following these steps above you shall come to know how to resolve the open_basedir issue on your own. For any other information check our <strong> help</strong>.</span></p>
<div> </div> </div>

<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 

<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 

</div>