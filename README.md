<h2>Verifying File Integrity using SHA256 Checksums</h2>
<h1>Project Description</h1>
In this tutorial, I will show you how to verify the integrity of a file using a provided checksum. Integrity safeguards against unauthorized modifications, alterations, or deletions of data. By maintaining integrity, organizations can have confidence in the accuracy and consistency of their data, which is essential for making informed decisions, ensuring compliance with regulations, and maintaining trust with stakeholders.

<h1>Tools Used</h1>

- PowerShell
- SHA256 Hash Checksum
- Oracle VirtualBox exe

<h1>Download VirtualBox for Windows Hosts from the Official Site</h1>

![0](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/0.png)

<h1>Open the SHA256 checksums link provided by Oracle.</h1>

![1](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/1.png)

<p>This page will contain the SHA256 checksums for each file you can download. We are only interested in the Windows version.</p>

![2](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/2.png)

<h1>Open your Downloads Folder and open PowerShell</h1>

![3](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/3.png)

<p>You can also open Powershell normally instead and manually navigate to this directory using cd.</p>

![4](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/4.png)

<h1>Get the File Hash of the File you Downloaded</h1>

![5](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/5.png)

<p>Make sure you are in the right directory, then use Get-Filehash on the downloaded file</p>

![6](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/6.png)

<p>If you are on windows, you can use Ctrl-C to copy the file hash to make the next step easier.</p>

<h1>Compare the Hashes</h1>

<p>Use the find function in your browser, then enter the file hash you got from PowerShell</p>

![7](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/7.png)

<p>If it matches like it did here, then you have successfully verified the integrity of your file!</p>
