<h1>Investigate Suspicious File Hash using VirusTotal Website</h1>


<h2>Project description</h2>
For this project, I acted as a Cybersecurity Analyst on a security team for an organization. One of my job roles involved investigating suspicious files.<br/><br/>

There was a file discovered that was attached to an email an employee received in their inbox. Shortly after the reception of the email, an alert was sent to the SOC (System Operations Center) by the IDS (Intrusion Detection System) stating that multiple unauthorized executable files were detected on the employee's computer.<br/><br/>

The following is a timeline of the events leading up to this alert:

1:11 p.m.: An employee receives an email containing a file attachment.

1:13 p.m.: The employee successfully downloads and opens the file.

1:15 p.m.: Multiple unauthorized executable files are created on the employee's computer.

1:20 p.m.: An intrusion detection system detects the executable files and sends out an alert to the SOC.<br/><br/>

<h2>Creating SHA256 Hash of File</h2>
Transferred a copy of the file securely to an isolated Linux virtual machine. Ran the sha256sum command on the file. Noted the SHA256 file hash.<br/><br/>

SHA256 file hash: 54e6ea47eb04634d3e87fd7787e2136ccfbcc80ade34f246a12cf93bab527f6b</br></br>
                                                
<p align="center">
<img src="https://i.imgur.com/o1Djike.png" height="80%" width="80%" alt="Creating SHA256 Hash of File"/>
<br />
<br />
</p>

<h2>Used VirusTotal Website to Investigate File Hash</h2>
Pasted the hash value in the search box of the VirusTotal website.</br></br>
                                                
<p align="center">
<img src="https://i.imgur.com/Fc97h0B.png" height="80%" width="80%" alt="Used VirusTotal Website to Investigate File Hash"/>
<br />
<br />
</p>

<h2>VirusTotal Website Results</h2>
The following image is the results I retrieved from the VirusTotal website from the hash. By these results, it was found that 61/73 security vendors flagged this file as malicious. The popular threat label is "trojan.flagpro/fragtor" which means it is a trojan from the fragtor/flagpro family.</br></br>
                                                
<p align="center">
<img src="https://i.imgur.com/E4OBbTc.png" height="80%" width="80%" alt="VirusTotal Website Results"/>
<br />
<br />
</p>

<h2>Summary</h2>

In this excerise, I demonstrated the use of hashing and investigating suspicious files as a Cybersecurity Analyst. This example displayed how effective crowdsourcing is by the VirusTotal results.
