---
title: How to Connect to the MySQL Database
excerpt: Best Linux, Windows, Unlimited plans wirh 55% OFFER
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
<h1>How to Connect to the MySQL Database</h1>
<h2><strong>What is MySQL?</strong></h2>
<p><span style="font-weight: 400;">MySQL is one of the most popular Open Source SQL database management systems which is developed and distributed as well as supported by Oracle Corporation. <br/><br/></span></p>
<strong>Important points to remember on MySQL:<br/><br/></strong>
<p><strong>MySQL is a data management system:</strong></p>
<p><span style="font-weight: 400;">Database can be defined as the collection of data. Database could be anything which can be from a simple shopping list to a picture gallery, a database can also be a vast collection of data. A database management system is required for adding, accessing as well as processing the data stored in a computer database. We might be knowing that computers are one of the best equipment to store large amounts of data, hence database management plays an important role in computing. Even we can say that <a title="dedicated servers" href="https://www.hostingraja.in/server/dedicated-servers/">dedicated servers</a> are a form of the computer where a large amount of data is stored.</span></p>
<p><span style="font-weight: 400;"><strong>MySQL is relational</strong>:</span></p>
<p><span style="font-weight: 400;">Here in MySQL the data is stored in separate tables rather than storing it in one single storeroom. Hence the database is structured in way to optimize it for speed. Hence this type of structured model gives a flexible environment. The best part is that you can set up the rules governing the relationship between different data fields. </span></p>
<p><strong>My SQL is Open Source</strong></p>
<p><span style="font-weight: 400;">Open Source can be defined as the way by which the user can modify the software. Hence MySQL can be modified by downloading it through the internet, one can study the source code and change it according to its needs. </span></p>
<p><strong>MySQL Server is faster, scalable, reliable, and easy to use</strong></p>
<p><span style="font-weight: 400;">MySQL is easy to run on a desktop or laptop along with the applications. If an entire machine is dedicated to MySQL, one can adjust the settings so that you can utilize the memory, I/O capacity, and CPU power.  MYSQL <a title="Server" href="https://www.hostingraja.in/server/">Server</a> is offering a rich and useful set of functions which makes it best suited for accessing databases on the internet.</span></p>
<p><strong>MySQL works in embedded systems</strong></p>
<p><span style="font-weight: 400;">The MySQL Database Software consists of a multi-threaded SQL server, which supports different types of back ends, administrative tools, and a wide range of applications.</span></p>
<p><strong> Contributed MySQL software is available</strong></p>
<p><span style="font-weight: 400;">MySQL Server has features developed with close cooperation for users. Most of the applications or languages across the web support the MySQL Database Server.</span></p>
<br/><br/>If you do not know have MySQL database and MySQL user, refer to the following links to create the MySQL database and MySQL user,<br/><br/><br/>Cpanel<br/><br/><a href="/web/20231205195629/https://help.hostingraja.in/error-troubleshoot/how-to-set-up-a-database-using-the-mysql-database-wizard">https://help.hostingraja.in/error-troubleshoot/how-to-set-up-a-database-using-the-mysql-database-wizard</a><br/><br/>Plesk<br/><a href="/web/20231205195629/https://help.hostingraja.in/how-tos/how-to-create-a-mysql-mssql-database-in-plesk"><br/>https://help.hostingraja.in/how-tos/how-to-create-a-mysql-mssql-database-in-plesk<br/></a><br/>Ovipanel<br/><br/><a href="https://www.ovipanel.in/tutorials/database/how-to-create-mysql-database">https://www.ovipanel.in/tutorials/database/how-to-create-mysql-database<br/></a><a href="https://www.ovipanel.in/tutorials/database/mysql-database">https://www.ovipanel.in/tutorials/database/mysql-database<br/></a><br/>
<h3><strong>Below are the three methods we can connect the MySQL using PHP</strong></h3>
<br/><strong>1. MySQLi Procedure</strong><br/><br/><strong>Local Mysql Connection</strong> <br/><br/>
<div class="view-code-dev">$db_server = 'locahost';<br/>$db_username = 'username';<br/>$db_password = 'password';<br/>$db_name = 'database';<br/><br/><br/>$connect = mysqli_connect($db_server, $db_username, $db_password, $db_name);<br/><br/>if (!$connect) {<br/> die("Connection failed: " . mysqli_connect_error());<br/>}<br/>...<br/>...<br/>mysqli_close($conn);</div>
<br/><br/><strong>Remote Mysql Connection</strong><br/><br/>
<div class="view-code-dev">$db_server = 'server_ip';<br/>$db_username = 'username';<br/>$db_password = 'password';<br/>$db_name = 'database';<br/>$db_port = 'port';<br/><br/><br/>$connect = mysqli_connect("$db_server:$db_port", $db_username, $db_password, $db_name);<br/><br/>if (!$connect) {<br/> die("Connection failed: " . mysqli_connect_error());<br/>}<br/>....<br/>....<br/>mysqli_close($connect);</div>
<br/><br/><strong>2. PDO</strong><br/><br/><strong>Local Mysql Connection</strong> <br/><br/>
<div class="view-code-dev">$db_server = 'locahost';<br/>$db_username = 'username';<br/>$db_password = 'password';<br/>$db_name = 'database';<br/><br/>try {<br/>$connect= new PDO("mysql:host=$db_server;dbname=$db_name", $db_username, $db_password);<br/>$connect-&gt;setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);<br/>echo "Connected successfully";<br/>} catch(PDOException $e) {<br/>echo "Connection failed: " . $e-&gt;getMessage();<br/>}<br/>....<br/>...<br/>$connect = null;</div>
<br/><br/><strong>Remote Mysql Connection</strong><br/><br/>
<div class="view-code-dev">$db_server = 'server_ip';<br/>$db_username = 'username';<br/>$db_password = 'password';<br/>$db_name = 'database';<br/>$db_port = 'port';<br/><br/>try {<br/>$connect = new PDO("mysql:host=$db_server:$db_port;dbname=$db_name", $db_username, $db_password);<br/>$connect-&gt;setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);<br/>echo "Connected successfully";<br/>} catch(PDOException $e) {<br/>echo "Connection failed: " . $e-&gt;getMessage();<br/>}<br/>....<br/>...<br/>$connect = null;</div>
<br/><strong>3. MySQLi Object-Oriented</strong><br/><br/><strong>Local Mysql Connection</strong> <br/><br/>
<div class="view-code-dev">$db_server = 'locahost';<br/>$db_username = 'username';<br/>$db_password = 'password';<br/>$db_name = 'database';<br/><br/>$connect = new mysqli($db_server, $db_username, $db_password, $db_name);<br/><br/>if ($connect-&gt;connect_error) {<br/> die("Connection failed: " . $connect-&gt;connect_error);<br/>}<br/>....<br/>....<br/>$connect-&gt;close();</div>
<br/><strong>Remote Mysql Connection</strong><br/><br/>
<div class="view-code-dev">$db_server = 'server_ip';<br/>$db_username = 'username';<br/>$db_password = 'password';<br/>$db_name = 'database';<br/>$db_port = 'port';<br/><br/>$connect = new mysqli("$db_server:$db_port", $db_username, $db_password, $db_name);<br/><br/>if ($connect-&gt;connect_error) {<br/> die("Connection failed: " . $connect-&gt;connect_error);<br/>}<br/>.....<br/>.....<br/>$connect-&gt;close();</div>
<br/><br/>Based on the CMS / Frameworks we can connect the MySQL varies method,<br/><br/><strong>WordPress CMS</strong><br/><br/>Locate your wp-config.php file under the public_html folder,<br/><br/>Local Mysql Connection <br/><br/>
<div class="view-code-dev">define('DB_HOST', 'locahost');<br/>define('DB_USER', 'username');<br/>define('DB_PASSWORD', password');<br/>define('DB_NAME', 'database');</div>
<br/><br/>Remote Mysql Connection<br/><br/>
<div class="view-code-dev">define('DB_HOST', 'server_ip:port');<br/>define('DB_USER', 'username');<br/>define('DB_PASSWORD', password');<br/>define('DB_NAME', 'database');</div>
<br/> <br/><a title="Larvel Frameworks" href="https://www.hostingraja.in/server/laravel-server-india/">Larvel Frameworks</a><br/><br/>Locate your app/config/database.php file under the public_html folder,<br/><br/><strong>Local Mysql Connection</strong> <br/><br/>
<div class="view-code-dev">'mysql' =&gt; array(<br/> 'read' =&gt; array(<br/> 'host' =&gt; 'locahost',<br/> ),<br/> 'write' =&gt; array(<br/> 'host' =&gt; 'locahost'<br/> ),<br/> 'driver' =&gt; 'mysql',<br/> 'database' =&gt; 'database',<br/> 'username' =&gt; 'username',<br/> 'password' =&gt; 'password',<br/> 'charset' =&gt; 'utf8',<br/> 'collation' =&gt; 'utf8_unicode_ci',<br/> 'prefix' =&gt; '',<br/>),</div>
<br/><br/><strong>Remote Mysql Connection</strong><br/><br/>
<p class="view-code-dev">'mysql' =&gt; array(<br/> 'read' =&gt; array(<br/> 'host' =&gt; env('DB_HOST', 'server_ip'),<br/> 'port' =&gt; env('DB_PORT', '3306'),<br/> ),<br/> 'write' =&gt; array(<br/> 'host' =&gt; env('DB_HOST', 'server_ip'),<br/> 'port' =&gt; env('DB_PORT', '3306'),<br/> ),<br/> 'driver' =&gt; 'mysql',<br/> 'database' =&gt; env('DB_DATABASE', 'database'),<br/> 'username' =&gt; env('DB_USERNAME', 'username'),<br/> 'password' =&gt; env('DB_PASSWORD', 'password'),<br/> 'charset' =&gt; 'utf8',<br/> 'collation' =&gt; 'utf8_unicode_ci',<br/> 'prefix' =&gt; '',<br/>),<br/><br/><br/><br/></p>
<h3><strong>How to connect DB in MySQL (OviPanel)</strong><br/><br/></h3>
<p><span style="font-weight: 400;">There are three ways  to connect PHP to MySQL<br/><br/>            i) MySQL<br/></span>           ii) MySQLi<br/><span style="font-weight: 400;">           iii) PDO <br/><br/></span><b> i) MySQL</b></p>
<p>mysql_connect() function is helpful to open the connection in MySQL. Earlier PHP versions only used this function. Till 5.6 PHP version, this function working fine but PHP 7     version that function was deprecated due to security issues </p>
<p><span style="font-weight: 400;"> </span></p>
<p><span style="font-weight: 400;">&lt;?php</span></p>
<p><span style="font-weight: 400;">$connection = mysql_connect('localhost', 'mysqluser', 'mysqlpassword');</span></p>
<p><span style="font-weight: 400;">if (!$connection ) {</span></p>
<p><span style="font-weight: 400;">    die('Could not connect: ' . mysql_error());</span></p>
<p><span style="font-weight: 400;">}</span></p>
<p><span style="font-weight: 400;">echo 'Connected successfully';</span></p>
<p><span style="font-weight: 400;">mysql_close($connection );</span></p>
<p><span style="font-weight: 400;">?&gt;</span></p>
<p><span style="font-weight: 400;"> </span></p>
<p><span style="font-weight: 400;">Update mysqluser, mysqlpassword which was created by our end using ovipanel. <br/><br/><br/></span><b>ii) MySQLi</b></p>
<p><span style="font-weight: 400;"> </span></p>
<p><span style="font-weight: 400;">MySQLi is known as a MySQL improved extension. compared to MySQL, MySQLi has a lot of enhancements like object-oriented interface, support for Multiple Statements &amp; prepared statements, transaction, and so on. This function will be available from PHP5 </span></p>
<p><span style="font-weight: 400;"> </span></p>
<h4><b>Object oriented style:</b></h4>
<p><span style="font-weight: 400;">&lt;?php</span></p>
<p><span style="font-weight: 400;">$connection = new mysqli("localhost","mysqluser","mysqlpassword","mysqldatabase");</span></p>
<p><span style="font-weight: 400;">if ($connection -&gt; connect_errno) {</span></p>
<p><span style="font-weight: 400;">  echo "Failed to connect to MySQL: " . $mysqli -&gt; connect_error;</span></p>
<p><span style="font-weight: 400;">  exit();</span></p>
<p><span style="font-weight: 400;">}</span></p>
<p><span style="font-weight: 400;">?&gt;</span></p>
<h4><b>Procedural style:</b></h4>
<p><span style="font-weight: 400;">&lt;?php</span></p>
<p><span style="font-weight: 400;">$connection = mysqli_connect("localhost","mysqluser","mysqlpassword","mysqldatabase");</span></p>
<p><span style="font-weight: 400;"> </span></p>
<p><span style="font-weight: 400;">// Check connection</span></p>
<p><span style="font-weight: 400;">if (mysqli_connect_errno()) {</span></p>
<p><span style="font-weight: 400;">  echo "Failed to connect to MySQL: " . mysqli_connect_error();</span></p>
<p><span style="font-weight: 400;">  exit();</span></p>
<p><span style="font-weight: 400;">}</span></p>
<p><span style="font-weight: 400;">?&gt;</span></p>
<p><span style="font-weight: 400;">Update mysqluser, mysqlpassword, mysqldatabase which was created by our end using ovipanel. </span></p>
<p><span style="font-weight: 400;"> </span></p>
<p><strong>iii) PDO </strong></p>
<p><span style="font-weight: 400;">PHP Data Objects are helpful to connect the MySQL database via PHP. PDO enabled by default.</span></p>
<p><span style="font-weight: 400;"><br/><br/></span></p>
<p><span style="font-weight: 400;">&lt;?php</span></p>
<p><span style="font-weight: 400;">$servername = "localhost";</span></p>
<p><span style="font-weight: 400;">$username = "mysqluser";</span></p>
<p><span style="font-weight: 400;">$password = "mysqlpassword";</span></p>
<p><span style="font-weight: 400;"> </span></p>
<p><span style="font-weight: 400;">try {</span></p>
<p><span style="font-weight: 400;">  $connection = new PDO("mysql:host=$servername;dbname=mysqldatabase", $username, $password);</span></p>
<p><span style="font-weight: 400;">  // set the PDO error mode to exception</span></p>
<p><span style="font-weight: 400;"> $conn-&gt;setAttribute(PDO::ATTR_ERRMODE, PDO::ERRMODE_EXCEPTION);</span></p>
<p><span style="font-weight: 400;">  echo "Connected successfully";</span></p>
<p><span style="font-weight: 400;">} catch(PDOException $e) {</span></p>
<p><span style="font-weight: 400;">  echo "Connection failed: " . $e-&gt;getMessage();</span></p>
<p><span style="font-weight: 400;">}</span></p>
<p><span style="font-weight: 400;">?&gt;</span></p>
<p><span style="font-weight: 400;"> </span></p>
<p><span style="font-weight: 400;">Update mysqluser, mysqlpassword, mysqldatabase which was created by our end using ovipanel. </span></p>
<p><span style="font-weight: 400;"><br/><br/></span></p>
<h3 class="view-code-dev"><br/><br/></h3> </div>
<ul class="pager pagenav">
<li class="previous">
<a class="hasTooltip" title="How to secure your Wordpress website " aria-label="Previous article: How to secure your Wordpress website " href="/web/20231205195629/https://help.hostingraja.in/how-tos/how-to-secure-your-wordpress-website" rel="prev">
<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> </a>
</li>
<li class="next">
<a class="hasTooltip" title="How to check Mail Log in a Dedicated Box using WHM?" aria-label="Next article: How to check Mail Log in a Dedicated Box using WHM?" href="/web/20231205195629/https://help.hostingraja.in/how-tos/how-to-check-mail-log-in-a-server-using-whm" rel="next">
<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> </a>
</li>
</ul>
</div>