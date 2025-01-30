---
title: Troubleshoot the blank pages in wordpress
excerpt: >-
  Resolve WordPress blank page issues by troubleshooting plugins and themes for
  seamless website functionality
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
<div class="page-header"><h2 itemprop="headline">
Troubleshoot the blank pages in wordpress</h2>
</div>
<dl class="article-info muted">
<dt class="article-info-term">
</dt>
<dd class="modified">
<span class="icon-calendar" aria-hidden="true"></span>
<time datetime="2024-01-03T12:06:47+00:00" itemprop="dateModified">
Last Updated: 03 January 2024 </time>
</dd>
</dl>
<div itemprop="articleBody">
<h1 dir="ltr" style="text-align: center;"><span style="font-size: large;"><span style="font-size: xx-large;" data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;Troubleshoot the blank pages in wordpress&quot;}" data-sheets-userformat="{&quot;2&quot;:769,&quot;3&quot;:{&quot;1&quot;:0},&quot;11&quot;:4,&quot;12&quot;:0}">Troubleshoot the blank pages in wordpress</span><br/><br/></span></h1>
<h4 dir="ltr"><span style="font-size: large;">Problem</span></h4>
<div><span style="font-size: large;"> </span></div>
<p dir="ltr"><span style="font-size: large;">The blank page will occur when you try to view the <a href="https://www.hostingraja.in/hosting/wordpress-hosting/">wordpress website</a>, This may occur on single page, on multiple pages and on entire site. You may also unable to login to the admin panel.</span></p>
<p><span style="font-size: large;"> </span></p>
<h4 dir="ltr"><span style="font-size: large;">Resolution</span></h4>
<div><span style="font-size: large;"> </span></div>
<p dir="ltr"><span style="font-size: large;">The general causes for this problem on wordpress sites are:</span></p>
<p><span style="font-size: large;"> </span></p>
<ul>
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">A malfunctioning plugin </span></p>
</li>
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">A malfunctioning Theme</span></p>
</li>
</ul>
<p><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;">To resolve this problem you can disable the plugins one by one by selecting individually until the blank pages disappear. Apart from this if you notice that the current theme is causing the issue then you need to suspect the current theme by reverting back to its default theme.<br/><br/></span></p>
<h5 dir="ltr"><span style="font-size: large;">Disabling plugins</span></h5>
<div><span style="font-size: large;"> </span></div>
<p dir="ltr"><span style="font-size: large;">You can disable the plugins if you login to the wordpress as a administrator from the plugins options. If you are not an administrator you need to disable the plugins manually from the cPanel provided with your <a href="https://www.hostingraja.in/">website hosting</a>, To do this follow the below steps:<br/><br/></span></p>
<ol>
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Login to your cPanel</span></p>
</li>
</ol>
<ol start="2">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Click on file manager and then go to the path public_html/wp-content/plugins.</span></p>
</li>
</ol>
<ol start="3">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Each plugin will be in a separate directory, To disable the plugins you need to rename the plugin for example: to disable the Akismet plugin just rename it as Akismet_bak</span></p>
</li>
</ol>
<ol start="4">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">You need to repeat the above process for all the plugins one by one, If you notice that the particular plugin is causing the issue then it's well and good.</span></p>
</li>
</ol>
<h5 dir="ltr"><span style="font-size: large;"> </span></h5>
<h5 dir="ltr"><span style="font-size: large;">Reverting to the default theme</span></h5>
<div><span style="font-size: large;"> </span></div>
<p dir="ltr"><span style="font-size: large;">If you login as an administrator you can disable the themes in the admin panel from the optio Appearances---&gt;Themes, but if you are not an administrator you need to follow the same process as we have mentioned for plugins.</span></p>
<p><span style="font-size: large;"> </span></p>
<p dir="ltr"><span style="font-size: large;">Follow the below steps to reverting to the default theme:</span></p>
<ol>
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Login to your shared<a href="https://www.hostingraja.in/hosting/cpanel-hosting/"><b> hosting cPanel.</b></a></span></p>
</li>
</ol>
<ol start="2">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Go to the directory public_html/wp-content/themes</span></p>
</li>
</ol>
<ol start="3">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Note down the default theme, If there are several themes you need to revert back to the most recently used theme.</span></p>
</li>
</ol>
<ol start="4">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Go back to the cPanel home screen.</span></p>
</li>
</ol>
<ol start="5">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Open the phpmyadmin in the databases section.</span></p>
</li>
</ol>
<ol start="6">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Expand the database which you have assigned to the website.</span></p>
</li>
</ol>
<ol start="7">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Click on wp_options.</span></p>
</li>
</ol>
<ol start="8">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">You will see the template and stylesheet rows in the option_name column, In the option_value row you will see your current theme.</span></p>
</li>
</ol>
<ol start="9">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Double click on option_value in the template row, Type the default theme which you got from the step 3.</span></p>
</li>
</ol>
<ol start="10">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">Repeat step 9 for the stylesheet row. The default theme is now active.</span></p>
</li>
</ol>
<ol start="11">
<li dir="ltr">
<p dir="ltr"><span style="font-size: large;">If the previous theme was causing the issue the site should work now.</span></p>
</li>
</ol>
<div><span style="font-size: large;"><span style="font-size: large;"><br/>If you want to buy hosting, please see our <a href="https://www.hostingraja.in/">hosting</a> page.<br/> <br/><br/><br/></span></span><span style="font-size: large;"> </span></div> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="What is WordPress Multisite" aria-label="Previous article: What is WordPress Multisite" href="/docs/what-is-wordpress-multisite" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="Wordpress - malware / Phishing / hacked website , What to do ?" aria-label="Next article: Wordpress - malware / Phishing / hacked website , What to do ?" href="/docs/wordpress-malware-phishing-hacked-website-what-to-do" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>