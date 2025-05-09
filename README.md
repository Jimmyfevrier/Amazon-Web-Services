<p align="center"> Amazon-Web-Services </p>

<p align="center">
<img width="400" alt="Image" src="https://github.com/user-attachments/assets/6d11a4cf-52cc-48f5-8634-feed5a5b500d"/>
</p>

<h1> Creating Instances on EC2 </h1>
An Instance is the same thing as creating a Virtual Machine on Azure. Instead of calling it a VM on AWS they call it Instance. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: How to create an EC2 instance](https://youtu.be/86Tuwtn3zp0?si=hcpWygWuTppk5zzb)

<h2>Environments and Technologies Used</h2>

- Mac Bookpro
- AWS Account
- Microsot Remote Desktop


<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<h2> Steps to Create an EC2 Instance on AWS </h2>

- Step 1: I created a Free AWS account
  - note: that the free account allows you to create a free Instance for practice/testing purposes. 
- Step 2: create an Instance on EC 2
  - created 2 encripted keys
  - note: that you can create multiple instances at the same time. 
- Step 3: Connected to the Instance

<h2> Creating a Free AWS account </h2>

<p><h3> AWS account </h3> </p>
<p>
I went https://aws.amazon.com/free and created a free account. Once completed I observed menu options to get a understanding. 
</p>
<p>
<<img width="858" alt="Image" src="https://github.com/user-attachments/assets/f74e765f-c69e-49e2-a691-66f7753a058e" />
</p>

<br />
<p><h3> Creating an Instance on EC 2 </h3> </p>
<p> 
Click Search Bar > Type and select: "EC2" > Launch Instance
</p>
<br>
<p> Now you can Name your PC, select the version of PC you want, select how many RAMs, Create security groups and Add more security features (to block off traffic from untrusted websites), and an option to increase the amount of Instances created all at once. 

  note: This where you need to create a Key Password. Once the Key is created it will download it as an encripted file automatically into your computer. All Keys and passwords should be stored in a secured location (especially for a host computer). 
<p>
<img width="858" alt="Image" src="https://github.com/user-attachments/assets/f5dd9f05-9cca-44f0-8031-00812a97cfa5" />
</p>

<br />
<p><h3> Connected to the Instance </h3></p>
<p>
Once completed, I launch the instance (using Windows 2025). The Instance takes a few minutes to completely initialize, but once it was completed and running I selected the Windows Instance and select the Connect button. Next, I went to RDP Client (remote desktop Protocol) and selected the download link to install RDP which automatically adds the Instance and back on the webpage I uploaded the password key which populated a password so I can connect to the Instance.   
</p>

<p>
<img width="858" alt="Image" src="https://github.com/user-attachments/assets/1761047b-bc53-4863-8d3f-26fa44147ab7" />
</p>

<br />

<p> 
I Open up a Powershell Window as an Admin and practice pulling informaiton from the DNS server and practice flushing the Server as well to practice troubleshooting old Ip Address issuse. 
</p>
<p> <img width="858" alt="Image" src="https://github.com/user-attachments/assets/bc7a6204-409e-4470-a005-7fe9616646df" /> </p>

