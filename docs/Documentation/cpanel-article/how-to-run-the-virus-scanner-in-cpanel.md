---
title: how-to-run-the-virus-scanner-in-cpanel
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

```mdx
<div class="page-header">
</div>
<dl class="article-info muted">
<dt class="article-info-term">
</dt>
<dd class="modified">
<span class="icon-calendar" aria-hidden="true"></span>
<time datetime="2024-01-07T05:26:23+00:00" itemprop="dateModified">
Last Updated: 07 January 2024 </time>
</dd>
</dl>
<div itemprop="articleBody">
<p dir="ltr">If you are using cPanel for a website as WHM then many of the cPanel comes with ClamAV virus scanner feature, which helps you to safeguard against potential threats on your server. Not only that you can also run an on-demand scan of your website files to see whether if there are any files infected with a virus or not. And ClamAV is an open source antivirus and it is also very powerful because in ClamAV it uses its extensive database to detect several types of potential threats like viruses, Trojan horses, malware, malicious scripts etc. and helps your website to free from virus.<br/><br/>The below mentioned steps are used to run the virus scanner in cPanel.</p>
<p dir="ltr">1. Login to cPanel. (You can use the username and password sent you along with signup or If you are customer of some reseller, then you need to contact you <a href="https://www.hostingraja.in/" target="_blank" rel="noopener noreferrer">hosting provider</a> for username password). The loging URL for the control panel will be domainname.com:2082, In case, If you forget your UN/PWD, you can request for the same)<br/><br/></p>
<p dir="ltr">2. In <strong>“Advanced”</strong> section, click on the <strong>“Virus Scanner”</strong>. The Virus scanner is a in-built application comes with control panel. It can scan for most of the common types of malware/phishing and hacked files. The time taken to scan the entire public_html might take more time, based on the numer of files. While scanning, If the software finds any suspiciuos file, then it will move to a specific folder (quarantine folder). Those moved files, will be displayed at the end of the scanning, It is up to the user to fix the problem. Once the file is moved, your website may not be working properly.  So, It is strongly recommened to take the backup of your working website, before running the virus scanner.</p>
<p dir="ltr"> </p>
<p dir="ltr"><img src="https://image.hostingraja.in/images/helphostingraja/virus-scanner.webp" width="624" height="228" border="0" /></p>
<p dir="ltr"> </p>
<p dir="ltr">3. Select the service to scan.</p>
<ul style={{ marginLeft: "30px" }}>
<li>Scan Mail — Scans all of your account's mail folders.</li>
<li>Scan Entire Home Directory — Scans your account's home directory.</li>
<li>Scan Public FTP Space — Scans all of the folders that you can publicly access through FTP services.</li>
<li>Scan Public Web Space — Scans all of the folders that you can publicly access through the web.</li>
</ul>
<p dir="ltr"><img src="https://image.hostingraja.in/images/helphostingraja/virus-scanner-one.webp" width="624" height="231" border="0" /></p>
<p dir="ltr"><span id="docs-internal-guid-b7f2d52f-7fff-c5fa-e2ad-56eed40f68c1"><br/>4. Click on <strong>“Scan Now”</strong> button. A scan may require several minutes to complete. After the scan completes, the system returns you to the Virus Scanner interface.<br/></span> </p>
<p class="aisa-help-page-content">Using this virus scanner or ClamAV virus is very useful for every user. And ClamAV Virus Scanner software successfully scans the services of a<a href="/cpanel-article/how-to-create-a-cpanel-account-in-whm"><b> cPanel account</b></a> and detects harmful software and malware. Not only that using ClamAV virus for your website will also help to detect a possible security threat that prompts the user to take necessary action.</p>
<p class="aisa-help-page-content">The Virus Scanner scans your Control Panel account's services for malicious software. If the Virus Scanner identifies a potential threat, the system prompts you to perform the appropriate action. During the scan a new interface will appear which will display the following:- Files -The number of files that the scan processed out of the total number of files that exist in the specified directory. Data - The amount of data processed out of the total amount of data that exists in the specified directory. Scanner Progress- Displays the scan's progress. Affected Files - The files that the scan reported to contain malicious software.</p> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="how-to-calculate-my-cpu-usage-in-cpanel" aria-label="Previous article: how-to-calculate-my-cpu-usage-in-cpanel" href="/docs/how-to-calculate-my-cpu-usage-in-cpanel" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="How to configure Email authentication in cPanel" aria-label="Next article: How to configure Email authentication in cPanel" href="/docs/how-to-configure-email-authentication-in-cpanel" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
```