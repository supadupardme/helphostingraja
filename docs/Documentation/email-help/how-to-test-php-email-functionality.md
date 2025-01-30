---
title: How to test PHP email functionality
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
<div class="hostingraja-forum-article">
<h2>How to test PHP email functionality</h2>
<div class="hostingraja-forum-article-inner-div">
<div class="hostingraja-forum-article-contents">
<div class="hostingraja-forum-article-content">You can test PHP SMTP functions with the following two examples.</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"><strong>1. Normally PHP mail function without any authentication:</strong></div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">
<div class="copy-clipboard"><button class="copy-clipboard-button">Copy</button>
<pre>&lt;?php<br/><br/>$from = "<span id="cloak9605dba49851aca41214d9700f1d953e">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="b05886868342b7cd1b81a0eb-text/javascript">
				document.getElementById('cloak9605dba49851aca41214d9700f1d953e').innerHTML = '';
				var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
				var path = 'hr' + 'ef' + '=';
				var addy9605dba49851aca41214d9700f1d953e = 's&#117;pp&#111;rt' + '&#64;';
				addy9605dba49851aca41214d9700f1d953e = addy9605dba49851aca41214d9700f1d953e + 'h&#111;st&#105;ngr&#97;j&#97;' + '&#46;' + '&#105;n';
				var addy_text9605dba49851aca41214d9700f1d953e = 's&#117;pp&#111;rt' + '&#64;' + 'h&#111;st&#105;ngr&#97;j&#97;' + '&#46;' + '&#105;n';document.getElementById('cloak9605dba49851aca41214d9700f1d953e').innerHTML += '<a ' + path + '\'' + prefix + ':' + addy9605dba49851aca41214d9700f1d953e + '\'>'+addy_text9605dba49851aca41214d9700f1d953e+'<\/a>';
		</script>";<br/>$mail_result ="Mail failed";<br/>$headers = "MIME-Version: 1.0" . "\r\n";<br/>$headers .= "Content-type:text/html;charset=iso-8859-1" . "\r\n";<br/>$headers .= 'From: ' . $from . "\r\n";<br/>$headers .= 'Reply-To: ' .$from . "\r\n";<br/>$headers .= 'X-Mailer: PHP/' . phpversion();<br/>$to = "<span id="cloake93b89ac2e63dfaca393893a4d85637f">This email address is being protected from spambots. You need JavaScript enabled to view it.</span><script type="b05886868342b7cd1b81a0eb-text/javascript">
				document.getElementById('cloake93b89ac2e63dfaca393893a4d85637f').innerHTML = '';
				var prefix = '&#109;a' + 'i&#108;' + '&#116;o';
				var path = 'hr' + 'ef' + '=';
				var addye93b89ac2e63dfaca393893a4d85637f = '&#111;v&#105;h&#111;st&#105;ng' + '&#64;';
				addye93b89ac2e63dfaca393893a4d85637f = addye93b89ac2e63dfaca393893a4d85637f + 'gm&#97;&#105;l' + '&#46;' + 'c&#111;m';
				var addy_texte93b89ac2e63dfaca393893a4d85637f = '&#111;v&#105;h&#111;st&#105;ng' + '&#64;' + 'gm&#97;&#105;l' + '&#46;' + 'c&#111;m';document.getElementById('cloake93b89ac2e63dfaca393893a4d85637f').innerHTML += '<a ' + path + '\'' + prefix + ':' + addye93b89ac2e63dfaca393893a4d85637f + '\'>'+addy_texte93b89ac2e63dfaca393893a4d85637f+'<\/a>';
		</script>";<br/>$subject = "Mail sending from files";<br/><br/>if (mail($to,$subject,$body,$headers))<br/>echo "mail sent" ;<br/>else<br/>echo "mail not sent" ;<br/><br/>?&gt;&lt;
