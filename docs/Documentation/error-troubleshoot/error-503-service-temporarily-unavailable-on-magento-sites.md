---
title: Error 503 - Service Temporarily Unavailable on Magento Sites
excerpt: >-
  Resolve Magento's Error 503 with HostingRaja's robust hosting solutions and
  optimized resource management
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
<h2 itemprop="headline">
Error 503 - Service Temporarily Unavailable on Magento Sites </h2>
</div>
<dl class="article-info muted">
<dt class="article-info-term">
</dt>
</dl>
<div itemprop="articleBody">
<h1 dir="ltr" style="text-align: center;"><strong>Error 503 - Service Temporarily Unavailable on Magento Sites</strong></h1>
<p dir="ltr"><strong><span style="font-family: georgia, palatino;">Why we do get this error...?</span></strong><br/><strong><br/></strong></p>
<p dir="ltr">while installation of the Magento, the Magento will create the “maintenance.flag” Generally it will get removed automatically after the installation of the Magento but sometimes if in case if it was not removed the users <strong>will get the error message</strong> while opening the sites. The error will look like as mentioned in the below screenshot.</p>
<p dir="ltr"> </p>
<p><span style="font-weight: 400;">One of the main cause for 503 error is when your hosting account starts utilizing all of the available CPU resources. You can also check your resource usage on your server from your User Area. Moreover your server resources can be exceeded due to a traffic spike that is coming to your website and also because of poor optimization of website and database. </span></p>
<p dir="ltr"> </p>
<p><span style="font-weight: 400;">But today of you are using our server solution then you face any issues related to resource consumption. Because here at <a href="https://www.hostingraja.in/server/vps-servers/"><b>HostingRaja</b></a> we provide the <a href="https://www.hostingraja.in/">best hosting in India</a> with amazing and better resources. Thus you can easily handle and manage your website. And today if you are using cloud server then you also get the advantages of scaling your resource. Hence you will not face any issues with your Magento website. </span></p>
<p> </p>
<p dir="ltr"><strong>NOTE: The file “maintenance.flag” will create in the root directory.</strong></p>
<p><br/><br/></p>
<p dir="ltr"><img style="display: block; margin-left: auto; margin-right: auto;" title="Magento Service Unavailable" src="https://image.hostingraja.in/images/article/magento-service-unavailable.png" alt="Magento Service Unavailable" border="0" /></p>
<p> </p>
<p dir="ltr"><strong><span style="font-family: georgia, palatino;">SOLUTION:</span><br/><br/></strong></p>
<p dir="ltr">Once we get this error we feel that it's very difficult to resolve but the <strong>solution is very simple.</strong> Just we need to rename or remove the file name “maintenance.flag” which was created in the root directory while installation of the Magento hosting service.</p>
<p> </p>
<p dir="ltr"><span style="font-family: georgia, palatino;"><strong>Then what is “maintenance.flag”.......?</strong></span></p>
<p> </p>
<p dir="ltr">Usually the file “maintenance.flag” will consist the code which blocks the users to visit the site. The code will looks like as below:</p>
<p> </p>
<p dir="ltr">$maintenanceFile = 'maintenance.flag';<br class="kix-line-break" />$ip = $_SERVER['REMOTE_ADDR'];<br class="kix-line-break" /><br class="kix-line-break" />/***************<br class="kix-line-break" />* IP's allowed in maintenance.<br class="kix-line-break" />* Use publicly visible IP addresses on LIVE, local if on DEV<br class="kix-line-break" />***************/<br class="kix-line-break" /><br class="kix-line-break" />$allowed = array('10.0.0.100','10.0.0.101','10.0.0.20');<br class="kix-line-break" /><br class="kix-line-break" />if (file_exists($maintenanceFile) &amp;&amp; !in_array($ip, $allowed)) {<br class="kix-line-break" />   $basePath = dirname($_SERVER['PHP_SELF']);<br class="kix-line-break" />   include_once dirname(__FILE__) . '/errors/503.php';<br class="kix-line-break" />   exit;<br class="kix-line-break" />}</p>
<div> </div>
<div>
<p><strong>You can also follow the below step to solve this issue: </strong></p>
<br/>
<p><span style="font-weight: 400;"><strong>Step 1.</strong> Log into the cPanel of your Magento shop</span></p>
<br/>
<p><span style="font-weight: 400;"><strong>Step 2.</strong> Now in there under category Files, click on Filemanager.</span></p>
<br/>
<p><span style="font-weight: 400;"><strong>Step 3.</strong> Next go to the homedir of your Magento shop.</span></p>
<br/>
<p><span style="font-weight: 400;"><strong>Step 4.</strong> In here you need to Delete the maintenance.flag file</span></p>
<br/>
<p><span style="font-weight: 400;"><strong>Step 5.</strong> Next go to the var/cache folder of your Magento shop</span></p>
<br/>
<p><span style="font-weight: 400;"><strong>Step 6.</strong> In here Delete all the caching files</span></p>
<br/>
<p><span style="font-weight: 400;"><strong>Step 7.</strong> Now if you reload the webshop, the error should be gone!</span></p>
</div> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="How to remove .php, .html, extensions using .htaccess." aria-label="Previous article: How to remove .php, .html, extensions using .htaccess." href="/docs/how-to-remove-php-html-extensions-using-htaccess" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="How to Open Port in Linux" aria-label="Next article: How to Open Port in Linux" href="/docs/how-to-open-port-in-linux" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>
