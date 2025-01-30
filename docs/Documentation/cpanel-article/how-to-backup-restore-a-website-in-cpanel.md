---
title: How to Backup & Restore a Website in cPanel?
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
<div class="page-header">
</div>
<dl class="article-info muted">
    <dt class="article-info-term">
</dt>
</dl>
<div itemprop="articleBody">
    <h1><strong><span style="font-size: xx-large;">How to Backup &amp; Restore a Website in cPanel?</span></strong></h1>
    <p> </p>
    <p><span style="font-weight: 400;">C-Panel is one of the easiest tools to manage a website and<a href="/cpanel-article/how-to-use-the-backup-wizard-in-cpanel"><b> cPanel backup</b></a> system offers several choices for backing up and restoring your website. A Full Backup is a full backup that contains your home directory, Your MySQL databases as well as your email forwarders and filters. You can use Full backup option if you are planning to move to another cPanel Linux VPS server.</span></p>
    <p><b>Taking the backup of the website:</b></p>
    <p><span style="font-weight: 400;">While taking the backup of the website you can neither take the full backup or partial backup.</span></p>
    <p><span style="font-weight: 400;">By opting to take a full backup, you can take the full backup of your account where the files related to the website and configuration. It is generally used when the website needs to be moved to another server. You also keep the backup in your local system as a copy.  </span></p>
    <p><span style="font-weight: 400;">By opting to take a Partial Backup, you have the opportunity to back up the Home directory and restore any of the following: The Home Directory containing the public_html folder that includes your website’s file, the  Databases, Email Forwarders, Email filters.</span></p>
    <p><b>Follow the below steps to take backup of your website: </b></p>
    <p dir="ltr"><b>Step 1:</b><span style="font-weight: 400;">  Log into your cPanel of your hosting account, you can do that by pointing your browser to http://your_ip_address:2083 and utilizing the credentials given for your Linux VPS server.<br/></span></p>
    <p dir="ltr"><span style="font-size: large;"><br/><br/></span></p>
    <p><b>Step 2:</b><span style="font-weight: 400;"> After you login into your c-panel in the main screen of cPanel &gt;&gt; Under files section &gt;&gt; click on backup</span></p>
    <p dir="ltr"><span style="font-size: large;"> </span></p>
    <p dir="ltr"><span style="font-size: large;"><br/><br/></span></p>
    <p><b>Step 3:</b><span style="font-weight: 400;"> After clicking on backup &gt;&gt; as per requirement you can choose full backup or partial backup. For full backup click on &gt;&gt; Download a full website backup. </span></p>
    <p><span style="font-weight: 400;">For partial backup go to Partial Backups section &gt;&gt; click on the Home Directory option. After you click on  Home Directory button &gt;&gt; a pop up will appear to download backup on your local system. You need to choose the location where you wish to download your backup and press OK button. </span></p>
    <p dir="ltr"><span style="font-size: large;"> </span></p>
    <p dir="ltr"><span style="font-size: large;"><br/><br/></span></p>
    <p><span style="font-weight: 400;">The backup of your Home Directory will be compressed and downloaded to the local system of your Linux VPS server. Following the above steps, you can take the backup of your website.</span></p>
    <p><span style="font-weight: 400;">It is always recommended that to take the backup before you make any changes in the configuration or website. And it is not recommended to store the backup in the file manager. The backup will be created in the form of a zip file (compressed file) which can be downloaded into your local computer for storage. It is always best to maintain your own backup (complete backup of your website)on your local system if even if the backups are taken at the server end as it would ensure that the website files and emails are safe.</span></p>
    <p><b>Restore Website using cpanel</b></p>
    <p><span style="font-weight: 400;">For restoring the website there are two options available to restore.</span></p>
    <p><span style="font-weight: 400;">&gt;&gt; Restore a Home Directory Backup</span></p>
    <p><span style="font-weight: 400;">&gt;&gt; Restore a MySQL Database Backup</span></p>
    <p><b>Follow the below steps to restore your website:<br/><br/>Step 1:<span style="font-weight: 400;"> Log into your cPanel of your hosting account, you can do that by pointing your browser to http://your_ip_address:2083 and utilizing the credentials given for your <a href="https://www.hostingraja.in/server/vps-servers/linux-vps-hosting/"><b> Linux VPS server</b></a>.
        <br/>
        <br/>
        </span>
        </b>
    </p>
    <p> <img title="Linux cPanel Backup image one" src="https://image.hostingraja.in/images/articles/linux-cpanel-server-backup-img1.png" alt="C-panel  login " width="326" height="339" /></p>
    <p><b>Step 2:</b><span style="font-weight: 400;"> After you login into your c-panel in the main screen of cPanel &gt;&gt; Under files section &gt;&gt; click on backup</span></p>
    <p><b><span style="font-weight: 400;"><img title="Linux cPanel Backup image two" src="https://image.hostingraja.in/images/articles/linux-cpanel-server-backup-img2.png" width="208" height="224" /></span></b></p>
    <p><b>Step 2.1:</b><span style="font-weight: 400;"> Follow the below steps to restore a Home Directory Backup</span></p>
    <p><b>Step 1: </b><span style="font-weight: 400;">To restore your website’s files &gt;&gt;go to the Restore a Home Directory Backup option &gt;&gt; and click on Choose File and the files which has to be uploaded</span></p>
    <p><b>Step 2: </b><span style="font-weight: 400;">You need to upload the file from your local system to your server.</span></p>
    <p><img src="https://image.hostingraja.in/images/articles/linux-cpanel-server-backup-img3.png" alt="Home directory backup " width="260" height="328" /></p>
    <p><b>Step 2.2:</b><span style="font-weight: 400;">  Follow the below steps to restore a MySQL Database Backup</span></p>
    <p><b>Step 1:</b><span style="font-weight: 400;"> To restore only the MySQL database &gt;&gt; go to the Restore a MySQL Database option &gt;&gt; and click on Choose Files &gt;&gt; next choose the file from your local system and upload it to your Linux VPS server.</span></p>
    <p><b>Step 2: </b><span style="font-weight: 400;">After the MySQL database is restored in your server you will get the below message “Congrats! Ideally restoring your database to a previous working form that you have backed up, has effectively brought back your missing information or enabled your site to work again properly.”</span></p>
    <p><span style="font-weight: 400;">If you are facing any issue while restoring the website or while taking up the backup, feel free to contact our support team via live chat, email, toll-free or ticket system and our support team is available 24/7.</span></p>
    <p><b> </b></p>
</div>
<ul class="pager pagenav">
    <li class="previous">
        <a class="hasTooltip" title="Changing File Permissions in cPanel" aria-label="Previous article: Changing File Permissions in cPanel" href="/docs/changing-file-permissions-in-cpanel" rel="prev">
            <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
    </li>
    <li class="next">
        <a class="hasTooltip" title="How can I reset my cPanel password for my domain?" aria-label="Next article: How can I reset my cPanel password for my domain?" href="/docs/how-can-i-reset-my-cpanel-password-for-my-domain" rel="next">
            <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
    </li>
</ul>
</div>