<h1>Investigate Suspicious File Hash using VirusTotal Website</h1>


<h2>Project description</h2>
For this project, I acted as a Cybersecurity Analyst on a security team for an organization. One of my job roles involved investigating a file that was attached to an email that a user received in their inbox. Shortly after the reception of the email, an alert was sent to the SOC (System Operations Center) by the intrusion detection system stating that multiple unauthorized excecutable files were detected on the employee's computer. <br/><br/>

Here is a timeline of the events leading up to this alert:

1:11 p.m.: An employee receives an email containing a file attachment.

1:13 p.m.: The employee successfully downloads and opens the file.

1:15 p.m.: Multiple unauthorized executable files are created on the employee's computer.

1:20 p.m.: An intrusion detection system detects the executable files and sends out an alert to the SOC.<br/><br/>

<h2>Creating SHA256 Hash of File</h2>
Transferred a copy of the file securely to an isolated Linux virtual machine. Ran the sha256sum command on the file. Noted the SHA256 file hash.<br/><br/>

SHA256 file hash: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b</br></br>
                                                
<p align="center">
<img src="https://i.imgur.com/o1Djike.png" height="80%" width="80%" alt="Open the file that contains the allow list"/>
<br />
<br />
</p>

<h2>Used VirusTotal Website to Investigate File Hash</h2>
Then I right-clicked on the "Command Prompt" result and selected "Run as administrator."</br></br>
                                                
<p align="center">
<img src="https://i.imgur.com/Fc97h0B.png" height="80%" width="80%" alt="Open the file that contains the allow list"/>
<br />
<br />
</p>

<h2>Command Prompt</h2>
The Command Prompt opened.</br></br>
                                                
<p align="center">
<img src="https://i.imgur.com/E4OBbTc.png" height="80%" width="80%" alt="Open the file that contains the allow list"/>
<br />
<br />
</p>

<h2>Summary</h2>

In this excerise, I demonstrated the use of diskpart to wipe a drive as a Cybersecurity Analyst. This example displayed how drives can easily be wiped for reuse.
