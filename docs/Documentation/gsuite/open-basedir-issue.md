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
<h1 dir="ltr"><span style="font-size: x-large;"><strong>open basedir issue</strong></span></h1>
<h2><span style="font-size: large;"><br/>What is meant by open_basedir?</span></h2>
The open_basedir is a function that defines the locations or paths from which PHP is authorized to access files using functions like gzopen() and fopen(). If a file or document defined by open_basedir which is outside of the paths is outside of the paths, then PHP will deny to open it in <a title="shared web hosting." href="https://www.hostingraja.in/"><strong>shared web hosting</strong>.</a><br/> 
<p dir="ltr"><strong><span style="font-size: large;">PHP Error</span></strong></p>
<p dir="ltr"><span style="font-size: large;"><strong>Unknown:</strong> open_basedir restriction in effect. File is not within the allowed path(s)</span></p>
<p><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;">The open_basedir function defines the paths from which PHP is allowed to access files using functions. If a file is outside of the paths defined by open_basdir, PHP will refuse to open it in shared <strong><a title="web hosting" href="https://www.hostingraja.in/">web hosting.</a></strong></span></p>
<p><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;">You can set open_basedir to none to remove this restriction.</span></p>
<p><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;">open_basedir limits all I/O operations in userspace PHP to a certain configurable subset of the filesystem, in particular to a number of directories and their subdirectories</span></p>
<p><span style="font-size: large;"> </span></p>
<div class="help-image-block"><img src="https://image.hostingraja.in/images/open-basedir-issue-1.png" alt="open basedir error" height="108"/> <img src="https://image.hostingraja.in/images/open-basedir-issue-2.png" alt="open basedir error" height="108"/></div>
<p><span style="font-size: large;"> </span></p>
<h3><strong><span style="font-size: large;"><span style="font-size: x-large; font-family: georgia, palatino;">How to fix this issue?</span><br/><br/></span></strong></h3>
<p dir="ltr"><span style="font-size: large;">Step - 1 : You have an exclusive alternative to disable open_basedir in the php.ini by utilizing the following:<br/><br/> open_basedir = none <br/><br/>Check and alter the open_basedir settings in your hosting account and set them to none. Search and get the open_basedir setting below the 'PHP Settings' area of your Plesk/cPanel. And lock it as 'none' from the drop-down. I have shown them in the Plesk panel picture for <strong><a title="Reseller Hosting" href="https://www.hostingraja.in/hosting/reseller-web-hosting/"> Windows Reseller hosting.</a></strong><br/><br/><br/></span></p>
<p dir="ltr"><span style="font-size: large;"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/open-basedir-issue1.png" alt="php stings" width="252" height="193" border="0"/></span></p>
<p><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/open-basedir-issue2.png" alt="open dir" width="421" height="239" border="0"/></span></p>
<p><span style="font-size: large;"><br/><br/></span></p>
<p dir="ltr"><span style="font-size: large;">Step - 2 : Kindly refer below steps to enable open_basedir  from cPanel, Which is the default control panel in our <strong><a title="Linux shared hosting" href="https://www.hostingraja.in/">Linux shared hosting</a></strong>.</span></p>
<p><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/open-basedir-issue3.png" alt="select php version " width="200" height="147" border="0"/></span></p>
<p><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;">Step - 3 : Click on “Switch to PHP Options”.</span></p>
<p><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/open-basedir-issue4.png" alt="switch php option " width="248" height="274" border="0"/></span></p>
<p><span style="font-size: large;"><br/><br/><br/></span></p>
<div class="help-image-block"><img src="https://image.hostingraja.in/images/open-basedir-issue5-1.png" alt="open basedir value" height="108"/> <img src="https://image.hostingraja.in/images/open-basedir-issue5-2.png" alt="open basedir value" height="108"/></div>
<p><span style="font-size: large;"><br/><br/></span></p>
<p dir="ltr"><span style="font-size: large;">Step - 4 : Click on save</span></p>
<p><span style="font-size: large;"> </span></p>
<p dir="ltr"><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/open-basedir-issue6.png" alt="click on save " width="253" height="215" border="0"/></p>
<p dir="ltr"><span style="font-size: large;">Following these steps above you shall come to know how to resolve the open_basedir issue on your own. For any other information check our <strong><a href="/web/20230306211540/https://help.hostingraja.in/&quot;"> help</a></strong>.</span></p>
<div> </div> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="INODE" aria-label="Previous article: INODE" href="/web/20230306211540/https://help.hostingraja.in/basic/inode" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="High Traffic Website" aria-label="Next article: High Traffic Website" href="/web/20230306211540/https://help.hostingraja.in/other-help/high-traffic-website" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>