---
title: How to exclude a folder from WordPress permalink
excerpt: >-
  Essentials of launching your Cloud Office startup with this comprehensive
  tutorial. Hosted by HostingRaja.
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
    <h1 dir="ltr" style="text-align: center;"><span style="font-size: x-large;"><strong>How to exclude a folder from WordPress permalink</strong></span></h1>
    <p> </p>
    <p dir="ltr"><strong><span style="font-family: georgia, palatino;"><em><span style="font-size: x-large;">What is Wordpress?</span></em></span><br /><br /></strong></p>
    <p dir="ltr">WordPress is<strong> free and open-source management</strong> system through you can use to create an attractive website or blog. It just may be the simple and most flexible blogging and website content management system (CMS) for the learner. <a href="https://www.hostingraja.in/hosting/wordpress-hosting/">WordPress Websites</a> is works on PHP hosting.<br /><br /></p>
    <p dir="ltr">It’s probably the simple and most strong blogging and website content management system in existence today through WordPress you can build and manage your own <strong>full-featured website</strong> using just your web browser.<br /><br /></p>
    <p dir="ltr"><strong><span style="font-size: x-large; font-family: georgia, palatino;"><em>What are the Advantages of Wordpress?</em></span><br /><br /></strong></p>
    <p dir="ltr">1. WordPress is Open Source management system.</p>
    <p dir="ltr">2. It’s user-friendly.</p>
    <p dir="ltr">3. It’s flexible and extensible</p>
    <p dir="ltr">4. WordPress is SEO-friendly.</p>
    <p dir="ltr">5. Through Wordpress, you can control your own content.</p>
    <p dir="ltr"><strong> Note:</strong> Apart from the above features in this article we are discussing the Permalinks which is one of the main features of the WordPress.<br /><br /></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: georgia, palatino;"><em><strong>What is Permalink?<br /><br /></strong></em></span></p>
    <p dir="ltr">Permalink<strong> is the link to a separate blog post.</strong> Those are important because if you ever need to link to an accurate blog entry you can use the permalink as your link. Permalinks are the persistent URL to your separate pages and blog posts. The Settings Permalinks Screen authorize you to select your default permalink construction. You can select from usual settings or create custom URL construction. You have to click the Save Changes button at the bottom of the screen for new settings to take reflect.<br /><br /></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: georgia, palatino;"><em><strong>What are the Benefits of Permalink?<br /><br /></strong></em></span></p>
    <p dir="ltr">1. Permalink is easy to remember.</p>
    <p dir="ltr">2. It is relevant.</p>
    <p dir="ltr">3. It is short and simple</p>
    <p dir="ltr">4. It provides SEO benefits.<br /><br /></p>
    <p dir="ltr"><strong>Structure of WordPress Permalinks settings.<br /><br /></strong></p> <img src="https://image.hostingraja.in/images/how-to-exclude-a-folder-from-wordpress-permalink.png" alt="Structure of WordPress Permalinks settings" width="322" height="369" border="0" /><br /><br />
    <p dir="ltr"><strong><span style="font-family: georgia, palatino; font-size: x-large;"><em>How to exclude a folder from WordPress permalinks?</em></span><br /><br /></strong></p>
    <p dir="ltr">If you want to exclude the particular subfolders from the WordPress rewrite rules, so you need to modify the .htaccess file and change the bold line below:</p>
    <p dir="ltr">Kindly login to cpanel and edit the .htacccess file.</p>
    <p dir="ltr"># BEGIN WordPress</p>
    <p dir="ltr">&lt;IfModule mod_rewrite.c&gt;</p>
    <p dir="ltr">RewriteEngine On</p>
    <p dir="ltr">RewriteBase /</p>
    <p dir="ltr">RewriteCond %{REQUEST_FILENAME} !-f</p>
    <p dir="ltr">RewriteCond %{REQUEST_FILENAME} !-d</p>
    <p dir="ltr">RewriteRule . /index.php [L]</p>
    <p dir="ltr">&lt;/IfModule&gt;</p>
    <p dir="ltr"># END WordPress</p>
    <p dir="ltr">you have to replace the bold line to</p>
    <p dir="ltr">RewriteRule ./ /index.php [L]<br /><br /></p>
</div>
<ul class="pager pagenav">
    <li class="previous"> <a class="hasTooltip" title="How to create a MySQL / MSSQL database in Plesk" aria-label="Previous article: How to create a MySQL / MSSQL database in Plesk" href="/how-tos/how-to-create-a-mysql-mssql-database-in-plesk" rel="prev"> <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a> </li>
    <li class="next"> <a class="hasTooltip" title="How to solve ERROR: Connection dropped by imap server Query: SELECT &quot;INBOX&quot; in Webmail " aria-label="Next article: How to solve ERROR: Connection dropped by imap server Query: SELECT &quot;INBOX&quot; in Webmail " href="/how-tos/how-to-solve-error-connection-dropped-by-imap-server-query-select-inbox-in-webmail-cpanel" rel="next"> <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a> </li>
</ul>