</pre>
</div>
</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"><strong>2. SMTP PHP mailer function with authentication email id and password:</strong> </div>
<div class="hostingraja-forum-article-content"><br/>We strongly recommend using an SMTP relay that requires authentication. Sending mail through unauthenticated SMTP servers (including the localhost relay on Cloud Sites) can result in delays or undelivered email due to stringent anti-spam filters.</div>
<div class="hostingraja-forum-article-content"><br/>Download the below links,<br/><br/><a href="https://support.hostingraja.in/PHPMailer_5.2.0.zip" target="_blank" rel="noopener noreferrer">https://support.hostingraja.in/PHPMailer_5.2.0.zip</a><br/><br/>and unzip the PHPMailer_5.2.0.zip file, Then provide the proper mail details in Sendingmail.php file.<br/><br/></div>
<div class="hostingraja-forum-article-content">PHPMailer_5.2.0/Sendingmail.php</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">&lt;?php</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">$hostname = "mail.domainname";</div>
<div class="hostingraja-forum-article-content">$SendingEmail = "Your_Email_ID";</div>
<div class="hostingraja-forum-article-content">$SendingPwd = "Your_secret_Email_Password";</div>
<div class="hostingraja-forum-article-content">$To = "To_address";</div>
<div class="hostingraja-forum-article-content">$Subject = "Subject";</div>
<div class="hostingraja-forum-article-content">$body = "Body";</div>
<div class="hostingraja-forum-article-content">$port = "465";</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">
<pre>require("class.phpmailer.php");<br/><br/>$mail = new PHPMailer();<br/><br/>$mail-&gt;IsSMTP(); // set mailer to use SMTP<br/>$mail-&gt;Host = $hostname; // specify main and backup server<br/>$mail-&gt;SMTPAuth = true; // turn on SMTP authentication<br/>$mail-&gt;Username = $SendingEmail; // SMTP username<br/>$mail-&gt;Password = $SendingPwd; // SMTP password<br/>$mail-&gt;Port = $port;<br/>$mail-&gt;SMTPDebug = 2;<br/>$mail-&gt;From = $SendingEmail;<br/>$mail-&gt;FromName = "support";<br/>$mail-&gt;AddAddress($To,$Name);<br/>$mail-&gt;SMTPSecure = "tls";<br/>$mail-&gt;AddAddress($To,$Name);<br/>$mail-&gt;WordWrap = 50; // set word wrap to 50 characters<br/>$mail-&gt;IsHTML(false); // set email format to HTML<br/>$mail-&gt;Subject = $Subject;<br/>$mail-&gt;Body = $Body;<br/><br/>if(!$mail-&gt;Send())<br/>{<br/>echo "Message could not be sent.";<br/>echo "Mailer Error: " . $mail-&gt;ErrorInfo;<br/>exit;<br/>}<br/><br/>echo "Message has been sent $To from $SendingEmail \n";</pre>
</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">?&gt;</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"><strong>Hostname in SMTP mail function:</strong></div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">You are connecting your domain,  just give the mail.domain otherwise your are configuring any other email.</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">For example, take as Gmail account  </div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"><strong>$hostname = "ssl://smtp.gmail.com";</strong></div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">$mail-&gt;Host = $hostname; // specify main and backup server</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"><strong>Port number in SMTP mail function:</strong></div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">Without an SSL connection, </div>
<div class="hostingraja-forum-article-content">
<p>SMTP server port for outgoing: 25 / 587</p>
<div class="hostingraja-forum-article-content">With an SSL connection, </div>
<div class="hostingraja-forum-article-content">
<p>SMTP server port for outgoing: 465 </p>
</div>
</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">$port = "465";</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"><strong>$mail-&gt;Port = $port;</strong></div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"><strong>HTML or NON-HTML in SMTP mail function:</strong></div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">If you send mail with HTML or without HTML check once, If you're sending normal text mail. But in SMTP configuration your enabling the IsHTML is tue. The mail will reached to spam folder. </div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"><strong>$mail-&gt;IsHTML(false);</strong> // set email format to HTML</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">So make sure you send mail with HTML tag or NOT.</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content">Kindly provide the proper login details and check it.</div>
<div class="hostingraja-forum-article-content"> </div>
<div class="hostingraja-forum-article-content"><span style="font-weight: bold;">Note</span>: Mail.php is a PEAR module and is installed on the server. It is included in the default include_path for PHP, so requiring it here will work by default without any additional effort on your part.</div>
<div class="hostingraja-forum-article-content"> </div>
</div>
</div>
</div> </div>
</div>