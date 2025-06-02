<h1>FIM(File Integrity Monitor) System </h1>

<h2>Description</h2>
This project demonstrates a basic version of a File Integrity Monitor alerting system using PowerShell. Hashing is the core component of this code, utilizing SHA-512 to compare an original baseline of the file structure to the new hash after a change is made. This can include creating a new file, changing the contents of an existing file, or even deleting a file. A FIM is very important for maintaining the integrity of files or folders and can be highly useful for businesses in the real world.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>File System</b>
- <b>SHA-512 Hash</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>

<h2>Project walk-through:</h2>

<p align="center">
Initial prompt to the user: <br/>
<img src="https://i.imgur.com/UPIiLqQ.jpeg" height="80%" width="80%" alt="FIM"/>
<br />
<br />
Prompted error message after the user selects option "B" when no baseline is currently on file: <br/>
<img src="https://i.imgur.com/Z42e3k7.jpeg" height="80%" width="80%" alt="FIM"/>
<br />
<br />
Another prompt to ask the user if they want to create a baseline; if not, the program will exit: <br/>
<img src="https://i.imgur.com/mHFHXVI.jpeg" height="80%" width="80%" alt="FIM"/>
<br />
<br />
Showing the alert messages for when the contents of a file is created (Green), changed (Yellow), or deleted(Red): <br/>
<img src="https://i.imgur.com/GbTCcfx.jpeg" height="80%" width="80%" alt="FIM"/>
<br />
<br />

</p>
