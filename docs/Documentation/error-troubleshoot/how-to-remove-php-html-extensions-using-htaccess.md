---
title: How to remove .php, .html, extensions using .htaccess.
excerpt: >-
  Easily remove .php and .html extensions using a .htaccess file for cleaner
  URLs
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
How to remove .php, .html, extensions using .htaccess. </h2>
</div>
<dl class="article-info muted">
<dt class="article-info-term">
</dt>
<dd class="modified">
<span class="icon-calendar" aria-hidden="true"></span>
<time datetime="2021-08-27T13:39:53+00:00" itemprop="dateModified">
Last Updated: 27 August 2021 </time>
</dd>
</dl>
<div itemprop="articleBody">
<h1 style="text-align: center;"><span style="font-size: xx-large;"><strong>How to remove .php, .html, extensions using .htaccess.</strong></span></h1>
<br/>
<div>
<p dir="ltr"> </p>
<p><b>What is a .htaccess file?</b></p>
<p> </p>
<p><span style="font-weight: 400;">In the page, we will discuss how the remove php, .html extensions using a .htaccess file. Before that let us know more about the .htaccess file. A .htaccess is basically a  configuration file for use on web servers. These .htaccess files can be used to alter the configuration of the Web Server software to enable/disable additional functionality and features. These features include basic redirect functionality, content password protection, image hotlink prevention, and PHP error logging.</span></p>
<p><span style="font-weight: 400;">A..htaccess file is a simple ASCII file that which is created with a Simple text editor like any notepad. You make configuration changes in the server using a .htaccess file.</span></p>
<br/>
<p><span style="font-weight: 400;">The .htaccess is just a file’s extension. It's not a file .htaccess, it is a simple .htaccess file. The .htaccess files can be uploaded to all sub-directories and main directories. For example, if you uploaded any .htaccess file located in your root directory of Domain.com, it would affect Domain.com/content/, Domain.com/content/images/, etc.</span></p>
<br/>
<p><b>How the .htaccess file helps you?</b></p>
<br/>
<p><span style="font-weight: 400;">Using .htaccess file can perform various operations such as </span></p>
<p><span style="font-weight: 400;">&gt;&gt;Using the .htaccess you can make sure that the  URLs are more user and search engine friendly.</span></p>
<p><span style="font-weight: 400;">&gt;&gt;You can remove the extensions like .php, .html, .htm, with the help of .htaccess</span></p>
<p><span style="font-weight: 400;">&gt;&gt;You can Redirect the user to different page or domain. </span></p>
<p><span style="font-weight: 400;">&gt;&gt; You also redirect the domain from http to https </span></p>
<p><span style="font-weight: 400;">&gt;&gt;Blocking the Ip by countries or series of IPs.</span></p>
<p><span style="font-weight: 400;">&gt;&gt;password protection for the specific Directories.</span></p>
<p><span style="font-weight: 400;">&gt;&gt;Rewrite URL's, error logging, hotlink prevention techniques</span></p>
<br/>
<p><span style="font-weight: 400;">And many other uses like </span><span style="font-weight: 400;">DirectoryIndex, Adding MIME types</span><span style="font-weight: 400;">, you can </span><span style="font-weight: 400;">enable CGI outside of the CGI-bin, disable directory listings, help in setting server timezone and Changing server signature, you can also prevent access to PHP includes files and  php.ini and you can also prevent requests with invalid characters</span></p>
<p><b>Now we will see how to remove extensions using .htaccess:</b></p>
<br/>
<p><span style="font-weight: 400;">To remove the .php extension from a file, for example, Domain.com/admin.php to Domain.com/admin you have to add the mentioned below code in the .htaccess file.</span></p>
<br/><br/><br/><br/>
<p><b>RewriteEngine On</b></p>
<p><b>RewriteCond %{REQUEST_FILENAME} !-f</b></p>
<p><b>RewriteRule ^([^\.]+)$ $1.php [NC,L]</b></p>
<img src="https://image.hostingraja.in/images/remove-php-html.webp" /><br/><br/>
<p><span style="font-weight: 400;">To remove the .html extension from a file, for example, Domain.com/admin.html to Domain.com/admin  you have to add the mentioned below code in the .htaccess file.</span></p>
<br/>
<p><b>RewriteEngine On</b></p>
<p><b>RewriteCond %{REQUEST_FILENAME} !-f</b></p>
<p><b>RewriteRule ^([^\.]+)$ $1.html [NC,L]</b></p>
<br/><img src="https://image.hostingraja.in/images/remove-php-html-one.webp"><br/><br/>
<p><span style="font-weight: 400;">By including the above appropriate code you can remove the extension. You can also remove the php extension of the particular folder that is </span><span style="font-weight: 400;">if you want to remove the Index.php successfully from your website URL then you need to make sure that the  mod_rewrite module is enabled on your server. So to know whether the mod_rewrite module is enabled or not you can contact our support team and they will help in this case. But you can also try a technique called URL rewriting where it allows you to hide the index.php portion of the URL behind the scenes. To remove the “index.php” from your site’s URLs, you need to make sure your server is set up to pass 404 requests off to index.php file behind the scenes. In Apache, you need redirection code in your site’s .htaccess file. If there is no .htaccess file existing (also check if the .htaccess file is present in the hidden files)then you need to create a new file called “.htaccess” in the site’s web root directory. </span></p>
<p> </p>
<p><span style="font-weight: 400;">Adding the below code in the .htaccess file you can remove the extension for a specific folder. Here the code  index.php file is taken as an example. For removing the extension for any other folder you need to replace the index.php with the desired file name.  </span></p>
<p> </p>
<p><b>&lt;IfModule mod_rewrite.c&gt;</b></p>
<p><b>   RewriteEngine On</b></p>
<p><b>   RewriteCond %{REQUEST_FILENAME} !-f</b></p>
<p><b>   RewriteCond %{REQUEST_FILENAME} !-d</b></p>
<p><b>   RewriteRule ^(.*)$ /index.php?/$1 [L]</b></p>
<p><b>&lt;/IfModule</b></p>
<p> </p>
<p><span style="font-weight: 400;">But sometimes there will be some problems like links returning 404s, a â€œNo Input File Specifiedâ€ error or all links may returning to the same content. So, in that case, you can force query strings. And still, if you are facing the same issue then you can rename .htaccess to something else and set Name of your websiteâ€™s index page in the cPanel back to index.php.</span></p>
<br/>
<p><span style="font-weight: 400;">If your website is using CodeIgniter framework and you need to remove the index.php from the URL then you can do it by removing it from the config file and with a proper .htaccess file with rewrite rule to remove .htaccess file, If index.php is removed without proper a proper .htaccess file or configuration steps then the site will show 404 Error page.</span></p>
<p> </p>
<p><b>If you need any assistance, feel free to contact our technical team members as they are available 24/7 via phone call,  chat, <a href="https://support.hostingraja.in/">ticket system</a>.</b></p>
<div> </div>
</div> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="Disk Overused Issue" aria-label="Previous article: Disk Overused Issue" href="/docs/disk-overused-issue" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="Error 503 - Service Temporarily Unavailable on Magento Sites" aria-label="Next article: Error 503 - Service Temporarily Unavailable on Magento Sites" href="/docs/error-503-service-temporarily-unavailable-on-magento-sites" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>