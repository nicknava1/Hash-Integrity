<h1>Verifying File Integrity using Checksums</h1>
<h2>Project Description</h2>
In this tutorial, I will show you how to verify the integrity of a file using a provided checksum. Integrity safeguards against unauthorized modifications, alterations, or deletions of data. By maintaining integrity, organizations can have confidence in the accuracy and consistency of their data, which is essential for making informed decisions, ensuring compliance with regulations, and maintaining trust with stakeholders.

<h2>Tools Used</h2>

- PowerShell
- SHA256 Hash Checksum
- Oracle VirtualBox exe

<h2>Download VirtualBox for Windows Hosts from the Official Site</h2>

You can download VirualBox from their Downloads page linked here: [https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)

![0](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/0.png)

<h2>Open the SHA256 checksums link</h2>

![1](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/1.png)

<p>This page will contain the SHA256 checksums for each file you can download. We are only interested in the Windows version.</p>

![2](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/2.png)

<h2>Open your Downloads Folder and open PowerShell</h2>

![3](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/3.png)

![4](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/4.png)

<p>You can also open Powershell normally instead and manually navigate to this directory using cd.</p>

<h2>Get the File Hash of the File you Downloaded</h2>

![5](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/5.png)

<p>Make sure you are in the right directory, then use Get-Filehash on the downloaded file</p>

![6](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/6.png)

<p>If you are on windows, you can use Ctrl-C to copy the file hash to make the next step easier.</p>

<h2>Compare the Hashes</h2>

<p>Use the find function in your browser, then enter the file hash you got from PowerShell</p>

![7](https://github.com/nicknava1/Hash-Integrity/blob/main/Hash%20Checksum/7.png)

<p>If it matches like it did here, then you have successfully verified the integrity of your file!</p>
