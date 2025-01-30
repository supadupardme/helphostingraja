---
title: Already WordPress is installed in softaculous
excerpt: >-
  Resolve missing domain in Softaculous for WordPress installation by editing
  installations.php via File Manager
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
<div class="page-header">
<h2 itemprop="headline">
Already WordPress is installed in softaculous, But from the softaculous List, the Domain is missing and not able to install the WordPress</h2>
</div>
<dl class="article-info muted">
<dt class="article-info-term">
</dt>
<dd class="modified">
<span class="icon-calendar" aria-hidden="true"></span>
<time datetime="2021-08-04T14:04:50+00:00" itemprop="dateModified">
Last Updated: 04 August 2021 </time>
</dd>
</dl>
<div itemprop="articleBody">
<span style="font-size: 18pt;"><strong>Already WordPress is installed in softaculous, But from the softaculous List, the Domain is missing and not able to install the WordPress.<br/><br/></strong><br/></span>
<ol>
<li>
<p><span style="font-weight: 400; font-size: 12pt;"> Login to Cpanel.</span></p>
</li>
<li>
<p><span style="font-weight: 400; font-size: 12pt;">Click on "File Manager" and open the installations.php file under the .softaculous folder.</span></p>
</li>
<li>
<p><span style="font-weight: 400; font-size: 12pt;">Copy the content and paste it in the <a href="https://www.unserialize.com/">https://www.unserialize.com/</a> website input box and click on the "unserialize" button, this will give the result of the file content in the array format.</span></p>
</li>
<li>
<p><span style="font-weight: 400; font-size: 12pt;">Identify the particular array of the domain and remove the array from the installations.php file<br/><br/><img src="https://image.hostingraja.in/images/softaculous-unserialize.png" alt="softaculous-unserialize" width="300" height="603" /></span></p>
<p> </p>
<img src="https://image.hostingraja.in/images/softaculous-remove.png" alt="softaculous-remove" width="463" height="321" /></li>
<li>
<p><span style="font-size: 12pt;"><span style="font-weight: 400;">In 1st line of the installations.php, the WordPress installation count is mentioned. For example, a:4 where "4" is the WordPress installation count.</span><span style="font-weight: 400;"><br/></span></span></p>
<span style="font-size: 12pt;"><span style="font-weight: 400;"><img src="https://image.hostingraja.in/images/softaculous-less-1.png" alt="softaculous-less-1" width="356" height="186" /></span></span></li>
<li>
<p><span style="font-weight: 400; font-size: 12pt;">Subtract by 1 the count of the WordPress installation and save the file.</span></p>
</li>
<li>
<p><span style="font-weight: 400; font-size: 12pt;">Still facing the same issue rise ticket to softaculous support team for a solution.</span></p>
</li>
</ol> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="PHP version change or WordPress version change" aria-label="Previous article: PHP version change or WordPress version change" href="/docs/php-version-change-or-wordpress-version-change" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="Quick wordpress Migration With Migration Guru Plugin" aria-label="Next article: Quick wordpress Migration With Migration Guru Plugin" href="/docs/quick-wordpress-migration-with-migration-guru-plugin" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>