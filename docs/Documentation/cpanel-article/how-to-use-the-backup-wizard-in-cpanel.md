---
title: How to use the backup wizard in cpanel?
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
    <span style={{fontSize: "xx-large"}}><strong>How to use the backup wizard in cpanel? </strong></span>
    <strong><br /></strong>
    <p dir="ltr"><span style={{fontSize: "x-large"}}><strong>What do you mean by a backup wizard in a cpanel?</strong></span></p>
    <br />
    <p dir="ltr">In a web  hosting cPanel, the Backup wizard is an easy interface for creating and restoring backups. The backup will be done for the complete website or for the part of the website.</p>
        Likewise, the backup files will be restored. The backup files will be downloaded to the local machine or transferred to a remote server through FTP. The Backup wizard will be found beneath the Files section of the cPanel. This feature will be
        very helpful for taking local backups during the time of server migration.</p>
    <br />
    <p dir="ltr">If you make use of our cPanel for your hosting services. Then the cPanel will offer a very simple and powerful tool for creating and restoring the backups in a panel. cPanel hosting        plan provides the good features for the user with which the user will be able to make changes or perform numerous operations related to the server or the website hosted on it.</p>
    <br />
    <p dir="ltr"><span style={{fontSize: "x-large"}}><strong>Steps to use the backup wizard in cpanel:</strong></span></p>
    <br />
    <p dir="ltr"><strong>Step-1:</strong> Login to cpanel</p>
    <p dir="ltr"><strong>Step-2:</strong> Select Backup Wizard from Files section</p>
    <br />
    <p dir="ltr"></p>
    <br />
    <p dir="ltr"><strong>Step-3:</strong> Click on the Back up button</p>
    <br />
    <p dir="ltr"></p>
    <br />
    <p dir="ltr"><strong>Step-4:</strong> Click on the Full backup</p>
    <br />
    <p dir="ltr"></p>
    <br />
    <p>Step 5:<span style={{fontWeight: 400}}> After you click on full backup &gt;&gt; Choose where you want to save your backup and you can also add email to notify when the backup is complete</span></p>
    <p><span style={{fontWeight: 400}}>The option for saving your backup</span></p>
    <p><span style={{fontWeight: 400}}>Home Directory:  The backup file will be saved on the server.</span></p>
    <p><span style={{fontWeight: 400}}>Remote FTP Server: the backup file will be stored on a remote server using FTP </span></p>
    <p><span style={{fontWeight: 400}}>Remote FTP Server (passive mode transfer): the backup file will be stored on a remote server using passive FTP</span></p>
    <p><span style={{fontWeight: 400}}>Secure Copy (SCP): The backup file will be stored on a remote server using SCP</span></p>
    <p>Important:<span style={{fontWeight: 400}}> The Remote FTP Server, Remote FTP Server (passive mode transfer), or SCP destination options can only be selected by advanced users.and when these options are selected you need to enter information on remote servers in the checkbox</span></p>
    <p><span style={{fontWeight: 400}}>If you need to be notified when the backup process is completed then you need to enter your email address in the text box and </span><span style={{fontWeight: 400}}>to disable notifications, select the checkbox  Do not send email notification of backup completion</span></p>
    <br />
    <p dir="ltr"></p>
    <br />
    <p dir="ltr"><strong>Step-6:</strong> Add click on the Generate Backup button</p>
    <br />
    <p dir="ltr"></p>
    <br />
    <p dir="ltr"><strong>Step-7:</strong> Your backup will be under progress and will look like the below screenshot</p>
    <br />
    <p dir="ltr"></p>
    <br />
    <p>Step 8:<span style={{fontWeight: 400}}> As soon as your backup completes it will look like the below screenshot and you can download the backup by clicking on it.</span></p>
    <p><span style={{fontWeight: 400}}>The backup file's creation date appears in the filename, which begins with a backup-MM-DD-YYYY string, where MM represents the month, DD represents the date, and YYYY represents the year and the system stores full backup files as tarballs that use the .tar.gz file extension.</span></p>
    <br />
    <p dir="ltr"></p>
    <br />
    <p><span style={{fontWeight: 400}}>Following the above steps, you can take backup using the backup wizard in your cpanel </span></p>
    <p> </p>
    <p>Steps to take a partial backup</p>
    <p dir="ltr"> </p>
    <p><span style={{fontWeight: 400}}>Step 1: Login cpanel &gt;&gt; backup wizard &gt;&gt;click on  backup</span></p>
    <p><span style={{fontWeight: 400}}>Step 2: under partial backup select the backup which is needed </span></p>
    <p>Home directory: <span style={{fontWeight: 400}}>To restore the /home directory</span></p>
    <p>MySQL databases: <span style={{fontWeight: 400}}>To restore databases </span></p>
    <p>Email Forwarders  Filters:<span style={{fontWeight: 400}}> to restore mail forwarders or filters.</span></p>
    <p><span style={{fontWeight: 400}}>Step 3: The Download section of the interface will appear &gt;&gt; Click the desired backup file to download it.</span></p>
    <p>Note:</p>
    <p><span style={{fontWeight: 400}}>When you create a partial backup, the backup type determines the backup file's extension.</span></p>
    <p><span style={{fontWeight: 400}}>The backup file's extension depends on the portion of your site that you backed up.</span></p>
    <p><span style={{fontWeight: 400}}>For Home directory-  *tar.gz</span></p>
    <p><span style={{fontWeight: 400}}>MySQL databases: *.sql</span></p>
    <p><span style={{fontWeight: 400}}>Email Forwarders &amp; Filters:  *.net, *.com </span></p>
    <p><span style={{fontWeight: 400}}>When you back up your home directory, all of the files that you own and files that you do not own, but to which you possess access, will also be taken back up.</span></p>
    <p> </p>
    <p>Steps to restore files using the backup wizard:</p>
    <p><span style={{fontWeight: 400}}>You can also Restore files using the backup wizard, to restore a file or folder from an existing backup, follow the below steps:</span></p>
    <p><span style={{fontWeight: 400}}>Step 1: In </span><span style={{fontWeight: 400}}>cPanel &gt;&gt; Backup Wizard</span><span style={{fontWeight: 400}}>  &gt;&gt; click on Restore<br /><br /><br /> </span></p>
    <p><br />Step 2:<span style={{fontWeight: 400}}>Select the type of file or directory which should be restored :</span></p>
    <p>Home directory: <span style={{fontWeight: 400}}>To restore the /home directory</span></p>
    <p>MySQL databases: <span style={{fontWeight: 400}}>To restore databases </span></p>
    <p>Email Forwarders &amp; Filters configuration:<span style={{fontWeight: 400}}> to restore mail forwarders or filters configuration </span></p>
    <p>Step 3:<span style={{fontWeight: 400}}> In restore interface section &gt;&gt; select the file which should be uploaded </span></p>
    <p>Step 4:<span style={{fontWeight: 400}}> And click on upload to restore the backup. </span></p>
    <p> </p>
    <p>Important things to consider before you start your backup</p>
    <p><span style={{fontWeight: 400}}>1) Ensure to check the disk availability before you start the backup process. When you don't have enough disk space left, then the backup process will break in-between and also, your website will stop working. Assume you have used the disk space of around 1GB, then ensure that at least 55% of them is available for backup.</span></p>
    <p><span style={{fontWeight: 400}}>2) Verify the remaining amount of inode limit. If you don't have enough inode count, then also backup can break.</span></p>
    <p><span style={{fontWeight: 400}}>3) ANOTHER IMPORTANT POING TO CONSIDER WHEN TAKING A BACKUP IN CPANEL IS, do not take backup again &amp; again without deleting your old backup. Once you take the backup, ensure to download to your local system. If you don't delete the old backups before taking the new backup, then your backup size will keep increasing, it will affect your disk quota and also website functionality. Make sure to always keep one copy of the backup in the server.</span></p>
    <p>Note<span style={{fontWeight: 400}}>:</span></p>
    <p><span style={{fontWeight: 400}}>&gt;&gt; You </span>must <span style={{fontWeight: 400}}>download and compress the backup file prior to restoration. </span></p>
    <p><span style={{fontWeight: 400}}>&gt;&gt; After you decompress the backup file, you can upload and restore individual portions of your website that the full backup file contains.</span></p>
    <p><span style={{fontWeight: 400}}>&gt;&gt;The backup process for an account near or over its quota may fail because the system cannot write necessary files, such as a database lock file.</span></p>
    <p><span style={{fontWeight: 400}}>If you are facing any issue or if you have any clarification, feel free to contact our support team via live chat, email, toll-free or ticket system and our support team is available 24/7.<br /><br /><br /></span></p>
</div>

    
        
            <span class="icon-chevron-left" aria-hidden="true"></span> <span aria-hidden="true">Prev</span> 
    
    
        
            <span aria-hidden="true">Next</span> <span class="icon-chevron-right" aria-hidden="true"></span> 
    

</div>