---
title: How to take backup from one server and move to another server using SSH
excerpt: >-
  Here is the information about How to take backup from one server and move to
  another server using SSH
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
    <span style={{fontSize: "18pt"}}><strong>How to take backup from one server and move to another server using SSH</strong></span>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>The </span>backup is necessary<span style={{fontWeight: 400}}> because when it comes to important information, it’s crucial for businesses to make sure that their data is protected and backed up in the event of an emergency. But unfortunately, today only about 50% of small and medium-sized businesses are confident that their data is being backed up properly. And many times they feel as if they lack with their technical experts or equipment to back up their critical data properly. But the truth is that disaster waits for no one and it can happen at any time and in any form. Even something as harmless as accidentally dropping an important hard drive can throw business into a tailspin. Regardless of the type of disaster that may occur to a business, you as a company may very well experience one. That’s where data backup comes into play. It also recommended taking a backup when you are performing any configuration changes in the server.</span></span></p>
    <p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}> The</span> main purpose of the backup<span style={{fontWeight: 400}}> is to create a copy of data that can be recovered in the event of a primary data failure. Because if there is a failure in the primary failure then it will result in hardware or software failure, data corruption or even human-caused event with malware attack or deleting the data accidentally. By having backup copies it allows data to be restored at any point of time which will help the business to recover from an unplanned event.</span></span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>Moreover storing the copied data on a separate medium is more critical to protect against the primary data loss or corruption. The alternate medium can be in the same location as the primary data or at a remote location. The possibility of weather-related events may justify having copies of data at remote locations. For best results, backup copies are made on a consistent, regular basis to minimize the amount of data lost between backups. The more time passes between backup copies, then the more potential for data loss when recovering from a backup. Retaining multiple copies of data provides the insurance and flexibility to restore to a point in time not affected by data corruption or malicious attacks.</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <span style={{fontSize: "14pt"}}>What is SSH?</span>
    <p><span style={{fontSize: "14pt"}}>Secure Shell which is commonly known as SSH,<span style={{fontWeight: 400}}> it is most commonly used by Linux Hosting server and it is a </span>protocol<span style={{fontWeight: 400}}> that is used to login to the server in a secure way</span></span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>SSH is a more secure network connection when compared to FTP, hence it is recommended to take backup using SSH, and Installing and Managing applications through the command line, using SSH you can very quick Live Edit and save the files, though no need of downloading it to the Local system.</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>Note:</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>In shared hosting, you will be having a restriction for all your access. Hosting providers will set a limit and restriction as per their plans or their terms. And also in few cheap hosting plans you will not get SSH access. </span></p>
    <p><br /><br /></p>
    <span style={{fontSize: "14pt"}}>Steps to log in your server SSH:</span>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}><strong>Step 1</strong>: To log in to your computer from a Unix-like machine, go to a command-line and type:</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}>ssh &lt;username&gt;@&lt;computer name or IP address&gt;</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>Example:</span></p>
    <p><span style={{fontSize: "14pt"}}>ssh root@donamain_name.com (or) ssh <span id="cloak54877589670d2b419f6c823357f826e8">This email address is being protected from spambots. You need JavaScript enabled to view it.</span></p>
                
                    document.getElementById('cloak54877589670d2b419f6c823357f826e8').innerHTML = '';
                    var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
                    var path = 'hr' + 'ef' + '=';
                    var addy54877589670d2b419f6c823357f826e8 = 'r&#111;&#111;t' + '&#64;';
                    addy54877589670d2b419f6c823357f826e8 = addy54877589670d2b419f6c823357f826e8 + '11' + '&#46;' + '12' + '&#46;' + '11' + '&#46;' + '12';
                    var addy_text54877589670d2b419f6c823357f826e8 = 'r&#111;&#111;t' + '&#64;' + '11' + '&#46;' + '12' + '&#46;' + '11' + '&#46;' + '12';document.getElementById('cloak54877589670d2b419f6c823357f826e8').innerHTML += ''+addy_text54877589670d2b419f6c823357f826e8+'';
                
            </span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}><strong>Step 2</strong>: You should get the usual password prompt &gt;&gt; Enter the password to login into SSH </span></p>
    <p><br /><br /></p>
    <span style={{fontSize: "14pt"}}>Step to take backup from one server and move to another server using SSH: </span>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>First, you need </span>to generate backup using SSH<span style={{fontWeight: 400}}> for the server :</span></span></p>
    <p><span style={{fontSize: "14pt"}}>Step 1: <span style={{fontWeight: 400}}>Login to the </span><span style={{fontWeight: 400}}>current server SSH</span><span style={{fontWeight: 400}}> (Putty) from where the backup has to be generated.</span></span></p>
    <p><span style={{fontSize: "14pt"}}> Step 2:<span style={{fontWeight: 400}}> Go to the home directory.</span></span></p>
    <p><span style={{fontSize: "14pt"}}> $ cd /home</span></p>
    <p><span style={{fontSize: "14pt"}}> Step 3:<span style={{fontWeight: 400}}> Enter the below command to generate the backup on the server.</span></span></p>
    <p><span style={{fontSize: "14pt"}}> sudo /scripts/pkgacct Username</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>Where,</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>username should be replaced with the particular domain’s username.</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}> Step 4: <span style={{fontWeight: 400}}>Once the backup is completed, move the backup file to a particular account so that the backup should be downloadable. Enter the below command for moving the backup file to a particular account.</span></span></p>
    <p><span style={{fontSize: "14pt"}}> mv cpmove-$user.tar.gz /home/$user/public_html</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}> Where,</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>$user.tar.gz is the backup file name.</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>$user is the username of the account, where the backup file is being moved.</span></p>
    <p><span style={{fontSize: "14pt"}}>Step 5:<span style={{fontWeight: 400}}> After moving the backup to a particular account, correct the file permission of the backup file. You can set the file permission using the below command:</span></span></p>
    <p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}> </span> chmod 644 cpmove-$user.tar.gz</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}> Where,</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>$user.tar.gz is the backup file name.</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>Example: Go the current path where the backup file is moved. Change the file permission to 644.</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <span style={{fontSize: "14pt"}}>Second, you need to move the backup to another server: </span>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}> Step 6<span style={{fontWeight: 400}}>: Now the backup file can be downloaded &gt;&gt; Login to the New server SSH, where the backup has to be moved.</span></span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>Download the backup file on the new server by running the below command.</span></p>
    <p><span style={{fontSize: "14pt"}}>wget http://$userdomain/cpmove-$user.tar.gz</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}>Where,</span></p>
    <p><span style={{fontWeight: 400, fontSize: "14pt"}}> http://$userdomain/cpmove-$user.tar.gz is the backup file link.</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}>Step 7:<span style={{fontWeight: 400}}> Run the below command for restoring the backup on the new server.</span></span></p>
    <p><span style={{fontSize: "14pt"}}>sudo /scripts/restorepkg backup file name ex: username.tar.gz</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}><span style={{fontWeight: 400}}>If you need any assistance in this regard, you can contact us at </span><span style={{fontWeight: 400}}>http://support.hostingraja.in/</span></span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}>Get the best Windows<strong> VPS Hosting</strong> here</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}><strong>Related Backup taking from other Panel:</strong></span></p>
    <p><span style={{fontSize: "14pt"}}>Refer the below links for Backup taking from other Plesk Panel,</span></p>
    <p><span style={{fontSize: "14pt"}}>https://help.hostingraja.in/other-help/how-to-take-complete-account-backup-and-restore-website-in-plesk</span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
    <p><span style={{fontSize: "14pt"}}> </span></p>
</div>

      <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span>  
      <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span>