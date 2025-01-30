---
title: How to Configure CSF on Linux
excerpt: >-
  Configuration of csf on linux and steps to allow and deny IP in Config-server
  Firewall
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
    <h1><strong><span style="font-size: xx-large;">How to Configure CSF on Linux</span></strong></h1>
    <p dir="ltr"><span style="font-size: large;">As we have already discuss how to Install CSF on a server, in this tutorial we are going to discuss how to configure CSF on a <strong>Linux <a href="https://www.hostingraja.in/server/dedicated-servers">Dedicated</a> server</strong>.<br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;">AFter installing CSF on a server, a CSF firewall is fully ready to protect your server from dangerous assaults, but still you require to set extra rules and configure it so will will function properly to support you.<br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;">At this point you know why it is mentioned as Config-server Firewall because it still relied upon your requirements to configure to work properly.<br /><br /></span></p>
    <p dir="ltr"><strong><span style="font-size: x-large;">Allow &amp; Deny IP in Config-server Firewall:</span></strong></p>
    <p dir="ltr"><span style="font-size: large;">In the event that you have to permit or deny IP address using CLI, these decisions according to the accompanying are generally utilized:<br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;">Rundown out every single connected lead are given in CSF by utilizing this,</span></p>
    <p dir="ltr"><strong><span style="font-size: large;"> $ sudo csf -l</span></strong></p>
    <p dir="ltr"><span style="font-size: large;">To enable CSF &amp; LFD,</span></p>
    <p dir="ltr"><strong><span style="font-size: large;"> $ sudo csf -e</span></strong></p>
    <p dir="ltr"><span style="font-size: large;">You will see this message at the end,</span></p>
    <p dir="ltr"><span style="font-size: large;">Starting lfd: Done</span></p>
    <p dir="ltr"><span style="font-size: large;">csf and lfd have been enabled</span></p>
    <p dir="ltr"><span style="font-size: large;">Stop CSF Firewall Service,</span></p>
    <p dir="ltr"><span style="font-size: large;"> $ sudo csf -x</span></p>
    <p dir="ltr"><span style="font-size: large;">CSF is stopped, no worries utilize this</span></p>
    <p dir="ltr"><span style="font-size: large;"> $ sudo csf -s</span></p>
    <p dir="ltr"><span style="font-size: large;">Use the following command for restart</span></p>
    <p dir="ltr"><span style="font-size: large;"> $ sudo csf -r</span></p>
    <p dir="ltr"><span style="font-size: large;">To put your IP address to a lasting enable list in csf.allow:</span></p>
    <p dir="ltr"><span style="font-size: large;"> $ sudo csf -a 000.00.00.00</span></p>
    <p dir="ltr"><span style="font-size: large;">Remove from allow list</span></p>
    <p dir="ltr"><span style="font-size: large;"> $ sudo csf -ar 000.00.00.00</span></p>
    <p dir="ltr"><span style="font-size: large;">Put an IP into deny in csf.deny:</span></p>
    <p dir="ltr"><span style="font-size: large;"> $ sudo csf -d 000.00.00.00</span></p>
    <p dir="ltr"><span style="font-size: large;">Remove from Deny list,</span></p>
    <p dir="ltr"><span style="font-size: large;"> $ sudo csf -dr 000.00.00.00<br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;">On the off chance that you need to whitelist an IP, The given value in csf.conf of IGNORE_ALLOW will appear as "0" and on the off chance that you need to transform it to "1" and reboot administration of CSF on your <strong>Linux Dedicated server</strong>.</span></p>
    <p dir="ltr"><strong><span style="font-size: large;"> $ sudo csf -i</span></strong></p>
    <p dir="ltr"><span style="font-size: large;">Find your input pattern which an organize on IP-tables e.g: IP, Port and etc.</span></p>
    <p dir="ltr"><strong><span style="font-size: large;"> $ sudo csf -g 000.00.00.00</span></strong></p>
    <p dir="ltr"><span style="font-size: large;">Remove or flush blocked list</span></p>
    <p dir="ltr"><strong><span style="font-size: large;"> $ sudo csf -f</span></strong></p>
    <p dir="ltr"><span style="font-size: large;">Update CSF to the most recent version,</span></p>
    <p dir="ltr"><strong><span style="font-size: large;"> $ sudo csf -u</span></strong></p>
    <p dir="ltr"><span style="font-size: large;">csf is already at the most recent version: v9.28</span></p>
    <p dir="ltr"><span style="font-size: large;">All right, now we have learned how to enable or disable IP’s although what about ports?<br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;">Because of several choices in csf.conf we are simply beginning here.</span></p>
    <p dir="ltr"><span style="font-size: large;">Yet, don't stress we will direct you through the most straightforward route conceivable to configure CSF firewall.<br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;">In csf.conf file list of ports specified in TCP IPv4 as well as IPv6 but at present we will set this for IPv4 because many of us are well-know to handle it.<br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;">Additionally, it's critical to know which ports are opened or shut reason it'll influence your task on a server in your <strong>Linux Dedicated server hosting account</strong>.<br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;"># Allow incoming TCP ports</span></p>
    <p dir="ltr"><span style="font-size: large;">TCP_IN = "10,11,12,15,53,80,110,473,963,741,587,789,123"</span></p>
    <h1 dir="ltr"> </h1>
    <p dir="ltr"><span style="font-size: large;"># Allow outgoing TCP ports</span></p>
    <p dir="ltr"><span style="font-size: large;">TCP_OUT = "10,11,12,15,53,80,110,473,963,741,587,789,123"</span></p>
    <h1 dir="ltr"> </h1>
    <p dir="ltr"><span style="font-size: large;"># Allow incoming UDP ports</span></p>
    <p dir="ltr"><span style="font-size: large;">UDP_IN = "10,11,12"</span></p>
    <h1 dir="ltr"> </h1>
    <p dir="ltr"><span style="font-size: large;"># Allow outgoing UDP ports</span></p>
    <p dir="ltr"><span style="font-size: large;"># To allow outgoing traceroute add 33434:33523 to this </span></p>
    <p dir="ltr"><span style="font-size: large;">list</span></p>
    <p dir="ltr"><span style="font-size: large;">UDP_OUT = "10,11,12,15,53,80"</span></p>
    <h1 dir="ltr"> </h1>
    <p dir="ltr"><span style="font-size: large;">The ports given above TCP and UDP are enabled a web server on your <strong><a href="https://www.hostingraja.in/hosting">Linux</a> Dedicated server</strong> to impart utilizing default ports.<br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;">At the point when a server begins an administration that administration characterizes a port of correspondence and that is a passage to impart to outside world and for approaching movement.</span></p>
    <p dir="ltr"><span style="font-size: large;">You can verify at present on your system which administrations utilizing which particular ports for correspondence,</span></p>
    <p dir="ltr"><span style="font-size: large;"> $ sudo csf -p</span></p>
    <h1 dir="ltr"> </h1>
    <p dir="ltr"><span style="font-size: large;">Ports tuning in for outer connections and the executables running behind them:</span></p>
    <p dir="ltr"><span style="font-size: large;">Port/Proto Open Conn PID/User Command Line Executable</span></p>
    <p dir="ltr"><span style="font-size: large;">22/tcp 4/6 2 (736/root) /usr/sbin/sshd -D /usr/sbin/sshd</span></p>
    <p dir="ltr"><span style="font-size: large;">80/tcp 4/6 - (876/root) /usr/sbin/apache2 -k start /usr/sbin/apache2</span></p>
    <p dir="ltr"><span style="font-size: large;">80/tcp 4/6 - (878/www-data) /usr/sbin/apache2 -k start /usr/sbin/apache2</span></p>
    <p dir="ltr"><span style="font-size: large;">80/tcp 4/6 - (879/www-data) /usr/sbin/apache2 -k start /usr/sbin/apache2</span></p>
    <p dir="ltr"><span style="font-size: large;">8009/tcp -/- - (704/tomcat) /usr/lib/jvm/java-8-oracle/jre/bin/j... /usr/lib/jvm/java-8-oracle/jre/bin/java</span></p>
    <p dir="ltr"><span style="font-size: large;">8080/tcp -/- - (704/tomcat) /usr/lib/jvm/java-8-oracle/jre/bin/j... /usr/lib/jvm/java-8-oracle/jre/bin/java<br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;">You can set your custom ports on this arrangement underneath list indicates you default benefit ports which are broadly utilized as a part of association services,<br /><br /></span></p>
    <p dir="ltr"><span style="font-size: large;">Here are some widely recognized service ports,</span></p>
    <p dir="ltr"><span style="font-size: large;">21 : FTP</span></p>
    <p dir="ltr"><span style="font-size: large;">22 : SSH</span></p>
    <p dir="ltr"><span style="font-size: large;">23 : Telnet</span></p>
    <p dir="ltr"><span style="font-size: large;">25 : SMTP Mail Transfer</span></p>
    <p dir="ltr"><span style="font-size: large;">43 : WHOIS service</span></p>
    <p dir="ltr"><span style="font-size: large;">53 : NameServer (DNS)</span></p>
    <p dir="ltr"><span style="font-size: large;">80 : HTTP (Default Web Server)</span></p>
    <p dir="ltr"><span style="font-size: large;">110 : POP protocol (Email Service)</span></p>
    <p dir="ltr"><span style="font-size: large;">443 : HTTP Secure (SSL for HTTPS )</span></p>
    <p dir="ltr"><span style="font-size: large;">995 : POP over SSL/TLS</span></p>
    <p dir="ltr"><span style="font-size: large;">9999 : Urchin</span></p>
    <p dir="ltr"><span style="font-size: large;">3306 : MysQL Server</span></p>
    <p dir="ltr"><span style="font-size: large;">2082 : cPANEL Default</span></p>
    <p dir="ltr"><span style="font-size: large;">2083 : cPANEL - (Secure / SSL)</span></p>
    <p dir="ltr"><span style="font-size: large;">2086 : cPANEL WHM</span></p>
    <p dir="ltr"><span style="font-size: large;">2087 : cPANEL WHM - (Secure / SSL)</span></p>
    <p dir="ltr"><span style="font-size: large;">2095 : cpanel webmail</span></p>
    <p dir="ltr"><span style="font-size: large;">2096 : cpanel webmail - (Secure / SSL)</span></p>
    <p dir="ltr"><span style="font-size: large;">Plesk Control Panel : 8443</span></p>
    <p dir="ltr"><span style="font-size: large;">Direct Admin Control Panel: 2222</span></p>
    <p dir="ltr"><span style="font-size: large;">Webmin Control Panel : 10000</span></p>
    <h1 id="docs-internal-guid-130c7871-ca6c-ba49-2665-4a6ea8b735de" dir="ltr"><br /><br /><br /><br /></h1>
    <p dir="ltr"> </p>
</div>
<ul class="pager pagenav">
    <li class="previous"> <a class="hasTooltip" title="How to check Mail Log in a Dedicated Box using WHM?" aria-label="Previous article: How to check Mail Log in a Dedicated Box using WHM?" href="/docs/how-to-check-mail-log-in-a-server-using-whm" rel="prev"> <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a> </li>
    <li class="next"> <a class="hasTooltip" title="How to improve the Website Speed by 70% in One Hour" aria-label="Next article: How to improve the Website Speed by 70% in One Hour" href="/docs/how-to-improve-the-website-speed-by-70-in-one-hour" rel="next"> <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a> </li>
</ul>
