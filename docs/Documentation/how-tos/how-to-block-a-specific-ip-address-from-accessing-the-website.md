---
title: How to block a specific IP address from accessing the website
excerpt: Best Linux, Windows, Unlimited plans wirh 55% OFFER
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
    <h1 dir="ltr"><span style="font-size: xx-large;"><strong>How to block a specific IP address from accessing the website </strong></span></h1> <br />
    <p dir="ltr">If you've got annoying website visitors, spammers, or site scrapers you'll find it helpful to block these users from accessing your site content. You'll be able to block unauthorized unhealthy users by their IP address with the help of a .htaccess file. Before you begin, you need to have the FTP login details, an FTP client, and the Plain text editor. <span data-sheets-value="{&quot;1&quot;:2,&quot;2&quot;:&quot;At the lower part of the screen, there will be the IP Blocker page, you'll see a segment called Currently-Blocked IP Addresses. This gives a rundown of IP addresses that are right now blocked from getting to your server. To lift access limitations, utilize the Delete button close to every IP address or reach.&quot;}" data-sheets-userformat="{&quot;2&quot;:897,&quot;3&quot;:{&quot;1&quot;:0},&quot;10&quot;:1,&quot;11&quot;:4,&quot;12&quot;:0}">At the lower part of the screen, there will be the IP Blocker page, you'll see a segment called Currently-Blocked IP Addresses. This gives a rundown of IP addresses that are right now blocked from getting to your server. To lift access limitations, utilize the Delete button close to every IP address or reach.</span></p> <br />
    <p dir="ltr"><img src="https://image.hostingraja.in/images/articles/how-to-block-a-specific-ip-address-from-accessing-the-website-in-cloud-server.png" alt="How to block a specific IP address from accessing the website" border="0" /></p> <br />
    <p dir="ltr"><span style="font-size: x-large;"><strong>Steps to block a specific IP address from accessing the website:</strong></span></p> <strong><br /></strong>
    <p dir="ltr"><strong>Secure directories by IP address and domain:</strong></p> <br />
    <p dir="ltr">In the below example, all the IP addresses and domains are acceptable, except for 123.456.789 and abcdef.co:</p> <br />
    <p dir="ltr"># allow all except those indicated here</p>
    <p dir="ltr">&lt;Files *&gt;</p>
    <p dir="ltr">order allow,deny</p>
    <p dir="ltr">allow from all</p>
    <p dir="ltr">deny from 123.456.789</p>
    <p dir="ltr">deny from .*abcdef\.co.*</p>
    <p dir="ltr">&lt;/Files&gt;</p> <br /><br />
    <p dir="ltr">In the below example, all the IP addresses are denied access except only for 123.456.789 and abcdef.co:</p> <br />
    <p dir="ltr"># Deny access to everyone, except those listed here:</p>
    <p dir="ltr">&lt;Files *&gt;</p>
    <p dir="ltr">order deny,allow</p>
    <p dir="ltr">deny from all</p>
    <p dir="ltr">allow from 123.456.789</p>
    <p dir="ltr">allow from .*abcdef\.co.*</p>
    <p dir="ltr">&lt;/Files&gt;</p> <br />
    <p dir="ltr">In the below example you will find the steps to block inappropriate visitors based on the <a href="https://www.hostingraja.in/domains/">domain name</a>. Simply replace "abcdef20″ and "abcdef30″ along with the offending domains of your requirement:</p> <br />
    <p dir="ltr"># block visitors referred from indicated domains</p>
    <p dir="ltr">RewriteEngine on</p>
    <p dir="ltr">RewriteCond %{HTTP_REFERER} abcdef20\.co [NC,OR]</p>
    <p dir="ltr">RewriteCond %{HTTP_REFERER} abcdef30\.co [NC]</p>
    <p dir="ltr">RewriteRule .* - [F]</p>
    <div> </div>
</div>
<ul class="pager pagenav">
    <li class="previous"> <a class="hasTooltip" title="How to take backup of emails and restore in shared Linux webmail" aria-label="Previous article: How to take backup of emails and restore in shared Linux webmail" href="/how-tos/how-to-take-backup-of-emails-and-restore-in-shared-linux-webmail" rel="prev"> <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a> </li>
    <li class="next"> <a class="hasTooltip" title="How to Use HostingRaja Site Builder" aria-label="Next article: How to Use HostingRaja Site Builder" href="/how-tos/how-to-use-hostingraja-site-builder" rel="next"> <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a> </li>
</ul>