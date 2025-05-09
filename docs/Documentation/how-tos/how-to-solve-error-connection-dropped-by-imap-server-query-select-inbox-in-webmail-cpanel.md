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
    <span style={{fontSize: "18pt"}}>How to solve ERROR: Connection dropped by imap server Query: SELECT "INBOX" in Webmail</span>
    <p dir="ltr"><span style={{fontSize: "x-large", fontFamily: "georgia, palatino"}}><strong> </strong></span></p>
    <p><span style={{fontSize: "18pt"}}>The Errors and its solution:</span></p>
    <p>ERROR is as shown below :</p>
    <p>Connection dropped by IMAP server Query: SELECT "INBOX"</p>
    <p dir="ltr"><strong> </strong></p>
    <p>You get this above error gets when the dovecot indexes are corrupted. To fix this simply purge the indexes</p>
    <p dir="ltr"><strong> </strong></p>
    <p>The exact error message could be obtained by using below command -</p>
    <p dir="ltr"><strong> </strong></p>
    <p>tail - f /var/log/maillog</p>
    <p dir="ltr"><strong> </strong></p>
    <p>"Error: broken sync positions in index file /home/user/mail/domainname.com/user/dovecot.index" and "Warning:fscking index file /home/user/mail/domainname.com/user/dovecot.index"</p>
    <p dir="ltr"><strong> </strong></p>
    <p>Here is the Solution</p>
    <p dir="ltr"><strong> </strong></p>
    <p>Solution 1: Delete all files named "dovecot" in the path "/home/cpanel_username/mail/domainname.com/user/maildir" using :</p>
    <p dir="ltr"><strong> </strong></p>
    <p> rm -f dovecot*</p>
    <p dir="ltr"><strong> </strong></p>
    <p>OR</p>
    <p>Solution 2: You can simply rename the dovecot.index page as:</p>
    <p dir="ltr"><strong> </strong></p>
    <p> mv dovecot.index dovecot.index_bk</p>
    <p dir="ltr"><strong> </strong></p>
    <p>Solution 3: At times you might face this error if when the user exceeds the Quota so you try solving this error by increasing the email quota.</p>
    <p><br /><br /></p>
    <p>In this pages, we will discuss about How to solve ERROR: Connection dropped by IMAP server Query: SELECT "INBOX" which is shown below, before that let us understand what is webmail and IMAP protocol.<br /><br /><br /><br /></p>
    <p dir="ltr">What is Webmail?</p>
    <p>Webmail is an email system, w</p>
    <p dir="ltr"><span style={{fontSize: "x-large", fontFamily: "georgia, palatino"}}><strong> </strong></span></p>
    <p>Steps for logging into webmail.</p>
    <p>Step 1:<span style={{fontWeight: 400}}> Use example.com/webmail Be sure to replace example.com with your actual domain name, eg if your cheap domain name is abc.com then you need to use abc.com/webmail.</span></p>
    <p><span style={{fontWeight: 400}}>You can also use the below </span></p>
    <p><span style={{fontWeight: 400}}>For secure access</span></p>
    <p><span style={{fontWeight: 400}}>https://ServerIP:2096 - Access your Webmail with https and your IP address https://yourdomainname.com:2096 - Access your Webmail with https and your domain name </span></p>
    <p><span style={{fontWeight: 400}}>For insecure access:</span></p>
    <p><span style={{fontWeight: 400}}>http://ServerIP:2095 - with http and your IP address.</span></p>
    <p><span style={{fontWeight: 400}}>http://yourdomainname.com:2095 - Access your Webmail with http and your domain and hosting</span></p>
    <p dir="ltr"><span style={{fontSize: "x-large", fontFamily: "georgia, palatino"}}><strong> </strong></span></p>
    <p>Step 2:<span style={{fontWeight: 400}}> Enter your username and password and then click ok. Enter your full email address all in lowercase.</span></p>
    <p>Step 3:<span style={{fontWeight: 400}}> Then click on login </span></p>
    <p dir="ltr"><span style={{fontSize: "x-large", fontFamily: "georgia, palatino"}}><strong> </strong></span></p>
    <p>Examples of webmail software are Roundcube and SquirrelMail and Horde.</p>
    <p>What is Roundcube?</p>
    <p><span style={{fontWeight: 400}}>Roundcube is a</span> multilingual IMAP client which is web-based<span style={{fontWeight: 400}}> with an application-like user interface. Roundcube is a free and open-source software where clients log in and view, send and reply to emails.</span></p>
    <p dir="ltr"><span style={{fontSize: "x-large", fontFamily: "georgia, palatino"}}><strong> </strong></span></p>
    <p>What is SquirrelMail?</p>
    <p><span style={{fontWeight: 400}}>SquirrelMail is open Source webmail with a </span>full-featured e-mail application<span style={{fontWeight: 400}}>. SquirrelMail offers Imap proxy and email application at once. Where users can use mail service to send and receive emails.</span></p>
    <p dir="ltr"><span style={{fontSize: "x-large", fontFamily: "georgia, palatino"}}><strong> </strong></span></p>
    <p>What is Horde.?</p>
    <p><span style={{fontWeight: 400}}>Horde is a Groupware Webmail Edition is a free, enterprise-ready. web-based communication. where users can send, </span>read and organize email messages<span style={{fontWeight: 400}}> and share and manage - contacts, tasks, notes, files and bookmarks with the standards compliant components from the Horde.</span></p>
    <p dir="ltr"><span style={{fontSize: "x-large", fontFamily: "georgia, palatino"}}><strong> </strong></span></p>
    <p>What's the difference between RoundCube, Horde, and SquirrelMail?</p>
    
        <span style={{fontWeight: 400}}>RoundCube, Horde, and SquirrelMail this are three webmail available applications to everyone. Each of them has the same login page. YourDomain.com/webmail with different interface and features but they all access the same mailbox.</span>
    
    
        <span style={{fontWeight: 400}}>Horde may have the most features: a phone device interface; calendar and task organizer, custom filters; along with the ability to share content with others.</span>
    
    
        <span style={{fontWeight: 400}}>RoundCube and SquirrelMail are more streamlined with few of the features and both are easy to use. We encourage our clients to work with each application and find that one that suits their needs.</span>
    
    <p dir="ltr"><span style={{fontSize: "x-large", fontFamily: "georgia, palatino"}}><strong> </strong></span></p>
    <p>What is IMAP?</p>
    <p><span style={{fontWeight: 400}}>IMAP is an Internet Message Access Protocol. which is used by e-mail clients to get the messages from the mail server over a TCP/IP connection In other words IMAP is basically an internet mail protocol which is used for accessing email on a remote web server from a local client. It is commonly used for retrieving emails it is supported by all modern email clients and web servers.IMAP also allows simultaneous access for multiple clients hence IMAP configuration is suitable when you are planning to use email from different locations/devices or if it email is managed by multiple users</span></p>
    <p><span style={{fontWeight: 400}}>T</span><span style={{fontWeight: 400}}>he IMAP -internet mail protocol works on two ports by default :</span></p>
    
        Port 143<span style={{fontWeight: 400}}> - it is default IMAP non-encrypted port</span>
        Port 993<span style={{fontWeight: 400}}> - it is default IMAP encrypted port - used when you need to connect using IMAP securely </span>
     <br />
    <p>If you need any assistance, feel free to contact our technical team members as they are available 24/7 via phone call, chat, ticket system.</p>
    <p dir="ltr"><span style={{fontSize: "x-large", fontFamily: "georgia, palatino"}}><strong> </strong></span></p>
</div>

      <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span>  
      <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span>