# ActiveDirectory_Lab_PowerShell
<h1>JWipe - Disk Sanitization</h1>

<h2>Description</h2>
Project Overview:  Drive Sanitization Script

This project involves a straightforward PowerShell script that guides users through the process of securely wiping (zeroing out) any drives connected to the system. The utility is designed to provide a simple, yet effective, way to sanitize disks by giving the user control over the target disk and the number of overwrite passes.

The script allows users to select the drive they wish to target and specify how many overwrite passes they want to perform, enhancing security by making data recovery more difficult. Based on the user’s input, the PowerShell script generates a Diskpart script file tailored to the selected parameters. The script then automatically launches Diskpart, a built-in Windows utility, to carry out the disk sanitization process.

Key Features:
	•	Target Selection: Choose which disk to wipe from the list of connected drives.
	•	Overwrite Passes: Set the number of times the disk will be overwritten, increasing security.
	•	Automation: The script generates and runs a Diskpart script to automate the sanitization process.

Purpose:

This utility is an essential tool for securely wiping drives, especially when preparing them for decommissioning or reusing, where sensitive data must be fully removed to prevent unauthorized recovery.

Learning Goals:
	•	Implementing PowerShell scripting to automate administrative tasks.
	•	Gaining hands-on experience with Diskpart for disk management and sanitization.
	•	Enhancing knowledge of data security by applying multiple overwrite passes to ensure thorough data erasure.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>
- <b>Oracle Virtual box<b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Take a look at the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
