---
title: Migration of http to https in Cpanel
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

    

<div itemprop="articleBody">
    <strong><span style={{fontSize: "xx-large"}}>Migration of http to https in Cpanel</span></strong>
    <p dir="ltr"><span style={{fontSize: "large"}}><br /><strong>A website request form without secure:</strong><br /><br /></span><span style={{fontSize: "14pt"}}>HTTP is Hyper Text Transfer protocol that is used in networking. Whenever basically you type a website in the browser. By default website loading from normal 80 port with http:// request.<br /><br />Whenever a request is initiated by the client to server, an underlying TCP handshake is done from client to server side. Once the handshake is completed then HTTP protocol starts sending requests and server fulfills the request based on the data available with it. <br /><br /><strong>A website request form with secure:</strong><br /><br />HTTPS is Hyper Text Transfer protocol secure that is used in networking. Whenever basically you type a <strong>domain name</strong> in the browser. By default website loading from normal 443 port with https:// request.<br /><br />This is Hypertext Transfer protocol with added security layer in place in the form on TLS/SSL. Servers and clients communicate with each other exactly the same as HTTP but over a secure channel.<br /><br />1) It is confirmed after using HTTPS that you are talking to the server directly that you are thinking of. <br />2) It also ensures that only the server reads the data you sent over the network. No else can read it. <br /></span></p>
        <span
        style={{fontSize: "large"}}>3) And also your secret data transfer with encrypted form.
            <br />
            <br />
            <br /><strong>With HTTPS How the SEO ranking gets improved:</strong></span>
    </p>
    <p></p>
    <p dir="ltr"><span style={{fontSize: "large"}}><br /></span><span style={{fontSize: "large"}}>The secure website has more priority for the Google analysis, If the website is loading from HTTPS it's the high trusted website consider by Google analysis.<br /><br />If you are any competitor having the same or any better than you. But there website insecure means, A Google analysis give the first priority to secure website. <br /><br />The visitor also giving more priority for the Secure website. because of the trusted company.<br /><br /><strong>After Install SSL It's unsecured or Padlock is Missing Error:</strong><br /><br /><strong>1. Check the SSL certificated is installed successfully or not</strong><br /><br />Once the SSL certificated is installed. Check the from the below links SSL is properly installed or not.<br /><br />https://www.sslshopper.com/ <br /><br />The SSLshopper is helping to check the SSL certificated is installed properly and then when it's gets expiring. SSL related query for your domain you can get it from the SSLshopper.<br /></span></p>
    <p></p>
    <p dir="ltr"><span style={{fontSize: "large"}}><strong>2. Then apply the redirection script for your .htaccess file.<br /><br /></strong>Copy and paste the redirection script to your .htaccess file and them replace your domain at the place of example.com.<strong><br /><br />RewriteEngine On</strong><br /><strong>RewriteCond %`{HTTP_HOST}` example\.com `[NC]`</strong><br /><strong>RewriteCond %`{SERVER_PORT}` 80</strong><br /><strong>RewriteRule ^(.*)$ https://example.com/$1 [R,L]<br /><br /><br />3. After applying the redirection script Still unsecured or Padlock is missing<br /><br /></strong>This problem with your file structure inside the PHP file you're using the unsecured links directly to script.<br /><br />For example:<br /><strong><br />&lt;a href="http://example.com/images/log.png"&gt;log&lt;/a&gt;<br /><br /></strong>Otherwise, you using the unsecured script inside the tables from the database. For that your export the database and find and replace the http:// to https://<strong><br /></strong><br /><br /><strong>4. In WordPress CMS after installing the SSL, it's shown unsecured or Padlock it missing</strong><br /><br />Manually how to change the http:// to https:// for your Wordpress website.<br /><br />Run the below script from your phpmyadmin <br /><br /></span></p>
        <span
        style={{fontSize: "12pt"}}>UPDATE wp_options SET option_value = replace(option_value, 'http://www.example.com', 'http://example.com') WHERE option_name = 'home' OR option_name = 'siteurl';</span>
            <br /><span style={{fontSize: "12pt"}}><br />UPDATE wp_posts SET post_content = replace(post_content, 'http://www.example.com', 'http://example.com');</span>
            <br /><span style={{fontSize: "12pt"}}><br />UPDATE wp_postmeta SET meta_value = replace(meta_value,'http://www.example.com','http://example.com');</span></p>
    <p></p>
    <p dir="ltr"><span style={{fontSize: "large"}}><br />2. From the WordPress Plugin redirect to http:// to https://.<br /><br />First, you need to install and activate the Really Simple SSL.<br /><br /><span style={{fontSize: "12pt", fontFamily: "arial, helvetica, sans-serif"}}>Upon activation, you need to visit the<strong> Settings » SSL</strong> page. The plugin will automatically detect your SSL certificate, and it will set up your WordPress site to use HTTPs.</span></p>
        <br />
        <br /><strong>Related to redirection method for other CMS refer the below links,</strong>
        <br />
        <br />Refer the below links for redirection method in Opencart, Magento, Joomla
        <br />https://help.hostingraja.in/how-tos/how-to-redirect-from-http-to-https-in-wordpress-magento-opencart-and-joomla
        <br />
        <br />
        </span>
    </p>
</div>

    
        
            <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 
    
    
        
            <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 
    

</div>