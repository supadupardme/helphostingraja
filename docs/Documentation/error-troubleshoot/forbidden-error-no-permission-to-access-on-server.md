---
title: Forbidden Error no permission to access on server
excerpt: >-
  Encounter a 'Forbidden Error' on HostingRaja? Ensure file permissions and
  mod_security settings are configured correctly
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
  <h2 itemprop="headline">Forbidden Error no permission to access on server</h2>
</div>
<dl class="article-info muted">
  <dt class="article-info-term"></dt>
  <dd class="modified">
    <span class="icon-calendar" aria-hidden="true"></span>
    <time datetime="2024-01-02T10:19:13+00:00" itemprop="dateModified">
      Last Updated: 02 January 2024
    </time>
  </dd>
</dl>
<div itemprop="articleBody">
  <strong>What is the Issue?</strong><br />
  When selecting particular menu from the menu bar on the website or saving any data in forms is showing permission error.This means that you are not allowed to open the particular file or folder on HostingRaja VPS or <a href="https://www.hostingraja.in/cloud/" target="_blank" rel="noopener noreferrer">Cloud server</a>.This may be due to missing files and folders or other security restrictions in the Secured Server. A server is called as secured server when it is capable of isolating the spammers, harmful executable files on the server.when you have a secured server you can be assured about the error free data transmission.<br /><br />
  <strong>Why has this issue occurred?</strong><br />
  This problem or issues may be due to any one of the following problem with HostingRaja <a href="https://www.hostingraja.in/server/vps-servers/" target="_blank" rel="noopener noreferrer">VPS</a> or cloud:<br /><br />
  The folders and files where you have placed your source code i.e public_html, is not given with proper permissions.<br />
  Ensure that each directory to which apache has access can be configured with respect to which services and features are allowed and /or disabled in that directory and its subdirectories.<br /><br />
  Mod_security is an apache module that helps to protect your website from various attacks. It is used to block commonly known exploits by use of regular expressions and rule set. If the file/folder which is trying to break the mod security rule set will not be allowed to move further. The mod security works for apache and it blocks some of the functions which is captured by it as it is harmful. some times it simply turns off the apache when some parameters which are not defiend and are acting within its limits.
  <strong>How can we prevent it?</strong><br />
  <strong>Follow any one of the following steps to prevent from the problem which is mentioned above:</strong><br /><br />
  1. Make sure that the files and folder which is present under public_html where your source code is present is having 755 permission instead of 750 and sensitive file should have 700 permission.Using 750 equates to users having read, write, and execute, groups having read and execute, and finally, world i.e your visitors having absolutely zero access, thus they will be forbidden from accessing and/or viewing the contents.<br />
  Use the following command to change file/folder permissions:<br />
  chmod -R 755 foldername/<br /><br />
  Note: Directories should have the execution permission.<br />
  File should have read permission.<br />
  Do not add execute permission for files.<br /><br />
  2. When it comes to the apache configuration, you need to check the below possibilities:<br />
  a) When you access a directory and there is no default file found in the directory <br />
  Apache options indexes is not abled for the particular directory For example,<br />
  DirectoryIndex index.html default.php welcome.php<br /><br />
  Make sure that You should not allow directory listing unless REALLY needed. Restrict the default index Directory Index to the minimum.<br /><br />
  b) By default, your global directory settings under <br />
  /etc/sentora/configs/apache/domains/domainname.conf looks like :<br />
  <br />
  &lt;Directory "/var/sentora/hostdata/demo/public_html/"&gt;<br />
  Options +FollowSymLinks -Indexes +ExecCGI<br />
  AllowOverride All<br />
  Require all granted<br />
  &lt;/Directory&gt;<br /><br />
  <strong>If these lines are missing you need to add it to this file and restart the apache Service using the command:</strong><br />
  <br />
  service httpd restart<br /> <br />
  Now clear your browser cookies and cache and check whether it is possible to <br />
  Access the folder /file.You can also check the error logs and access log of<br />
  Particular <a href="https://www.hostingraja.in/domains/">domain name</a> under<a href="https://www.hostingraja.in/"><b> HostingRaja</b></a> Log viewer module.<br /><br />
  Regarding this you can contact our support team for further details if you have any clarifications before doing any changes.<br /><br />
  3. Mod security is a software that we configure alongside web servers to secure them on all HostingRaja VPS and cloud servers. Mod-security has certain rules to filter all incoming requests to the websites in your server.<br /><br />
  These rules protect the websites in your server from hack attempts or code injections, which can cause malicious scripts to enter your server and mess it up entirely.<br /><br />
  Any request to the <a href="https://www.hostingraja.in/server/dedicated-servers/">web server</a> are filtered by these mod-security rules and if matched against any rule, the user would be denied access to the page and Forbidden error would be displayed. The mod security set certain hirarchy for itself as a filtering action and when one of the web server doesn't obey its limitations it simply blocks to avoid more losses. <br /><br />
  One of the default rules that Apache’s mod_security looks for is GET or POST in form submissions. This rule can lead to many contact forms giving 403 server errors in sites.<br /><br />
  Example,<br />
  Special Characters present in the arguments passed on the browser url.<br />
  Passing sql injection attack ex: abcd.com/new.php?id=%27<br /><br />
  To Resolve this mod security issue you need to contact our support team they will guide you regarding this issue and resolve the problem.
</div>
<ul class="pager pagenav">
  <li class="previous">
    <a class="hasTooltip" title="My Website is loading slow" aria-label="Previous article: My Website is loading slow" href="/docs/my-website-is-loading-slow-2" rel="prev">
      <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span>
    </a>
  </li>
  <li class="next">
    <a class="hasTooltip" title="Explained - FAQ on server load high or more." aria-label="Next article: Explained - FAQ on server load high or more." href="/docs/explained-faq-on-server-load-high-or-more" rel="next">
      <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span>
    </a>
  </li>
</ul>
```