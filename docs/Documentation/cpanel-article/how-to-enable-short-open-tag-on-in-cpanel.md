---
title: How to enable “short-open-tag” On in cPanel
excerpt: ''
deprecated: false
hidden: false
metadata:
  title: ''
  description: ''
  robots: index
next:
  description: ''
---
<dl class="article-info muted">
<dt class="article-info-term">
</dt>
<dd class="modified">
<span class="icon-calendar" aria-hidden="true"></span>
<time datetime="2021-08-27T13:26:25+00:00" itemprop="dateModified">
Last Updated: 27 August 2021 </time>
</dd>
</dl>
<div itemprop="articleBody">
<p dir="ltr">short_open_tag is a instruction that determines whether or not PHP will recognize code written between tags. Generally php users used tags to write php code. Moreover it is been recommended for several years that not use the short tag “short cut” and instead to use the full tag combination. And if you want to use PHP in combination with XML, then in that case you can disable this option in order to use inline.<br/><br/>It is very easy to configure php.ini file in cpanel, below are the steps to be followed to configure php.ini file :</p>
<ol>
<li dir="ltr">
<p dir="ltr">As usual login to your cpanel using your user name and password.</p>
</li>
<li dir="ltr">
<p dir="ltr">Once you login to your cpanel you will see the home page. In home page search for the option called “ php”. Once you search for the option, you can see the below image. </p>
</li>
</ol>
<p dir="ltr"><img src="https://image.hostingraja.in/images/helphostingraja/short-open-tag.webp" width="624" height="356" border="0" /></p>
<p dir="ltr"> Once you see the above image click on the option called “select PHP version”.  After clicking on that option, PHP selector / extensions page will appear, Like the below image.<br/><br/></p>
<p dir="ltr"><img src="https://image.hostingraja.in/images/helphostingraja/short-open-tag-one.webp" width="624" height="320" border="0" /></p>
<p dir="ltr"> <br/>Once this page is displayed, you will see the option called “switch to PHP options” at top and right side of the page. click on that option after clicking that you can see the below page.</p>
<p dir="ltr"> </p>
<p dir="ltr"><img src="https://image.hostingraja.in/images/helphostingraja/short-open-tag-two.webp" width="624" height="368" border="0" /></p>
<p dir="ltr"><span id="docs-internal-guid-89b5f711-7fff-14d8-d982-a8adfe4d25d1">In this page you can see the option “short_open_tag” . if you want to enable this option, select for “On” option . once it is done,click on the save button to save the changes you have made.</span></p>
<br/>
<p class="aisa-help-page-content"> </p>
<p class="aisa-help-page-content">And today most of the people are using the XML formate where it use these tags by other languages, so this will make your server to get confused and it will lead to having wrong parsing of code in the wrong context. And if you want to use PHP in combination with XML, you can disable this option in order to use inline.</p>
<br/>
<p class="aisa-help-page-content">"Generally, in a PHP script, we use tags, short_open_tag is a configuration directive in the php.ini file. It will describe PHP whether the short form """" of PHP’s open tag should be allowed or not for coding in php. The php.ini will provide you to enable PHP short tags ( ). PHP.ini allows you the option to use short style opening tags for PHP code like</p>
<div><span style="font-size: 12.16px;"> </span></div> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="Reseller cPanel invoice credits" aria-label="Previous article: Reseller cPanel invoice credits" href="/docs/reseller-cpanel-invoice-credits" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="how-to-calculate-my-cpu-usage-in-cpanel" aria-label="Next article: how-to-calculate-my-cpu-usage-in-cpanel" href="/docs/how-to-calculate-my-cpu-usage-in-cpanel" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>