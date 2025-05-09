---
title: How to resolve the error establishing a Database connection
excerpt: >-
  Here is the information about How to resolve the error establishing a Database
  connection
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
    <strong>How to resolve the error establishing a Database connection</strong>
    <p dir="ltr"><strong> </strong></p>
    <p><strong>What is “Error establishing a database connection”?</strong></p>
    <p dir="ltr"><strong> </strong></p>
    <p><span style={{fontWeight: 400}}>The “error establishing a database connection” is one of the most common and also scary errors that WordPress users can encounter. This error establishing a Database connection sometimes also known as the white screen of death (WSOD). And this error means that your website is no longer communicating or in other words your website no longer has access to your database and thus your entire website will go down. </span></p>
    <p dir="ltr"><strong> </strong></p>
    <p><strong>This is not something to be taken lightly! But you should try and resolve this immediately as this can directly affect your sales, traffic, and analytics.</strong></p>
    <p dir="ltr"><strong> </strong></p>
    <p><strong>Understanding The Problem</strong></p>
    <p dir="ltr"><strong> </strong></p>
    <p><span style={{fontWeight: 400}}>In WordPress, it uses two main pieces of technology to provide you with all its best and awesome techniques like PHP and MySQL.</span></p>
    <p dir="ltr"><strong> </strong></p>
    <p><span style={{fontWeight: 400}}>&gt;&gt;&gt; PHP is a programming language. In WordPress the core WordPress files – have been written in PHP. </span></p>
    <p dir="ltr"><strong> </strong></p>
    <p><span style={{fontWeight: 400}}>&gt;&gt;&gt; MySQL is database technology. And WordPress uses a MySQL database to store all of your website's content. And this also includes your post, pages with smaller elements like the title of your website, the layout of your widgets, the color settings, etc. Basically, the MySQL database is where every, even the smallest piece of information about your website, is kept.</span></p>
    <p dir="ltr"><strong> </strong></p>
    <p><span style={{fontWeight: 400}}>By putting these two together WordPress uses PHP commands to connect to the MySQL database to get the information it needs and later it displays everything on the screen. </span></p>
    <p dir="ltr"><strong> </strong></p>
    <p><span style={{fontWeight: 400}}>Now this is where the error comes into play. The error occurs when your WordPress account cannot access to the information in the database via PHP commands. So when that happens WordPress basically does not know what to do next! So the only thing it will display is - “Error establishing a database connection.”</span></p>
    <p> </p>
    <p dir="ltr"><strong>Why do we get this type of error while opening the website...?</strong></p>
    <p> </p>
    <p dir="ltr">Basically, this error will occur when the website is unable to establish a connection to the database,<strong> The reasons are:</strong></p>
    <p> </p>
    
        
            <p dir="ltr">the database credentials are wrong or it has been changed.</p>
        
    
    <p dir="ltr"> </p>
    
        
            <p dir="ltr">It could be that the database server is not responding.</p>
        
    
    <p dir="ltr"> </p>
    
        
            <p dir="ltr">it could be that the database has been corrupted.</p>
        
    
    <p dir="ltr"> </p>
    
        
            <p dir="ltr">maximum times this problem will occur due to the wrong credentials of the database.</p>
        
    
    <p> </p>
    <p dir="ltr"><strong>Let's have a look at how to troubleshoot this problem</strong></p>
    <p> </p>
    
        
            <p dir="ltr">Checking the wp-config.php file</p>
        
    
    <p> </p>
    <p dir="ltr">Wp-config file is very important for your entire WordPress installation site, In this, you have to mention the valid database details of the WordPress to connect the database. If you change the database credential you have to mention the same details in this file as well. First, you need to check everything is fine in your “web.config” file as mentioned below.</p>
    <p> </p>
    <p dir="ltr">define('DB_NAME', 'database-name');</p>
    <p dir="ltr">define('DB_USER', 'database-username');</p>
    <p dir="ltr">define('DB_PASSWORD', 'database-password');</p>
    <p dir="ltr">define('DB_HOST', 'localhost');</p>
    <p> </p>
    <p dir="ltr">If everything is fine in the “web.config” file then the problem might be from the database server or something went wrong on the server end.</p>
    <p> </p>
    
        
            <p dir="ltr">Check the MySql server(your web host)</p>
        
    
    <p> </p>
    <p dir="ltr">Often you will see this error when your site get load with high traffic with more mysql connections, If your host cannot handle such type of traffic (especially in the shared hosting) at this time the best way is to contact your hosting provider to upgrade your server to which can handle more traffic (we call these servers as VPS or CLOUD)</p>
    <p> </p>
    <p dir="ltr">For the users those who feel that there is some issue in the database server end, they can test some websites by pointing to the same server. If the other websites also get the same error then there might be an issue from the database server end.</p>
    <p> </p>
    <p dir="ltr">If you don't have any other sites on the same hosting for testing, login to your cPanel and open the phpmyadmin and check the database connection if its connect then fine but if in case if its not connected then might be an issue from the database server end. If you can connect then you need to check the database permissions is assigned sufficiently.</p>
    <p> </p>
    <p dir="ltr">To check the connection create a new file called “testconnection.php” and paste the below code.</p>
    <p> </p>
    <p dir="ltr">&lt;?php</p>
    <p dir="ltr">$link = mysql_connect('localhost', 'root', 'password');</p>
    <p dir="ltr">if (!$link) {</p>
    <p dir="ltr">die('Could not connect: ' . mysql_error());</p>
    <p dir="ltr">}</p>
    <p dir="ltr">echo 'Connected successfully';</p>
    <p dir="ltr">mysql_close($link);</p>
    <p dir="ltr">?&gt;</p>
    <p> </p>
    <p dir="ltr">If its get connected you will get the message “connected successfully” then we need to assume that the database has sufficient permissions.</p>
    <p> </p>
    <p dir="ltr">If you cannot connect the database by going to the phpmyadmin then you need to assume that something went wrong on the database server and you have to check with your server administrator.<br /><br /></p>
</div>

      <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span>  
      <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span>