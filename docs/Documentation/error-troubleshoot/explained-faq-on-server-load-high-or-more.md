---
title: Explained - FAQ on server load high or more.
excerpt: >-
  Learn to monitor server load via SSH to troubleshoot slow website performance
  effectively
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

Explained - FAQ on server load high or more. 
</div>

<span class="icon-calendar" aria-hidden="true"></span>

Last Updated: 02 January 2024 

<div itemprop="articleBody">
<strong><span id="docs-internal-guid-ce1e15b3-7fff-b469-4cf5-bf9a1ac10590">SERVER LOAD IS HIGH </span></strong>
<div>
<p dir="ltr"><strong>HOW TO FIND OUT THE SERVER LOAD IS HIGH IN YOUR VPS SERVER OR DEDICATED SERVER?</strong></p>
<strong><strong><br /></strong></strong>

<p dir="ltr">Website is loading slow</p>

<p dir="ltr">login to SSH of your linux server, press ‘w’ to know the current average load and top -cd2 to know which process is taking the load.</p>

<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>WHAT IS SERVER LOAD?</strong></p>
<strong><strong><br /></strong></strong>
<p dir="ltr">Load that expresses how many number of jobs or active processes are waiting in the queue to access the computer processor. This is calculated for a certain period of time over the last 1, 5, and 15 minutes.</p>
<p dir="ltr">This server load  is indication on how much work has been done on your serve.</p>
<p dir="ltr">We consider a load value under 5 to be acceptable.However if the server average load reach  5.00 or greater for a consistent period of time, then it's worth finding out the exact cause of the higher server load to resolve the issue or prevent from server down.</p>
<p dir="ltr">                   </p>
<p dir="ltr"><strong>HOW SERVER LOAD IS LINKED TO THE PERFORMANCE OF YOUR VPS </strong></p>
<p dir="ltr">            </p>

<p dir="ltr">Not reducing large image file sizes</p>

<p dir="ltr">Not using Gzip compression</p>

<p dir="ltr">Not using Browser Caching</p>

<p dir="ltr">Using larger numbers of plugins.</p>

<p dir="ltr">Users/spammers sending spam email.</p>

<p dir="ltr">Users sending large mailing lists.</p>

<p dir="ltr">Server backup file are consuming server space.</p>

<p dir="ltr">Running out of memory and swapping to the swap file.</p>

<p dir="ltr">Error take place due to software misconfiguration.</p>

<p dir="ltr">To many high resource website running in single server - This cumulative resources resulting in high server load.</p>

<p dir="ltr"> </p>
<p dir="ltr"><strong>HOW TO SOLVE THE PROBLEM</strong></p>
<strong><strong><br /></strong></strong>

<p dir="ltr">Optimize images</p>

<p dir="ltr">Enable Gzip compression</p>

<p dir="ltr">Minimize the number of plugins</p>

<p dir="ltr">Enable browser caching</p>

<p dir="ltr">Choose a reliable web hosting plan</p>

<p dir="ltr">Remove the unwanted files and plugins.</p>

<p dir="ltr">Download the backup files to local system</p>

<p dir="ltr">Provide highly secure passwords for mail account to avoid the spammers attack.</p>

<p dir="ltr">Use the load balance server for high resource website..</p>

<p dir="ltr">Check the database tables are closed properly or not.</p>

<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>SYMPTOMS FOR THE LOAD RELATED ISSUE</strong></p>
<strong><strong><br /></strong></strong>
<p dir="ltr">Files, databases will not be able to upload  or download from the server .</p>
<strong><strong><br /></strong></strong>
<p dir="ltr">Site will not load or very slow website loading.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr">Continuously server down will take place due to out of memory .When you restart the server it will work temporary after sometime again server will go down.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>STEPS TO CHECK THE SERVER LOAD ISSUE IN SSH:</strong></p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>STEP 1:</strong> To check the server load.</p>

<p dir="ltr">Command: w</p>

<p dir="ltr">Average load for the server is : 5</p>

<p dir="ltr">If Average load is with in 6 check with mentioned below gtmetrix site speed checking tool.</p>

<p dir="ltr">        https://gtmetrix.com/</p>
<p dir="ltr">             </p>

<p dir="ltr">KEEP-ALIVE should be enable for apache server.</p>

