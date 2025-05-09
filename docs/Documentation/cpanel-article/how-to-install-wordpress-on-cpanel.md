---
title: how to install wordpress on cpanel
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
<span style={{fontSize: "24pt"}}><strong>Installing WordPress on cPanel</strong></span>
<p><span style={{fontSize: "14pt"}}> </span></p>
<div dir="ltr"><span style={{fontSize: "x-large", fontFamily: "georgia, palatino"}}><strong>A Step-by-Step Guide with HostingRaja</strong></span></div>
<p><span style={{fontSize: "large"}}>WordPress is one of the most commonly used content management systems used worldwide. And, cPanel is one of the most popular web hosting control panels. Together, they make hosting your website as easy as baking. So, I thought I’d try and simplify the process of installing WordPress on cPanel, for both seasoned web enthusiasts and beginners alike. </span></p>
<p><span style={{fontSize: "large"}}>This article covers the following in detail; standard and manual WordPress installations, setting up WordPress on a subdomain, and installing themes through cPanel. Let's dive into the world of WordPress and cPanel, and start building your online presence today. </span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "18pt"}}><strong><span style={{fontFamily: "georgia, palatino", color: "#000000"}}>What Do You Need Before Installing WordPress on cPanel? </span></strong></span></p>
<p><span style={{fontSize: "large"}}>Installing your WordPress site on cPanel is not the first step of being online. Before you start the installation process, there are a few things you should know. This preparation is essential for a smooth and efficient installation. Make sure you everything mentioned below :</span></p>
<p dir="ltr"> </p>
<p><span style={{fontSize: "14pt"}}>Step 1:<span style={{fontWeight: 400}}> A Hosting Account with cPanel Access: Almost all web hosting providers will offer a cPanel with their hosting plans. They will provide you with the login credentials for your cPanel account. You can contact your hosting provider for assistance if you don’t have the credentials. </span></span></p>
<p><span style={{fontSize: "14pt"}}>Step 2:<span style={{fontWeight: 400}}>  Domain Name: Your domain name acts as your website’s address on the internet(eg. www.yourdomain.com). If you don’t have a domain name yet, you should register one and link it to your hosting account. </span></span></p>
<p><span style={{fontSize: "14pt"}}>Step 3:<span style={{fontWeight: 400}}>  A Stable Internet Connection: While this might seem obvious, a stable internet connection is vital to prevent any interruptions during the installation process.</span></span></p>
<p><span style={{fontSize: "14pt"}}>Step 4:<span style={{fontWeight: 400}}>  Basic Understanding of cPanel: It is helpful to have some familiarity with navigating through cPanel. If you’re new to cPanel, don’t worry; I’ll guide you through the necessary steps. </span></span></p>
<p><span style={{fontSize: "14pt"}}>Step 5:<span style={{fontWeight: 400}}> Once these requirements are in place, you can start the installation process. </span></span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p dir="ltr"><span style={{fontSize: "18pt"}}><strong><span style={{fontFamily: "georgia, palatino", color: "#000000"}}>Standard WordPress Installation on cPanel</span></strong></span></p>
<p><span style={{fontSize: "large"}}>Installing WordPress on cPanel is straightforward, thanks to auto-installers like Softaculous. These tools automate the process, making it user-friendly even for beginners. Here's how to do it:</span></p>
<p dir="ltr"> </p>
<p><span style={{fontSize: "14pt"}}> 1:<span style={{fontWeight: 400}}>Log into Your cPanel Account: Your hosting provider will provide you with a link to access your cPanel (eg. http://yourdomain.com/cpanel). Log in to your account by entering your username and password. </span></span></p>
<p><span style={{fontSize: "14pt"}}> 2:<span style={{fontWeight: 400}}>  Locate the WordPress Installer: Scroll down to the 'Software' or 'Softaculous Apps Installer' section in your cPanel dashboard. Click on the WordPress icon.</span></span></p>
<p><span style={{fontSize: "14pt"}}> 3:<span style={{fontWeight: 400}}>  Start the Installation Process: Click on the 'Install Now' button. This will open the following WordPress installation wizard.</span></span></p>
<p><span style={{fontSize: "14pt"}}> 4:<span style={{fontWeight: 400}}>  Fill in the Details: </span></span></p>

<span style={{lineHeight: "28px"}}>Choose the domain where you want to install WordPress.</span>
<span style={{lineHeight: "28px"}}>You can leave the directory field blank to install WordPress in the root directory. If you wish to install it in a subfolder, specify the folder name (e.g., www.yourdomain.com/blog).</span>
<span style={{flineHeight: "28px"}}>It is incredibly extensible with Plugins</span>
<span style={{lineHeight: "28px"}}>Create an admin username, password, and email. This should go without saying but ensure you have a strong password for security. </span>

<p><span style={{fontSize: "14pt"}}> 5:<span style={{fontWeight: 400}}>Advanced Options (Optional): You have the option to configure the database name, table prefix, and backup options if you need them. If you’re a beginner, I suggest using the default settings. </span></span></p>
<p><span style={{fontSize: "14pt"}}> 6:<span style={{fontWeight: 400}}>Install: Click on the 'Install' button. The installer will run and set up WordPress on your cPanel. You’ll get a confirmation screen with your website’s URL and admin login URL once it is successfully installed. </span> </span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p dir="ltr"><span style={{fontSize: "18pt"}}><strong><span style={{fontFamily: "georgia, palatino", color: "#000000"}}>Manual WordPress Installation in cPanel</span></strong></span></p>
<p><span style={{fontSize: "large"}}>Installing WordPress using Softaculous was pretty easy, right? But sometimes, you might need to install WordPress manually, especially if your hosting provider doesn’t support an auto-installer. Follow the following steps to install WordPress in cPanel manually. </span></p>
<p dir="ltr"> </p>
<p><span style={{fontSize: "14pt"}}> 1:<span style={{fontWeight: 400}}>Download WordPress: Download the latest version of WordPress from their official website (wordpress.org). </span></span></p>
<p><span style={{fontSize: "14pt"}}> 2:<span style={{fontWeight: 400}}>Upload WordPress to Your Hosting Account: </span></span></p>

<span style={{lineHeight: "28px"}}>Log into your cPanel account.</span>
<span style={{lineHeight: "28px"}}>Go to the 'File Manager' and open the public_html directory or the folder where you want to install WordPress.</span>
<span style={{flineHeight: "28px"}}>Upload the WordPress.zip file you downloaded and then extract it. If you extracted it into a folder, move the files to the public_html director or any installation directory depending on your needs. </span>

<p><span style={{fontSize: "14pt"}}> 3:<span style={{fontWeight: 400}}>Create a MySQL Database and User: </span></span></p>

<span style={{lineHeight: "28px"}}>In cPanel, go to the 'MySQL Databases' section.</span>
<span style={{lineHeight: "28px"}}>Create a new database for WordPress.</span>
<span style={{flineHeight: "28px"}}>Create a new MySQL user and assign it to the database with full privileges. </span>

<p><span style={{fontSize: "14pt"}}> 4:<span style={{fontWeight: 400}}>  Install WordPress.</span></span></p>

<span style={{lineHeight: "28px"}}>Open a new browser tab and go to your domain (e.g., yourdomain.com).</span>
<span style={{lineHeight: "28px"}}>You'll be greeted with the WordPress installation setup. Select your language and click 'Continue'.</span>
<span style={{flineHeight: "28px"}}>Enter the database details (database name, username, password) you created earlier.</span>
<span style={{lineHeight: "28px"}}>Click 'Submit', and then 'Run the installation'.</span>
<span style={{flineHeight: "28px"}}>Fill in the necessary site information (site title, admin username, password, email) and complete the installation. </span>

<p><span style={{fontSize: "14pt"}}> 5:<span style={{fontWeight: 400}}>Complete the Installation:</span></span></p>

<span style={{lineHeight: "28px"}}>Once you have filled in all the details, click 'Install WordPress'.</span>
<span style={{lineHeight: "28px"}}>After the installation is complete, you will receive a success message with a link to log into your WordPress dashboard.</span>
<span style={{lineHeight: "28px"}}>While manual installation is a bit complicated compared to automatic installation, it offers a lot more control over the installation process. It’s also a great opportunity to learn and understand how WordPress works behind the scenes.</span>

<p><span style={{fontWeight: 400, fontSize: "14pt"}}><strong>Step 2:</strong> Open the File manager &gt;&gt; and upload the file from your Local Computer.</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>If you are going to install WordPress For the Primary Domain Name then you need to Upload your File In the default directory “public_html”</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}><strong>Step 3:</strong> Click on the Upload &gt;&gt; select the file which has to be uploaded &gt;&gt; After Once upload you need to Extract the File in the File Manager.</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}>Method 2:<span style={{fontWeight: 400}}>  Upload the Wordpress.zip file in your File manager Using FTP.</span></span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>You can connect your Hosting account Directory using the FTP. </span></p>
<p><span style={{fontSize: "14pt"}}>The required  FTP Details</span></p>
<p><span style={{fontSize: "14pt"}}>Host:<span style={{fontWeight: 400}}> server ip(You can refer the server details, in your welcome email)</span></span></p>
<p><span style={{fontSize: "14pt"}}>User:<span style={{fontWeight: 400}}> MyUserName</span></span></p>
<p><span style={{fontSize: "14pt"}}>Pass:<span style={{fontWeight: 400}}> MyPass</span></span></p>
<p><span style={{fontSize: "14pt"}}>Port:<span style={{fontWeight: 400}}> 21 By default the Port number will be 21, Some case if you are using SFTP the port will be 22.</span></span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}> You can use the Filezilla tool to connect your hosting account using the FTP, you can refer the Below screen</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}> </span></p>
<p dir="ltr"> </p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Now the file is Uploaded into the File manager.</span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}>Step 3:<span style={{fontWeight: 400}}>  After the file is uploaded in file manager &gt;&gt;  Extract the Wordpress.zip file from File Manager. To extract the file follow the below steps :</span></span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}> Step 3.1: Go to file manager &gt;&gt; to public_html or the directory where you have uploaded the wordpress.zip file, &gt;&gt; right-click on the folder  </span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}> Step 3.2: Select and click-on Extract from the menu as shown in the above figure.</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p> </p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 3.3: after you click on extract &gt;&gt; you need to enter the directory to which the files should be extracted &gt;&gt;  and click on extract files to extract the files &gt;&gt; Once you click in the Extract File it will be extracted as below &gt;&gt; click on close and proceed to the next step</span></p>
<p> </p>
<p><span style={{fontSize: "14pt"}}>Step 4: <span style={{fontWeight: 400}}>Now we have Extracted the File Successfully, But if you check the Screen the File will be extracted in public_html/WordPress. So You have to access the website by http://domain.in/wordpress.</span></span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>To move the files from  the Wordpress to the domain_name directory /public_html, Follow the below steps:</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}> Step 4.1: To Move the Files From Wordpress Directory to Public_html which is parent Directory., You need to Select all the Files from the public_html/WordPress and click on Move as shown below</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 4.2: After you click on move files, select the path &gt;&gt; So that the Wordpress Files will move. You need to enter the Parent Directory “Public_html” if its a primary domain &gt;&gt; and click on move files.Now we have Successfully moved the File to the Parent Directory.</span></p>
<p> </p>
<p><span style={{fontSize: "14pt"}}>Step 5:<span style={{fontWeight: 400}}> Next, Create a Database and its User. </span></span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>To Install the Wordpress Website You need a Database So now we will Create the Database and Database User.</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 5.1: Login to the Cpanel ===&gt; Mysql Databases</span></p>
<p> </p>
<p><span style={{fontSize: "14pt"}}></span></p>
<p><br /><br /></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 5.2: You can enter the Databases name as you wish you can give any or project name.You can refer the below screen.</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 5.3: Once creating a Database now you need to create Database User.</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p dir="ltr"> </p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>You can also generate the password using the password generator.</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p dir="ltr"> </p>
<p> </p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 5.4: Now the Database and its User is created, the next thing to connect Database with its username, You can refer the below screen and add the database</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p dir="ltr"> </p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 5.5: We are adding the database and its username for assigning the Privileges to DB.</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p dir="ltr"> </p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Now we have done with creating the Database and its username and assigned Necessary privileges for the DB.</span></p>
<p><span style={{fontSize: "14pt"}}>Step 6: The last step is to configure this wp-config file in File manager.</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 6.1: Open the File manager  &gt;&gt; Edit the Wp-config.php file.</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>You may not find the file wp-config.php so you need to Rename the file wp-config-sample.php to wp-config.php as shown in the below screen.</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 6.2: Rename the File to wp-config.php</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 6.3: After Renaming it, you need to edit the file wp-config.php &gt;&gt;Click on Edit</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}>Click on Edit</span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 6.4: Now you need to do the Changes in your wp-config file.</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 6.5: You can replace the Values with your Database details and click on save.</span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}>Now the Setup is done, you can access the domain name you will see the below screen.</span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}><strong>Step 7:</strong> Install the Wordpress in Domain name</span></p>
<p><span style={{fontSize: "14pt"}}><strong>URL:</strong> http://domainname/wp-admin/install.php</span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}>Step 7.1: <span style={{fontWeight: 400}}>Click on continue and follow the next steps. Enter all the details and click on the install WordPress will be installed.</span></span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}>Step 7.2: <span style={{fontWeight: 400}}>WordPress is successfully installed.`</span></span></p>
<p> </p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}><br /><br /></span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Following the above steps, you can manually install WordPress for your domain </span></p>
<p id="install-wordpress-using-softaculous"><span style={{fontWeight: 400, fontSize: "14pt"}}>You can also easily install WordPress using softaculous Apps installer. Refer to the below steps to install WordPress for domain </span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}>Steps to install WordPress on cPanel by using one-click installer 'Softaculous apps installer’ :</span></p>
<p> </p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Step 1: Login into your </span>cPanel<span style={{fontWeight: 400}}>.</span></span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Step 2: On the </span>Software<span style={{fontWeight: 400}}> Section &gt;&gt; Select </span>Softaculous App Installer<span style={{fontWeight: 400}}>.</span></span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}> </span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}></span></p>
<p dir="ltr"> </p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Step 3: Click on the </span>WordPress<span style={{fontWeight: 400}}> icon, this will open several options like features, overview, and steps to </span>install<span style={{fontWeight: 400}}> WordPress.</span></span></p>
<p> </p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}></span></p>
<p> </p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Step 4: The brief overview, features are given about WordPress.  Click on </span>Install<span style={{fontWeight: 400}}> to get the details of WordPress installation.</span></span></p>
<p> </p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}></span></p>
<p> </p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 5: Complete the WordPress setup information. The below necessary required information you need to be filled.</span></p>
<p><span style={{fontSize: "14pt"}}>Choose Protocol:<span style={{fontWeight: 400}}> If your website has installed </span><span style={{fontWeight: 400}}>SSL certificate</span><span style={{fontWeight: 400}}>, then choose 'HTTPS', if not choose 'HTTP' protocol.</span></span></p>
<p><span style={{fontSize: "14pt"}}>Choose Domain:<span style={{fontWeight: 400}}> If your hosting panel has multiple domains, then choose the name of the domain which you would like to install WordPress.</span></span></p>
<p><span style={{fontSize: "14pt"}}>In Directory:<span style={{fontWeight: 400}}> Leave a blank column, so that WordPress will be installed directly on your domain.</span></span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>If you're installing sub-folder like 'wp', then your website will not load directly. This will make your website load with folder name like "example.com/wp"</span></p>
<p><span style={{fontSize: "14pt"}}>Admin Username:<span style={{fontWeight: 400}}> Enter a Username of your WordPress Dashboard.</span></span></p>
<p><span style={{fontSize: "14pt"}}>Admin Password:<span style={{fontWeight: 400}}> Enter a Password of your WordPress Dashboard login.</span></span></p>
<p><span style={{fontSize: "14pt"}}>Admin Email:<span style={{fontWeight: 400}}> Enter a valid email address.</span></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Step 6: Once all the information filled, click on the install button to </span>install<span style={{fontWeight: 400}}> WordPress. The WordPress installation may take 1-2 min of time. Please be patient until WordPress installation completes.</span></span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 7: Once WordPress installed, it will show WordPress admin login credentials with the dashboard URL.</span></p>
<p> </p>
<p><span style={{fontSize: "14pt"}}></span></p>
<p> </p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Step 8: Visit your </span>website<span style={{fontWeight: 400}}> on the </span>browser<span style={{fontWeight: 400}}>. Your website will show the </span>WordPress<span style={{fontWeight: 400}}> default page.</span></span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Following the above step, you can easily install WordPress using the softaculous apps installer</span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}>How to Uninstall the existing WordPress Website:</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>If you want to uninstall your existing WordPress website which is already installed, you can uninstall it using the below steps.</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 1: In WordPress panel &gt;&gt; the installed WordPress apps will be shown like below image</span></p>
<p> </p>
<p><span style={{fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 2: Click the delete icon (the red - Xicon )</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 3: Then your app will be uninstalled.</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}> Following the above, you can uninstall Wordpress app.</span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>If you need any assistance in this regard, you can contact us at https://support.hostingraja.in/</span></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Get the dedicated server</span><span style={{fontWeight: 400}}> hosting in india</span><span style={{fontWeight: 400}}> offers only here</span></span></p>
<p> </p> </div>

<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 

<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 

</div>