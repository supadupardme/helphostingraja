---
title: >-
  How to solve ERROR: Connection dropped by imap server Query: SELECT "INBOX" in
  Webmail
excerpt: >-
  How to solve the Connection dropped by IMAP server Query ERROR and understand
  what is webmail and IMAP protocol. Get assistance if needed.
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
    <h1 dir="ltr" style="text-align: center;"><span style="font-size: 18pt;">How to solve ERROR: Connection dropped by imap server Query: SELECT "INBOX" in Webmail</span></h1>
    <p dir="ltr"><span style="font-size: x-large; font-family: georgia, palatino;"><strong><em> </em></strong></span></p>
    <p><span style="font-size: 18pt;"><b>The Errors and its solution:</b></span></p>
    <p>ERROR is as shown below :</p>
    <p><b>Connection dropped by IMAP server Query: SELECT "INBOX"</b></p>
    <p dir="ltr"><strong><em> </em></strong></p>
    <p>You get this above error gets when the dovecot indexes are corrupted. To fix this simply purge the indexes</p>
    <p dir="ltr"><strong><em> </em></strong></p>
    <p>The exact error message could be obtained by using below command -</p>
    <p dir="ltr"><strong><em> </em></strong></p>
    <p><b>tail - f /var/log/maillog</b></p>
    <p dir="ltr"><strong><em> </em></strong></p>
    <p>"Error: broken sync positions in index file /home/user/mail/domainname.com/user/dovecot.index" and "Warning:fscking index file /home/user/mail/domainname.com/user/dovecot.index"</p>
    <p dir="ltr"><strong><em> </em></strong></p>
    <p><b>Here is the Solution</b></p>
    <p dir="ltr"><strong><em> </em></strong></p>
    <p>Solution 1: Delete all files named "dovecot" in the path "/home/cpanel_username/mail/domainname.com/user/maildir" using :</p>
    <p dir="ltr"><strong><em> </em></strong></p>
    <p> <b>rm -f dovecot*</b></p>
    <p dir="ltr"><strong><em> </em></strong></p>
    <p>OR</p>
    <p>Solution 2: You can simply rename the dovecot.index page as:</p>
    <p dir="ltr"><strong><em> </em></strong></p>
    <p><b> mv dovecot.index dovecot.index_bk</b></p>
    <p dir="ltr"><strong><em> </em></strong></p>
    <p>Solution 3: At times you might face this error if when the user exceeds the Quota so you try solving this error by increasing the email quota.</p>
    <p><br /><br /></p>
    <p><b>In this pages, we will discuss about </b>How to solve ERROR: Connection dropped by IMAP server Query: SELECT "INBOX" which is shown below, before that let us understand what is webmail and IMAP protocol.<br /><br /><img src="https://image.hostingraja.in/images/helphostingraja/errror-in-webmail.webp" alt="Error in webmail" width="293" height="193" /><br /><br /></p>
    <p dir="ltr"><b><i>What is Webmail?</i></b></p>
    <p><a href="https://www.hostingraja.in/email/email-solutions/">Webmail is an email system</a>, w</p>
    <p dir="ltr"><span style="font-size: x-large; font-family: georgia, palatino;"><strong><em> </em></strong></span></p>
    <p><b><i>Steps for logging into webmail.</i></b></p>
    <p><b>Step 1:</b><span style="font-weight: 400;"> Use example.com/webmail Be sure to replace example.com with your actual domain name, eg if your <a href="https://www.hostingraja.in/domains/">cheap domain</a> name is abc.com then you need to use abc.com/webmail.</span></p>
    <p><span style="font-weight: 400;">You can also use the below </span></p>
    <p><span style="font-weight: 400;">For secure access</span></p>
    <p><span style="font-weight: 400;">https://ServerIP:2096 - Access your Webmail with https and your IP address https://yourdomainname.com:2096 - Access your Webmail with https and your domain name </span></p>
    <p><span style="font-weight: 400;">For insecure access:</span></p>
    <p><span style="font-weight: 400;">http://ServerIP:2095 - with http and your IP address.</span></p>
    <p><span style="font-weight: 400;">http://yourdomainname.com:2095 - Access your Webmail with http and your <a href="https://www.hostingraja.in/domains/">domain and hosting</a></span></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: georgia, palatino;"><strong><em> </em></strong></span></p>
    <p><b>Step 2:</b><span style="font-weight: 400;"> Enter your username and password and then click ok. Enter your full email address all in lowercase.</span></p>
    <p><b>Step 3:</b><span style="font-weight: 400;"> Then click on login </span></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: georgia, palatino;"><strong><em> </em></strong></span></p>
    <p><b>Examples of webmail software are Roundcube and SquirrelMail and Horde.</b></p>
    <p><b><i>What is Roundcube?</i></b></p>
    <p><span style="font-weight: 400;">Roundcube is a</span><b> multilingual IMAP client which is web-based</b><span style="font-weight: 400;"> with an application-like user interface. Roundcube is a free and open-source software where clients log in and view, send and reply to emails.</span></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: georgia, palatino;"><strong><em> </em></strong></span></p>
    <p><b><i>What is SquirrelMail?</i></b></p>
    <p><span style="font-weight: 400;">SquirrelMail is open Source webmail with a </span><b>full-featured e-mail application</b><span style="font-weight: 400;">. SquirrelMail offers Imap proxy and email application at once. Where users can use mail service to send and receive emails.</span></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: georgia, palatino;"><strong><em> </em></strong></span></p>
    <p><b><i>What is Horde.?</i></b></p>
    <p><span style="font-weight: 400;">Horde is a Groupware Webmail Edition is a free, enterprise-ready. web-based communication. where users can send, </span><b>read and organize email messages</b><span style="font-weight: 400;"> and share and manage - contacts, tasks, notes, files and bookmarks with the standards compliant components from the Horde.</span></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: georgia, palatino;"><strong><em> </em></strong></span></p>
    <p><b><i>What's the difference between RoundCube, Horde, and SquirrelMail?</i></b></p>
    <ul>
        <li style="font-weight: 400;"><span style="font-weight: 400;">RoundCube, Horde, and SquirrelMail this are three webmail available applications to everyone. Each of them has the same login page. YourDomain.com/webmail with different interface and features but they all access the same mailbox.</span></li>
    </ul>
    <ul>
        <li style="font-weight: 400;"><span style="font-weight: 400;">Horde may have the most features: a phone device interface; calendar and task organizer, custom filters; along with the ability to share content with others.</span></li>
    </ul>
    <ul>
        <li style="font-weight: 400;"><span style="font-weight: 400;">RoundCube and SquirrelMail are more streamlined with few of the features and both are easy to use. We encourage our clients to work with each application and find that one that suits their needs.</span></li>
    </ul>
    <p dir="ltr"><span style="font-size: x-large; font-family: georgia, palatino;"><strong><em> </em></strong></span></p>
    <p><b><i>What is IMAP?</i></b></p>
    <p><span style="font-weight: 400;">IMAP is an Internet Message Access Protocol. which is used by e-mail clients to get the messages from the mail server over a TCP/IP connection In other words IMAP is basically an internet mail protocol which is used for accessing email on a remote web server from a local client. It is commonly used for retrieving emails it is supported by all modern email clients and web servers.IMAP also allows simultaneous access for multiple clients hence IMAP configuration is suitable when you are planning to use email from different locations/devices or if it email is managed by multiple users</span></p>
    <p><span style="font-weight: 400;">T</span><span style="font-weight: 400;">he IMAP -internet mail protocol works on two ports by default :</span></p>
    <ul>
        <li style="font-weight: 400;"><b>Port 143</b><span style="font-weight: 400;"> - it is default IMAP non-encrypted port</span></li>
        <li style="font-weight: 400;"><b>Port 993</b><span style="font-weight: 400;"> - it is default IMAP encrypted port - used when you need to connect using IMAP securely </span></li>
    </ul> <br />
    <p><b>If you need any assistance, feel free to contact our technical team members as they are available 24/7 via phone call, chat, <a href="https://support.hostingraja.in/" target="_blank" rel="noopener noreferrer">ticket system</a>.</b></p>
    <p dir="ltr"><span style="font-size: x-large; font-family: georgia, palatino;"><strong><em> </em></strong></span></p>
</div>
<ul class="pager pagenav">
    <li class="previous"> <a class="hasTooltip" title="How to exclude a folder from WordPress permalink" aria-label="Previous article: How to exclude a folder from WordPress permalink" href="/docs/how-to-exclude-a-folder-from-wordpress-permalink" rel="prev"> <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a> </li>
    <li class="next"> <a class="hasTooltip" title="How to set redirection for without WWW to with WWW URL in Tomcat using UrlRewriteFilter" aria-label="Next article: How to set redirection for without WWW to with WWW URL in Tomcat using UrlRewriteFilter" href="/docs/how-to-set-redirection-for-without-www-to-with-www-url-in-tomcat-using-urlrewritefilter" rel="next"> <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a> </li>
</ul>