<p dir="ltr">To enable KEEP-ALIVE =&gt; login to WHM =&gt; Search Apache Setting module =&gt; Enable    KEEP-ALIVE After 5 minute check with gtmetrix KEEP-ALIVE is enabled or not.</p>

<p dir="ltr">Inform the client check browser caching And Optimize images ,Minify JavaScript,CSS,HTML.</p>

<strong><strong><br /></strong></strong>
<p dir="ltr">        But this is very basic case you should check the mentioned below cases also.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>OUT OF MEMORY:</strong></p>
<br />
<p dir="ltr"><strong>STEP 2:</strong> To check the disk space</p>
<p dir="ltr">             </p>
<p dir="ltr">Command :free -h</p>
<strong><strong><br /></strong></strong>
<p dir="ltr">This is command to check what space is allocated and how much client have used, and free space.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>STEP 3: </strong>Refer the message log file.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr">Command: vim /var/log/messages</p>
<p dir="ltr">  </p>
<p dir="ltr">Search ? Out of memory</p>
<p dir="ltr">                </p>
<p dir="ltr">               Check the date and time , if issue is related to out of memory inform the client to upgrade the plan.(If client is maintaining any backup files in server inform the client to download the backup to local system and delete from server)</p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>MYSQL QUERY :</strong></p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>STEP 2: </strong><strong> </strong>Check which process taking high load.</p>
<p dir="ltr">             </p>
<p dir="ltr">Command : top -cd2</p>
<p dir="ltr">            </p>
<p dir="ltr">          Analyse for few minutes which process is taking high load, Most of the time mysql will take high load.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>STEP 3: </strong>To check which mysql database taking more load.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr">Command : mysqladmin proc</p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>STEP 4:</strong></p>
<p dir="ltr">           </p>
<p dir="ltr"><strong>Case 1: </strong>If sentora_postfix database taking high , Check the mailq in SHH</p>
<p dir="ltr">             Command : mailq</p>
<p dir="ltr">If continuously mails sending in mailq it may be due to client sending lot of emails or spam mails or someone might have hacked the client mails.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>Case 2:</strong> If  client database is taking high load.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr">It will happen due improper table close in client database(Inform the client to check table connection is closed or not) or due to lot hits in databases.</p>
<p dir="ltr">         </p>
<p dir="ltr">Example: e commerce site will take lot of mysql lot , Because it will have lot of plugins and products. (Inform the client to move load balance server.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr">Check 3306 port enable in csf or not , If client not using external database connection remove this port from csf</p>
<strong><strong><br /></strong></strong>
<p dir="ltr">Command: lsof -i:3306 =&gt; to check port is enabled in server or not.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>SERVER SLOW DUE TO HITS:</strong></p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>STEP 2:</strong> Use the mentioned below command to know server hits.</p>
<strong><strong><br /></strong></strong>
<p dir="ltr">Command: tail -f /etc/httpd/logs/access_log</p>
<strong><strong><br /></strong></strong>
<p dir="ltr">Command: tail -f /etc/httpd/logs/ssl_access_log</p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>STEP 3: </strong>To check the mentioned below file to know Which countries are trying to access the server.</p>
<p dir="ltr">                   vim /etc/csf/csf.deny</p>
<strong><strong><br /></strong></strong>
<p dir="ltr"><strong>STEP 4:</strong> If you found a lot of hits from other countries apart from his own country, Inform about the hits to clients and ask him what are the countries he has given the access  for his website.</p>
<p dir="ltr">                      Example: If client doesn't  wants to access his site from China and United States , just give the country code in <strong>CC_DENY in csf.</strong></p>
<strong><strong><br /></strong></strong>
<p dir="ltr">Refer this link to Deny counrty code in CSF:  https://www.liquidweb.com/kb/how-to-block-traffic-by-country-in-the-csf-firewall/</p>
<p dir="ltr">To know the country code : https://serverhealers.com/blog/csf-country-code-full-list/</p>
<p dir="ltr">                    </p>
<p dir="ltr">      </p>
<strong><span id="docs-internal-guid-f1761e0a-7fff-8259-ff8b-7a151b7c9fda">               BEFORE EDITING ANYTHING YOU SHOULD INFORM THE SENIOR</span><br /></strong></div> </div>

<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 

<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 

</div>