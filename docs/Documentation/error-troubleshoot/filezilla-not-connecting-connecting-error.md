---
title: Filezilla not connecting, Connecting Error
excerpt: >-
  FileZilla is a popular, free, open-source software for transferring files
  securely between local PCs and servers
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
Filezilla not connecting, Connecting Error</h2>
</div>
<dl class="article-info muted">
<dt class="article-info-term">
</dt>
<dd class="modified">
<span class="icon-calendar" aria-hidden="true"></span>
<time datetime="2021-08-27T13:37:39+00:00" itemprop="dateModified">
Last Updated: 27 August 2021 </time>
</dd>
</dl>
<div itemprop="articleBody">

<h2><span style="font-weight: 400;">What is Filezilla?</span></h2>
<p><span style="font-weight: 400;">FileZilla is one of the most popular and free open-source applications which is used in transferring files from local PC and remote servers. FileZilla traditionally supports the File Transfer Protocol over the Transport Layer Security. This software of FileZilla is available on different platforms and it's absolutely free.</span></p>
<p><span style="font-weight: 400;">FTPS is less firewall-friendly when compared to SFTP as it requires opening a number of ports in the operation. </span></p>
<strong style="margin: 0px; padding: 0px; border: 0px; font-size: 14px; vertical-align: baseline; color: #444444; font-family: 'Open Sans', Helvetica, Arial, sans-serif; font-style: normal; font-variant: normal; letter-spacing: normal; line-height: 24px; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: #ffffff;"><br/>Steps to Fix the “Unable to connect” issue<br/></strong><br style="color: #444444; font-family: 'Open Sans', Helvetica, Arial, sans-serif; font-size: 14px; font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 24px; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: #ffffff;" /><span style="color: #444444; font-family: 'Open Sans', Helvetica, Arial, sans-serif; font-size: 14px; font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 24px; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-stroke-width: 0px; display: inline !important; float: none; background-color: #ffffff;">1) Error </span><strong style="margin: 0px; padding: 0px; border: 0px; font-size: 14px; vertical-align: baseline; color: #444444; font-family: 'Open Sans', Helvetica, Arial, sans-serif; font-style: normal; font-variant: normal; letter-spacing: normal; line-height: 24px; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: #ffffff;">“Server sent passive reply with unroutable address. Using server address instead.”</strong><br/><br/><img title="Filezilla-connecting-error" src="https://image.hostingraja.in/images/Filezilla-connecting-error.jpg" alt="Filezilla-connecting-error" width="100%" height="371" border="0" /><br/><br/><span style="color: #444444; font-family: 'Open Sans', Helvetica, Arial, sans-serif; font-size: 14px; font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 24px; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-stroke-width: 0px; display: inline !important; float: none; background-color: #ffffff;">This type of issue comes occasionally because the server is unable to connect in passive mode<br/><br/></span><span style="color: #444444; font-family: 'Open Sans', Helvetica, Arial, sans-serif; font-size: 14px; font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 24px; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-stroke-width: 0px; display: inline !important; float: none; background-color: #ffffff;">2) Switch to Active mode in File Zilla and you are in.<br/></span><br style="color: #444444; font-family: 'Open Sans', Helvetica, Arial, sans-serif; font-size: 14px; font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 24px; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: #ffffff;" /><span style="color: #444444; font-family: 'Open Sans', Helvetica, Arial, sans-serif; font-size: 14px; font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 24px; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-stroke-width: 0px; display: inline !important; float: none; background-color: #ffffff;">Goto </span><strong style="margin: 0px; padding: 0px; border: 0px; font-size: 14px; vertical-align: baseline; color: #444444; font-family: 'Open Sans', Helvetica, Arial, sans-serif; font-style: normal; font-variant: normal; letter-spacing: normal; line-height: 24px; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-stroke-width: 0px; background-color: #ffffff;">File Zilla &gt;&gt; Edit &gt;&gt; Settings &gt;&gt; Connection &gt;&gt; FTP &gt;&gt; Passive mode &gt;&gt; “Fall back to active”</strong><br/><img title="aws_ftp_active_mode" src="https://image.hostingraja.in/images/aws_ftp_active_mode.jpg" alt="aws_ftp_active_mode" width="100%" height="516" border="0" /><br/><br/><span style="color: #444444; font-family: 'Open Sans', Helvetica, Arial, sans-serif; font-size: 14px; font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 24px; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-stroke-width: 0px; display: inline !important; float: none; background-color: #ffffff;"><br/><span style="font-size: 14pt;"><strong>Alternative Method </strong></span><br/><br/><strong>FileZilla =&gt; Edit =&gt; Settings =&gt; FTP=&gt; Transfer Mode (Click on "Active" and then Tick "Allow fall back to ......"</strong><br/><img title="Filezilla-connection" src="https://image.hostingraja.in/images/Filezilla-connection.jpg" alt="Filezilla-connection" width="100%" height="535" border="0" /><br/><br/><br/> Re-connect your FTP user !!!<br/><br/>By following these steps you can fix the issue when the Filezilla is not connecting.</span><span style="color: #444444; font-family: 'Open Sans', Helvetica, Arial, sans-serif; font-size: 14px; font-style: normal; font-variant: normal; font-weight: normal; letter-spacing: normal; line-height: 24px; orphans: auto; text-align: start; text-indent: 0px; text-transform: none; white-space: normal; widows: auto; word-spacing: 0px; -webkit-text-stroke-width: 0px; display: inline !important; float: none; background-color: #ffffff;"><br/><br/></span> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="RAM Usage / Why more memory (RAM) is used by my server?" aria-label="Previous article: RAM Usage / Why more memory (RAM) is used by my server?" href="/docs/ram-usage-why-more-memory-ram-is-used-by-my-server" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="My Website is loading slow" aria-label="Next article: My Website is loading slow" href="/docs/my-website-is-loading-slow-2" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>
