---
title: Changing File Permissions in cPanel
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
<span style={{fontSize: "14pt"}}><strong>Changing File Permissions in cPanel</strong></span>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Each and every file and folder in </span>cpanel Linux hosting account<span style={{fontWeight: 400}}> has permissions, which command who all can read, write or execute that particular file or folder. When you create the files these permissions will assign automatically. Mostly as a user, you will not need to modify those permissions, although there are few circumstances when any update, setup-installation etc. need a file or folder permissions to need to be changed.</span></span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Here you will be provided with the information to run some form of Linux. Here you will be provided with the information on the basics of file permissions. Here the concept discussed must be applicable to most </span>Linux systems<span style={{fontWeight: 400}}> which includes the Grid and Server.</span></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}></span></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}> Why file permission is important?</span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>The proper type of file permissions is an extremely important part of </span>ensuring that the website is secure.</span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Determining the correct form of file permissions for a specific file requires to know what type of information is contained in the file as well as the purpose of that information. There are some guidelines that need to be followed which reside in a </span>web-accessible location<span style={{fontWeight: 400}}>.</span></span></p>
<p><span style={{fontSize: "14pt"}}>File permissions are based on three categories on a Linux based system in a <strong>web hosting</strong> service:</span></p>

<span style={{fontSize: "14pt"}}>User<span style={{fontWeight: 400}}> - It is a specific account of the hosting system. You can think of it as general as the person who has uploaded or created the file.</span></span>

<span style={{fontSize: "14pt"}}>Group<span style={{fontWeight: 400}}> - It refers to the specific selection of one or more user. Each user belongs to a default group.</span></span>

<span style={{fontSize: "14pt"}}>Other<span style={{fontWeight: 400}}> - It refers to any other account on the hosting system.</span></span>

<p><span style={{fontSize: "14pt"}}>Here each of these categories can be granted the access in performing the actions on the file:</span></p>

<span style={{fontSize: "14pt"}}>Read<span style={{fontWeight: 400}}> - It is an ability by which one can view the contents of the file or the directory.</span></span>

<span style={{fontSize: "14pt"}}>Write<span style={{fontWeight: 400}}> - It is an ability by which one can change the contents of the file or the directory.</span></span>

<span style={{fontSize: "14pt"}}>Execute<span style={{fontWeight: 400}}> - It is an ability to ask the server for treating the file as a program.</span></span>

<p><span style={{fontSize: "14pt"}}>One should never allow more access to the file that is absolutely necessary.</span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}>What is the required permission for files and folder?</span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>In cpanel, the </span>files should have 644 <span style={{fontWeight: 400}}> permission and </span>folder should have 755 <span style={{fontWeight: 400}}>permission. </span></span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>The users whom the directory or folder belongs to should have write access. Apart from it everyone else must be having the read and execute permissions.therefore the folder permission should be 755</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Documents, videos, images and audio files each of it belongs to the category of static content. Here the extensions of the file can indicate that it is static content. The list of some of the extensions which indicate that the file is a static content are: .html, .htm, jpeg, .jpg, .gif, .png, .css, .js, .mpeg, .mgp, .mp3, .avi, .txt, .doc and .pdf</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Only the users with who the static content file belongs to should be having the write access. Apart from it, everyone else should be having the read permissions. Execute permissions are not harmful but the following rule is least permissive and hence it is not granted the access. hence the file should have 644 permission </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>The scripts or the binaries which run on the server and generate the web pages fall into the category of dynamic content. If WordPress or some other content is being used for blogging then it falls into this category. Some of the extensions indicating the dynamic content are shown below: .php, .php4, .php5, .cgi, .pl, .py and .rb</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>For the user, a dynamic content file belongs to the person who is having the read, write as well as execute permissions. No one else should be having any other permissions. Here the rules of the least permissive are extremely important when it comes to running these types of files as are often containing sensitive information such as a database password. So the file permission for script files will be 700 (only one person permission to read,write, execute)</span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<span style={{fontSize: "14pt"}}>You can change the file permission in SSH using the below commands:</span>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>To change folder permission: </span></p>
<p><span style={{fontSize: "14pt"}}>chmod 755 &lt;folder_name&gt;</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Ex: chmod 755 wp-content</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>To change file  permission: </span></p>
<p><span style={{fontSize: "14pt"}}>chmod 644 &lt;file_name&gt;</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Ex: chmod 644 index.html</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>To change  permission for script files: </span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>:</span>chmod 700 script.php</span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<span style={{fontSize: "14pt"}}>Steps to  Change the file permissions using Cpanel:</span>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 1: Login into C-panel &gt;&gt; go to file manager</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Step 2: You can view the File Permissions in cPanel as shown below. File/folders permissions can be easily viewed or modified through cPanel’s file manager option or from any FTP programs</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}> </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>In the screenshot given above, you can see the permissions of each file and folder in the right-hand side of the screen. One of the most important things you need to remember is that specific files and folders must be set to particular permission. For </span>example<span style={{fontWeight: 400}}>:</span></span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>Folder - 755</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>.html and .php - 644</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>public _html - 755</span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>CGI and Perl scripts - 755</span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Step 3: If the file does not have appropriate permission then you to </span>Change file Permission Setting. <span style={{fontWeight: 400}}>You can change the files and folders permission through the </span> cpanel file manager<span style={{fontWeight: 400}}> option. In the File Manager, go to the file you want to change the permission to &gt;&gt;  hit right click of your mouse in that particular file </span></span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Step 4: choose </span>change permissions<span style={{fontWeight: 400}}> from the menu as shown in the screenshot below:</span></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}></span></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}> Step 5: You can easily </span>change the permission window<span style={{fontWeight: 400}}> where you can easily alter the setting as you want by checking or unchecking the boxes next to the permissions.</span></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}></span></span></p>
<p><span style={{fontSize: "14pt"}}> </span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>Step 6: Once you are done with adjusting permissions, click the </span>Change Permissions button<span style={{fontWeight: 400}}>.</span></span></p>
<p><span style={{fontSize: "14pt"}}>Note : </span></p>
<p><span style={{fontWeight: 400, fontSize: "14pt"}}>You should only change permissions if it is needed and make sure you are not permitting additional access to your valuable files and folders that is essential because doing that can leave your web page unprotected.</span></p>
<p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>If you are looking more information or need additional help related to this, feel free to </span>contact our support team<span style={{fontWeight: 400}}>. </span><span style={{fontWeight: 400}}>you can contact us at </span><span style={{fontWeight: 400}}>http://www.hostingraja.in/support/</span></span></p>
<p dir="ltr"><span style={{fontSize: "14pt"}}> </span></p>
<div id="basics-of-file-permissions-in-linux"><span style={{fontSize: "14pt"}}> </span></div> </div>

<span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 

<span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 

</div>