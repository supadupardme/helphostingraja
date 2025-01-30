---
title: How to access the SSH in shared Linux?
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
    <h1><span style="font-size: xx-large;"><strong>How to access the SSH in <a href="https://www.hostingraja.in/" target="_blank" rel="noopener noreferrer">shared Linux</a>?</strong></span></h1> <br /><br /><span style="font-size: x-large;"><strong>What Is SSH?</strong></span><br /><br />
    <p><span style="font-size: 14pt;"><b>Secure Shell which is commonly known as SSH,</b><span style="font-weight: 400;"> it is a </span><b>protocol</b><span style="font-weight: 400;"> that is used to login </span> <span style="font-weight: 400;">to the server in a secure way and it is most commonly used by Linux based servers</span></span></p> <br />
    <p><span style="font-weight: 400; font-size: 14pt;">SSH can be used in Linux and Windows OS based hosting using the software tools. For Linux, you can use your terminal to connect to the server while for windows you can use PUTTY or KITTY software to connect to the server.</span></p> <br />
    <p><span style="font-weight: 400; font-size: 14pt;">The SSH is an essential tool to be master as a system administrator.</span></p> <br />
    <p><span style="font-size: 14pt;"><strong>Note:</strong></span></p>
    <p><span style="font-weight: 400; font-size: 14pt;">In shared hosting, you will be having a restriction for all your access. Hosting providers will set a limit and restriction as per their plans or their terms. And also in few lower shared hosting plans you will not get SSH access. </span></p> <br />
    <p><span style="font-size: 14pt;"><b>What are the advantages of using SSH for managing the website</b></span></p>
    <ol>
        <li><span style="font-weight: 400; font-size: 14pt;"> SSH is a more secure network connection when compared to FTP.</span></li>
        <li><span style="font-weight: 400; font-size: 14pt;"> Cache Clearing in the server can be done easily through ssh in seconds when compared to FTP Login Or Panel Login.</span></li>
        <li><span style="font-weight: 400; font-size: 14pt;"> Very quick in Live Editing and saving the files, though no need of downloading to the Local system.</span></li>
        <li><span style="font-weight: 400; font-size: 14pt;"> Installing and Managing applications via command line.</span></li>
    </ol> <br />
    <p><span style="font-size: 14pt;"><b>Why do need SSH to maintain a server</b></span></p>
    <ol>
        <li><span style="font-weight: 400; font-size: 14pt;"> Services LIKE mysql, Apache, Java etc. can be started Or stopped easily from the server end using SSH.</span></li>
        <li><span style="font-weight: 400; font-size: 14pt;"> The firewall can be controlled over ssh. For example, need to Block or unblock the IPS, we can use SSH.</span></li>
        <li><span style="font-weight: 400; font-size: 14pt;"> Solving the issues by Checking the Logs in the server end.</span></li>
        <li><span style="font-weight: 400; font-size: 14pt;"> Which service take more load in the server can be able to Monitor Over SSH.</span></li>
        <li><span style="font-weight: 400; font-size: 14pt;"> Removing the files from the server is very quick over ssh compared to FTP and other protocols.</span></li>
    </ol> <br /><br />
    <p><span style="font-size: 14pt;"><b>How to access the SSH in shared hosting?</b></span></p> <br />
    <p><span style="font-weight: 400; font-size: 14pt;">For SSH access in<a href="https://www.hostingraja.in/hosting/linux-shared-server/"><b> shared Linux hosting,</b></a> you have to make sure that your hosting the provider has to enable the SSH Access for your account. If it's already been enabled, you can use the below steps to connect the SSH using the Putty.</span></p> <br />
    <p><span style="font-weight: 400; font-size: 14pt;">In Windows, to access SSH you need will need putty software to be installed in your local.</span></p> <br />
    <p><span style="font-weight: 400; font-size: 14pt;">Now you need to generate a PPK key through your Cpanel.</span></p> <br />
    <p><span style="font-weight: 400; font-size: 14pt;"><strong>Step 1 ~</strong> Login to cpanel &gt;&gt; click on the SSH.</span></p> <br /><br /><span id="docs-internal-guid-7ab3910f-2505-fcd7-6c49-a26f235173b2" style="font-size: 13.999999999999998pt; font-family: Arial; color: #93c47d; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"><img style="transform: rotate(0rad);" src="https://image.hostingraja.in/images/article/cloud/59.jpg" alt="SSH access in cPanel" width="276" height="532" border="0" /></span><br /><br /><br /><br />
    <p><span style="font-weight: 400; font-size: 14pt;"><strong>Step 2:</strong> After you Click on SSH Access &gt;&gt; Under the Manage SSH Keys click on Generate a new Key </span></p> <br />
    <p><span style="font-weight: 400; font-size: 14pt;">Step 3: After click on generate a new key &gt;&gt; you need to enter the password &gt;&gt; click on generate a key. Save the password (make sure you remember the password)</span></p> <br /><span id="docs-internal-guid-7ab3910f-2506-15c2-9801-0ec24c53ec7c" style="font-size: 13.999999999999998pt; font-family: Arial; color: #93c47d; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"><img style="transform: rotate(0rad);" src="https://image.hostingraja.in/images/article/cloud/61.jpg" alt="SSH access in cPanel" width="351" height="460" border="0" /></span><br /><br /><br /><span style="font-size: large;">Step 3 ~ Now you need to enter password and generate a key and save the password in any notepad.</span><br /><br /><span id="docs-internal-guid-7ab3910f-2506-3b4b-de28-c5910377bab1" style="font-size: 13.999999999999998pt; font-family: Arial; color: #93c47d; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"><img style="transform: rotate(0rad);" src="https://image.hostingraja.in/images/article/cloud/62.jpg" alt="SSH access in cPanel" width="178" height="227" border="0" /></span><br /><br /><span style="font-size: large;">Step 4 ~ once key generated click on GO Back and you can see the Key generated, click on manage as mentioned in below screen.</span><br /><br /><span id="docs-internal-guid-7ab3910f-2506-4fc1-5cc6-1a34bcf2717c" style="font-size: 13.999999999999998pt; font-family: Arial; color: #93c47d; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"></span><br /><br /><br />
    <p><span style="font-weight: 400; font-size: 14pt;">Step 6: Click on Authorise -You need to Authorise the key which you have generated.</span></p> <br /><span id="docs-internal-guid-7ab3910f-2506-604c-2470-caa40749fbd6" style="font-size: 13.999999999999998pt; font-family: Arial; color: #93c47d; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"><img style="transform: rotate(0rad);" src="https://image.hostingraja.in/images/article/cloud/63.jpg" alt="SSH access in cPanel" width="352" height="244" border="0" /></span><br /><br /><br /><br /><br /><span style="font-size: large;">Step 7 ~ Now you need to download the Private key.</span><br /><br /><span id="docs-internal-guid-7ab3910f-2506-724a-ffaf-a4d327416d4f" style="font-size: 13.999999999999998pt; font-family: Arial; color: #93c47d; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"><img style="transform: rotate(0rad);" src="https://image.hostingraja.in/images/article/cloud/64.jpg" alt="SSH access in cPanel" width="326" height="165" border="0" /></span><br /><br /><span style="font-size: large;">Step 8 ~ Enter the password which you have created at the time of generating the key and click on convert.</span><br /><br /><br /><span id="docs-internal-guid-7ab3910f-2506-8057-368f-a83e5d25c41e" style="font-size: 13.999999999999998pt; font-family: Arial; color: #93c47d; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"><img style="transform: rotate(0rad);" src="https://image.hostingraja.in/images/article/cloud/65.jpg" alt="SSH access in cPanel" width="467" height="284" border="0" /></span><br /><br /><span style="font-size: large;">Step 9 ~ Now you can download the file in local and save it.</span><br /><br /><span id="docs-internal-guid-7ab3910f-2506-9438-cee9-9f7015b68cc2" style="font-size: 13.999999999999998pt; font-family: Arial; color: #93c47d; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"><img style="transform: rotate(0rad);" src="https://image.hostingraja.in/images/article/cloud/66.jpg" alt="SSH access in cPanel" width="253" height="348" border="0" /></span><br /><br />
    <p><span style="font-weight: 400; font-size: 14pt;"><strong>Step 10:</strong> Open Putty enter the Server IP and add the RSA key in the putty as mentioned in the screen.(category &gt;&gt; SSH &gt;&gt; auth)</span></p> <br /><span id="docs-internal-guid-7ab3910f-2506-a8ca-58ee-500370d78024" style="font-size: 13.999999999999998pt; font-family: Arial; color: #93c47d; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"><img style="transform: rotate(0rad);" src="https://image.hostingraja.in/images/article/cloud/67.jpg" alt="SSH access in cPanel" width="465" height="444" border="0" /></span><br /><br /><br /><br />
    <p><span style="font-weight: 400;"><span style="font-size: 14pt;"><strong>Step 11:</strong> After You upload the file which you have downloaded &gt;&gt; click on open now enter the Your server IP and port 22 and select the SSH and click on open to connect to SSH</span> </span></p> <br /><br /><span id="docs-internal-guid-7ab3910f-2506-cc5a-78b3-e8fd1d10f136" style="font-size: 13.999999999999998pt; font-family: Arial; color: #93c47d; background-color: transparent; font-weight: 400; font-style: normal; font-variant: normal; text-decoration: none; vertical-align: baseline; white-space: pre-wrap;"><img style="transform: rotate(0rad);" src="https://image.hostingraja.in/images/article/cloud/68.jpg" alt="SSH access in cPanel" width="465" height="446" border="0" /></span><br /><br />
    <div id="login-issues-in-ssh">
        <p><span style="font-weight: 400; font-size: 14pt;">Following the above steps you can connect to SSH.</span></p>
        <p><span style="font-size: 14pt;"><strong><br /></strong><b>Login Issues in SSH </b></span></p>
        <p><span style="font-size: 14pt;"><strong> </strong></span></p>
        <p><span style="font-size: 14pt;"><span style="font-weight: 400;">When a </span><a href="https://www.hostingraja.in/domains/"><span style="font-weight: 400;">domain name</span></a><span style="font-weight: 400;"> is moved from one server to another then an issue with the </span><b>SSH logins might creep up</b><span style="font-weight: 400;">. Most of the warning dialog which most of the SSH programs gives looks something like as shown below:<br /><br /></span></span></p>
        <p><strong><span style="font-size: x-large;">WARNING: REMOTE HOST IDENTIFICATION HAS CHANGED</span></strong></p>
        <p><br />IT IS POSSIBLE THAT SOMEONE IS DOING SOMETHING NASTY!<br />Someone could be eavesdropping on you right now (man-in-the-middle attack)!<br /><br />It is also possible that the RSA host key has just been changed.<br /><br />The fingerprint for the RSA key sent by the remote host is<br /><strong>06:ea:f1:f8:db:75:5c:0c:af:15:d7:99:2d:ef:08:2a.</strong><br /><br />Please contact your system administrator.<br /><br />Add correct host key in /<strong>home/user/.ssh/known_hosts</strong> to get rid of this message.<br /><br />Offending key in <strong>/home/user/.ssh/known_hosts:4</strong><br /><br />RSA host key for domain.com has changed and you have requested strict checking.<br /><br />Host key verification failed.<br /><br /><br /><br /><strong><img style="display: block; margin-left: auto; margin-right: auto;" src="https://image.hostingraja.in/images/article/cloud/login-issesu-in-ssh.png" alt="Login Issues in SSH" width="470" height="351" border="0" /></strong><br /><br /><br /></p>
        <p dir="ltr">Here the <strong>SSH program will be printing this message</strong> and more often the text, it prohibits the user from connecting to the suspicious website. This problem rises when the website has changed the servers and the new servers RSA key which is being transmitted when the authentication is different from that of the old server.</p>
        <p> </p>
        <p dir="ltr">In the case of a migration you will be reasonably sure that the RSA key change is not an accident but to connect to the new server one must remove the line in <strong>.ssh/known_hosts</strong> that will correspond to the domain name. This could be done by editing the ‘known_hosts’ by hand or if the machine is having the Perl installed then you can use this one-liner:</p>
        <p> </p>
        <p dir="ltr"><strong>perl -p -i -e 's/^example.com.*n//;' ~/.ssh/known_hosts</strong></p>
        <p> </p>
        <p dir="ltr">Now you need to substitute the actual domain for example.com by always making sure of including the <strong>backslash</strong> before the dot. If you are having many domains that have moved you must be repeated this step for each one.<br /><br /></p>
    </div>
    <div id="how-to-use-ssh-in-linux">
        <div class="hostingraja-forum-article">
            <h2><strong>How to use SSH in Linux?</strong><br /><br /></h2>
            <div class="hostingraja-forum-article-inner-div">
                <div class="hostingraja-forum-article-contents">
                    <div class="hostingraja-forum-article-content">All modern Unix-like systems (Linux, OS X, BSDs, and others) include a command-line ssh client. To login to your computer from a Unix-like machine, go to a command-line and type:</div>
                    <div class="hostingraja-forum-article-content"><span style="font-weight: bold;">ssh &lt;username&gt;@&lt;computer name or IP address&gt;</span></div>
                    <div class="hostingraja-forum-article-content">Example:<br /> <span style="font-weight: bold;">ssh <span id="cloak5ce133b90108339aa0b92dd7341f13a0">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                            <script type="f778017411d68f79aafda8f7-text/javascript">
                                document.getElementById('cloak5ce133b90108339aa0b92dd7341f13a0').innerHTML = '';
                                var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                                var path = 'hr' + 'ef' + '=';
                                var addy5ce133b90108339aa0b92dd7341f13a0 = 'r&#111;&#111;t' + '&#64;';
                                addy5ce133b90108339aa0b92dd7341f13a0 = addy5ce133b90108339aa0b92dd7341f13a0 + '&#101;x&#97;mpl&#101;' + '&#46;' + 'c&#111;m';
                                var addy_text5ce133b90108339aa0b92dd7341f13a0 = 'r&#111;&#111;t' + '&#64;' + '&#101;x&#97;mpl&#101;' + '&#46;' + 'c&#111;m';document.getElementById('cloak5ce133b90108339aa0b92dd7341f13a0').innerHTML += '<a ' + path + '\'' + prefix + ':' + addy5ce133b90108339aa0b92dd7341f13a0 + '\'>'+addy_text5ce133b90108339aa0b92dd7341f13a0+'</a>';
                            </script> (or) ssh <span id="cloakb772950870aeb09831cd806f5776eb48">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                            <script type="f778017411d68f79aafda8f7-text/javascript">
                                document.getElementById('cloakb772950870aeb09831cd806f5776eb48').innerHTML = '';
                                var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                                var path = 'hr' + 'ef' + '=';
                                var addyb772950870aeb09831cd806f5776eb48 = 'r&#111;&#111;t' + '&#64;';
                                addyb772950870aeb09831cd806f5776eb48 = addyb772950870aeb09831cd806f5776eb48 + 'xxx' + '&#46;' + 'xxx' + '&#46;' + 'xx' + '&#46;' + 'xx';
                                var addy_textb772950870aeb09831cd806f5776eb48 = 'r&#111;&#111;t' + '&#64;' + 'xxx' + '&#46;' + 'xxx' + '&#46;' + 'xx' + '&#46;' + 'xx';document.getElementById('cloakb772950870aeb09831cd806f5776eb48').innerHTML += '<a ' + path + '\'' + prefix + ':' + addyb772950870aeb09831cd806f5776eb48 + '\'>'+addy_textb772950870aeb09831cd806f5776eb48+'</a>';
                            </script>
                        </span></div>
                    <div class="hostingraja-forum-article-content"><span style="font-weight: 400;">You should get the usual password prompt (or be told you can't log in if passwords are disabled).See ssh keys if you want to authenticate using keys instead of passwords.</span><br /><br /><img src="https://image.hostingraja.in/images/article/cloud/access-the-SSH.png" alt="cPanel SSH access" width="440" height="135" /><br /><br /><b>If you are facing any issues or </b><b>If you need any assistance, feel free to contact our technical team members as they are available 24/7 via phone call, chat, <a href="https://support.hostingraja.in/">ticket system</a>.</b></div>
                </div>
            </div>
        </div>
    </div>
</div>
<ul class="pager pagenav">
    <li class="previous"> <a class="hasTooltip" title="How to improve the Website Speed by 70% in One Hour" aria-label="Previous article: How to improve the Website Speed by 70% in One Hour" href="/how-tos/how-to-improve-the-website-speed-by-70-in-one-hour" rel="prev"> <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a> </li>
    <li class="next"> <a class="hasTooltip" title="How To Manage a MySQL Database with phpMyAdmin?" aria-label="Next article: How To Manage a MySQL Database with phpMyAdmin?" href="/how-tos/how-to-manage-a-mysql-database-with-phpmyadmin" rel="next"> <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a> </li>
</ul>
