---
title: How to check Mail Log in a Dedicated Box using WHM?
excerpt: >-
  Effortlessly review mail logs on your Dedicated Box via WHM with HostingRaja.
  Monitor email activity seamlessly for better insights.
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
    <h1 dir="ltr"><span style="font-size: xx-large;"><strong>How to check Mail Log in a Dedicated Box using WHM (HR-Panel)?</strong></span></h1>
    <p> </p>
    <p dir="ltr"><span style="font-size: large;">A server is one of the most effective ways of getting the website hosted successfully. <a href="https://www.hostingraja.in/server/dedicated-servers">Dedicated server</a> hardware is rented to you by the service provider. And the dedicated come with their own processors, RAM, bandwidth, hard drive and much more. With these servers, your website and its software will be included on the hard drives provided. The servers are flexible and permit you to run and install any program required by you. And can also share the features with anyone for which you give access to the system so can use the program at the same time.</span></p>
    <div><span style="font-size: x-large;"><strong><br />Below is the video on checking the Mail Log in WHM: </strong></span></div>
    <div> </div>
    <p dir="ltr"><span style="font-size: x-large;"><strong>Steps to check Mail Log in <a href="https://www.hostingraja.in/">Web Hosting</a> Manager:</strong></span></p>
    <p> </p>
    <p dir="ltr"><span style="font-size: large;"><strong>Step-1:</strong> Log in to the WHM panel.</span></p>
    <p dir="ltr"><span style="font-size: large;"><strong>Step-2:</strong> Click on Mail Log.</span></p>
    <p dir="ltr"><span style="font-size: large;"><strong>Step-3:</strong> It will display the complete Mail Log information.</span></p>
    <p dir="ltr"><span style="font-size: large;"><strong>Step-4:</strong> You will be offered with the information such as per day traffic summary, message rejects details and much more. </span><br /><br /></p>
    <p dir="ltr"><span style="font-size: large;">Get more info about checking the Mail Log in WHM - Dedicated or VPS or <a href="https://www.hostingraja.in/cloud/">Cloud Hosting</a>, by contacting<a href="https://www.hostingraja.in/hosting/compare-hosting-plans/"><b> Hosting Raja </b></a> support team members through the phone call, email, ticket system, live chat, <a href="https://support.hostingraja.in/">ticket system</a>. <a href="/other-help/high-traffic-website">HostingRaja support </a> team members are available 24/7 to solve all your issues.</span></p>
    <div> </div>
    <div id="how-to-check-the-mail-log">
        <h2 dir="ltr"><span style="font-size: xx-large;"><strong>How to check the mail log?</strong></span></h2> <br />
        <p dir="ltr">As you know that using dedicated gives you a lot of advantages with more resources and helps you to handle your website easily. Not only that today if you are having a website and if you have hosted it on the shared hosting environment and now if you are facing some issues related to resources or you face load time or server down then choosing dedicated is one of the best methods where it gives you more features and advantages in your hosting. Using dedicated will also get more flexibility and security in your hosting.</p> <br />
        <p dir="ltr">And today most of the people are using the email services on their dedicated. Because at present email plays an important mode of communication between business and its customers. Not only that with the help of email you can also easily create the brand awareness of your business products and services. So today if you are using dedicated hosting server for your website and if you are looking for information on how to check the mail log on your server then here is the solution.</p> <br />
        <p dir="ltr"><strong><span style="font-size: x-large;">Here is the solution to check the mail log on your server:</span> </strong></p> <strong><br /></strong>
        <p dir="ltr"><span style="font-size: x-large;"><strong>Plesk Users</strong></span></p> <br />
        <p dir="ltr">&gt;&gt;&gt; Log into your Plesk SSH or Root access</p> <br />
        <p dir="ltr">&gt;&gt;&gt; Follow this path to locate your email logs</p> <br />
        <p dir="ltr"><strong>/usr/local/psa/var/log/</strong></p> <br />
        <p dir="ltr">&gt;&gt;&gt; To view the email log use the following command</p> <br />
        <p dir="ltr"><strong>tail -f /usr/local/psa/var/log/maillog</strong></p> <br />
        <p dir="ltr">&gt;&gt;&gt; To search for a particular string:</p> <br />
        <p dir="ltr"><strong><span id="cloak239bc6f1423b6e2dcd09612b479bbe05">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                <script type="bb66d1a163691c0b3ef2edb7-text/javascript">
                    document.getElementById('cloak239bc6f1423b6e2dcd09612b479bbe05').innerHTML = '';
                    var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                    var path = 'hr' + 'ef' + '=';
                    var addy239bc6f1423b6e2dcd09612b479bbe05 = '&#101;x&#97;mpl&#101;' + '&#64;';
                    addy239bc6f1423b6e2dcd09612b479bbe05 = addy239bc6f1423b6e2dcd09612b479bbe05 + 'd&#101;m&#111;' + '&#46;' + 'c&#111;m';
                    var addy_text239bc6f1423b6e2dcd09612b479bbe05 = '&#101;x&#97;mpl&#101;' + '&#64;' + 'd&#101;m&#111;' + '&#46;' + 'c&#111;m';document.getElementById('cloak239bc6f1423b6e2dcd09612b479bbe05').innerHTML += '<a ' + path + '\'' + prefix + ':' + addy239bc6f1423b6e2dcd09612b479bbe05 + '\'>'+addy_text239bc6f1423b6e2dcd09612b479bbe05+'</a>';
                </script> /usr/local/psa/var/log/maillog |more
            </strong></p> <br />
        <p dir="ltr">&gt;&gt;&gt; This is how you get the log sequence showing the complete transmission of one piece of mail:</p> <br />
        <p dir="ltr"><strong>April 10 14:10:45 dv qmail: 1223985219.945231 new msg 153248276</strong></p>
        <p dir="ltr"><strong>April 10 14:10:45 dv qmail: 1223985219.945231 info msg 153248276: bytes 860 from &lt;&gt; qp 24106 uid 2522</strong></p>
        <p dir="ltr"><strong>April 10 14:10:45 dv qmail: 1223985219.945231 starting delivery 2: msg 163786382 to local <span id="cloakd9136fd5bebdffcc8047fb60ecb0679e">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                <script type="bb66d1a163691c0b3ef2edb7-text/javascript">
                    document.getElementById('cloakd9136fd5bebdffcc8047fb60ecb0679e').innerHTML = '';
                    var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                    var path = 'hr' + 'ef' + '=';
                    var addyd9136fd5bebdffcc8047fb60ecb0679e = '2-&#117;s&#101;r' + '&#64;';
                    addyd9136fd5bebdffcc8047fb60ecb0679e = addyd9136fd5bebdffcc8047fb60ecb0679e + '&#101;x&#97;mpl&#101;' + '&#46;' + 'c&#111;m';
                    var addy_textd9136fd5bebdffcc8047fb60ecb0679e = '2-&#117;s&#101;r' + '&#64;' + '&#101;x&#97;mpl&#101;' + '&#46;' + 'c&#111;m';document.getElementById('cloakd9136fd5bebdffcc8047fb60ecb0679e').innerHTML += '<a ' + path + '\'' + prefix + ':' + addyd9136fd5bebdffcc8047fb60ecb0679e + '\'>'+addy_textd9136fd5bebdffcc8047fb60ecb0679e+'</a>';
                </script>
            </strong></p>
        <p dir="ltr"><strong>April 10 14:10:45 dv qmail: 1223077819.937835 status: local 1/10 remote 0/20</strong></p>
        <p dir="ltr"><strong>April 10 14:10:45 dv qmail-local-handlers[24107]: Handlers Filter before-local for qmail started ...</strong></p>
        <p dir="ltr"><strong>April 10 14:10:45 dv qmail-local-handlers[24107]: from=</strong></p>
        <p dir="ltr"><strong>April 10 14:10:45 dv qmail-local-handlers[24107]: to=<span id="cloak66b44102bd1cd72a2515516f15253fe6">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                <script type="bb66d1a163691c0b3ef2edb7-text/javascript">
                    document.getElementById('cloak66b44102bd1cd72a2515516f15253fe6').innerHTML = '';
                    var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                    var path = 'hr' + 'ef' + '=';
                    var addy66b44102bd1cd72a2515516f15253fe6 = '&#117;s&#101;r' + '&#64;';
                    addy66b44102bd1cd72a2515516f15253fe6 = addy66b44102bd1cd72a2515516f15253fe6 + '&#101;x&#97;mpl&#101;' + '&#46;' + 'c&#111;m';
                    var addy_text66b44102bd1cd72a2515516f15253fe6 = '&#117;s&#101;r' + '&#64;' + '&#101;x&#97;mpl&#101;' + '&#46;' + 'c&#111;m';document.getElementById('cloak66b44102bd1cd72a2515516f15253fe6').innerHTML += '<a ' + path + '\'' + prefix + ':' + addy66b44102bd1cd72a2515516f15253fe6 + '\'>'+addy_text66b44102bd1cd72a2515516f15253fe6+'</a>';
                </script>
            </strong></p>
        <p dir="ltr"><strong>April 10 14:10:45 dv qmail: 1213077819..159866 delivery 2: success: did_0+0+2/</strong></p>
        <p dir="ltr"><strong>April 10 14:10:45 dv qmail: 1213077819..160087 status: local 0/10 remote 0/20</strong></p>
        <p dir="ltr"><strong>April 10 14:10:45 dv qmail: 1213077819..160159 end msg 163786382 </strong></p> <br />
        <p dir="ltr"><span style="font-size: x-large;"><strong>cPanel Users</strong></span></p> <br />
        <p dir="ltr">&gt;&gt;&gt; Log into your cPanel SSH or Root access</p> <br />
        <p dir="ltr">&gt;&gt;&gt; Follow this path to locate your email logs</p> <br />
        <p dir="ltr"><strong>/var/log/ </strong></p> <br />
        <p dir="ltr">&gt;&gt;&gt; To view the email log use the following command</p> <br />
        <p dir="ltr"><strong>less /var/log/maillog </strong></p> <br />
        <p dir="ltr">&gt;&gt;&gt; To search for a particular string:</p> <br />
        <p dir="ltr"><strong><span id="cloak2f2b25440226b092bbf8dcd5ae8d7cb7">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                <script type="bb66d1a163691c0b3ef2edb7-text/javascript">
                    document.getElementById('cloak2f2b25440226b092bbf8dcd5ae8d7cb7').innerHTML = '';
                    var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                    var path = 'hr' + 'ef' + '=';
                    var addy2f2b25440226b092bbf8dcd5ae8d7cb7 = '&#101;x&#97;mpl&#101;' + '&#64;';
                    addy2f2b25440226b092bbf8dcd5ae8d7cb7 = addy2f2b25440226b092bbf8dcd5ae8d7cb7 + 'd&#101;m&#111;' + '&#46;' + 'c&#111;m';
                    var addy_text2f2b25440226b092bbf8dcd5ae8d7cb7 = '&#101;x&#97;mpl&#101;' + '&#64;' + 'd&#101;m&#111;' + '&#46;' + 'c&#111;m';document.getElementById('cloak2f2b25440226b092bbf8dcd5ae8d7cb7').innerHTML += '<a ' + path + '\'' + prefix + ':' + addy2f2b25440226b092bbf8dcd5ae8d7cb7 + '\'>'+addy_text2f2b25440226b092bbf8dcd5ae8d7cb7+'</a>';
                </script> /var/log/exim_mainlog
            </strong></p> <br />
        <p dir="ltr">&gt;&gt;&gt; This is how you get the log sequence showing the complete transmission of one piece of mail:</p> <br />
        <p dir="ltr"><strong> 2010-11-10 11:40:40 1ZthQy-000586-3x &lt;= <span id="cloak49ef812acaec56573a98c28729ed94e6">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                <script type="bb66d1a163691c0b3ef2edb7-text/javascript">
                    document.getElementById('cloak49ef812acaec56573a98c28729ed94e6').innerHTML = '';
                    var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                    var path = 'hr' + 'ef' + '=';
                    var addy49ef812acaec56573a98c28729ed94e6 = '&#101;x&#97;mpl&#101;' + '&#64;';
                    addy49ef812acaec56573a98c28729ed94e6 = addy49ef812acaec56573a98c28729ed94e6 + 'd&#101;m&#111;' + '&#46;' + 'c&#111;m';
                    var addy_text49ef812acaec56573a98c28729ed94e6 = '&#101;x&#97;mpl&#101;' + '&#64;' + 'd&#101;m&#111;' + '&#46;' + 'c&#111;m';document.getElementById('cloak49ef812acaec56573a98c28729ed94e6').innerHTML += '<a ' + path + '\'' + prefix + ':' + addy49ef812acaec56573a98c28729ed94e6 + '\'>'+addy_text49ef812acaec56573a98c28729ed94e6+'</a>';
                </script> H=localhost (pyxv-qnqd.testdomain.com) [127.0.0.1]:42112 P=esmtpa A=dovecot_login:<span id="cloak9ba956b23eece5f352491c391544fa73">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                <script type="bb66d1a163691c0b3ef2edb7-text/javascript">
                    document.getElementById('cloak9ba956b23eece5f352491c391544fa73').innerHTML = '';
                    var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                    var path = 'hr' + 'ef' + '=';
                    var addy9ba956b23eece5f352491c391544fa73 = '&#101;x&#97;mpl&#101;' + '&#64;';
                    addy9ba956b23eece5f352491c391544fa73 = addy9ba956b23eece5f352491c391544fa73 + 'd&#101;m&#111;' + '&#46;' + 'c&#111;m';
                    var addy_text9ba956b23eece5f352491c391544fa73 = '&#101;x&#97;mpl&#101;' + '&#64;' + 'd&#101;m&#111;' + '&#46;' + 'c&#111;m';document.getElementById('cloak9ba956b23eece5f352491c391544fa73').innerHTML += '<a ' + path + '\'' + prefix + ':' + addy9ba956b23eece5f352491c391544fa73 + '\'>'+addy_text9ba956b23eece5f352491c391544fa73+'</a>';
                </script> S=597 id=<span id="cloakd5a4ba2eb3d82834bfce151131dbfee6">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                <script type="bb66d1a163691c0b3ef2edb7-text/javascript">
                    document.getElementById('cloakd5a4ba2eb3d82834bfce151131dbfee6').innerHTML = '';
                    var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                    var path = 'hr' + 'ef' + '=';
                    var addyd5a4ba2eb3d82834bfce151131dbfee6 = '33b&#97;c78&#97;&#101;03&#101;b&#101;8bb6&#101;c5&#101;545864c&#97;f6' + '&#64;';
                    addyd5a4ba2eb3d82834bfce151131dbfee6 = addyd5a4ba2eb3d82834bfce151131dbfee6 + 'd&#101;m&#111;' + '&#46;' + 'c&#111;m';
                    var addy_textd5a4ba2eb3d82834bfce151131dbfee6 = '33b&#97;c78&#97;&#101;03&#101;b&#101;8bb6&#101;c5&#101;545864c&#97;f6' + '&#64;' + 'd&#101;m&#111;' + '&#46;' + 'c&#111;m';document.getElementById('cloakd5a4ba2eb3d82834bfce151131dbfee6').innerHTML += '<a ' + path + '\'' + prefix + ':' + addyd5a4ba2eb3d82834bfce151131dbfee6 + '\'>'+addy_textd5a4ba2eb3d82834bfce151131dbfee6+'</a>';
                </script> T="Hiya!" for <span id="cloakbde8ed0e4e0f10ae0cfe7afb10fb4a6b">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                <script type="bb66d1a163691c0b3ef2edb7-text/javascript">
                    document.getElementById('cloakbde8ed0e4e0f10ae0cfe7afb10fb4a6b').innerHTML = '';
                    var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                    var path = 'hr' + 'ef' + '=';
                    var addybde8ed0e4e0f10ae0cfe7afb10fb4a6b = 'n&#111;r&#101;ply' + '&#64;';
                    addybde8ed0e4e0f10ae0cfe7afb10fb4a6b = addybde8ed0e4e0f10ae0cfe7afb10fb4a6b + 'gm&#97;&#105;l' + '&#46;' + 'c&#111;m';
                    var addy_textbde8ed0e4e0f10ae0cfe7afb10fb4a6b = 'n&#111;r&#101;ply' + '&#64;' + 'gm&#97;&#105;l' + '&#46;' + 'c&#111;m';document.getElementById('cloakbde8ed0e4e0f10ae0cfe7afb10fb4a6b').innerHTML += '<a ' + path + '\'' + prefix + ':' + addybde8ed0e4e0f10ae0cfe7afb10fb4a6b + '\'>'+addy_textbde8ed0e4e0f10ae0cfe7afb10fb4a6b+'</a>';
                </script>
            </strong></p>
        <p dir="ltr"><strong>2010-11-10 11:40:40 1ZthQy-000586-3x SMTP connection outbound 1446579596 1ZthQy-000586-3x example.com <span id="cloak2f065553ec5960f808bafd29e9f9f657">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                <script type="bb66d1a163691c0b3ef2edb7-text/javascript">
                    document.getElementById('cloak2f065553ec5960f808bafd29e9f9f657').innerHTML = '';
                    var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                    var path = 'hr' + 'ef' + '=';
                    var addy2f065553ec5960f808bafd29e9f9f657 = 'n&#111;r&#101;ply' + '&#64;';
                    addy2f065553ec5960f808bafd29e9f9f657 = addy2f065553ec5960f808bafd29e9f9f657 + 'gm&#97;&#105;l' + '&#46;' + 'c&#111;m';
                    var addy_text2f065553ec5960f808bafd29e9f9f657 = 'n&#111;r&#101;ply' + '&#64;' + 'gm&#97;&#105;l' + '&#46;' + 'c&#111;m';document.getElementById('cloak2f065553ec5960f808bafd29e9f9f657').innerHTML += '<a ' + path + '\'' + prefix + ':' + addy2f065553ec5960f808bafd29e9f9f657 + '\'>'+addy_text2f065553ec5960f808bafd29e9f9f657+'</a>';
                </script>
            </strong></p>
        <p dir="ltr"><strong>2010-11-10 11:40:40 1ZthQy-000586-3x =&gt; <span id="cloak26e328a9cd40a0996e99db77ee56225f">This email address is being protected from spambots. You need JavaScript enabled to view it.</span>
                <script type="bb66d1a163691c0b3ef2edb7-text/javascript">
                    document.getElementById('cloak26e328a9cd40a0996e99db77ee56225f').innerHTML = '';
                    var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                    var path = 'hr' + 'ef' + '=';
                    var addy26e328a9cd40a0996e99db77ee56225f = 'n&#111;r&#101;ply' + '&#64;';
                    addy26e328a9cd40a0996e99db77ee56225f = addy26e328a9cd40a0996e99db77ee56225f + 'gm&#97;&#105;l' + '&#46;' + 'c&#111;m';
                    var addy_text26e328a9cd40a0996e99db77ee56225f = 'n&#111;r&#101;ply' + '&#64;' + 'gm&#97;&#105;l' + '&#46;' + 'c&#111;m';document.getElementById('cloak26e328a9cd40a0996e99db77ee56225f').innerHTML += '<a ' + path + '\'' + prefix + ':' + addy26e328a9cd40a0996e99db77ee56225f + '\'>'+addy_text26e328a9cd40a0996e99db77ee56225f+'</a>';
                </script> R=dkim_lookuphost T=dkim_remote_smtp H=gmail-smtp-in.l.google.com [133.14.243.47] X=TLSv1.2:ECDHE-RSA-C="250 2.0.0 OK 1446579596 fk5si44423567pbd.33 - gsmtp" 22010-11-10 11:40:40 1ZthQy-000586-3x Completed
            </strong></p> <span id="docs-internal-guid-9a01371d-d2f0-367b-81b4-e3e3c0f8b2af"><br /><br /></span>
    </div>
</div>
<ul class="pager pagenav">
    <li class="previous"> <a class="hasTooltip" title="How to Connect to the MySQL Database" aria-label="Previous article: How to Connect to the MySQL Database" href="/docs/how-to-connect-to-the-mysql-database" rel="prev"> <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a> </li>
    <li class="next"> <a class="hasTooltip" title="How to Configure CSF on Linux" aria-label="Next article: How to Configure CSF on Linux" href="/docs/how-to-configure-csf-on-linux" rel="next"> <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a> </li>
</ul>