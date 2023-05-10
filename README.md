# Efficient Traceable Authorized Search System for Secure Cloud Storage
***ETASSFSCS*** 😄

As an example, let us consider a multinational software company such as TCS with branches located in various regions across the world. For the purpose of illustration, we can focus on two of its branches located in Bangalore and Hyderabad, India, respectively. Suppose that you are currently employed in the finance department of the Bangalore branch, while your friend works in the technical department of the Hyderabad branch.

If your friend requests that you obtain and share technical department-related files from your own branch's database, this would be a violation of company policy and may be considered illegal. Despite your friendship, it is imperative that you adhere to the company's regulations and not share any information that you are not authorized to access.

To address such situations, an Efficient Traceable Authorized Search System for Secure Cloud Storage can be implemented to prevent unauthorized access to data. The system can be designed to restrict access to only authorized personnel and specific data within their designated departments. In this example, the system would allow you to access only finance department-related files uploaded by your higher authorities, and not technical department-related files from your branch or any other branch.

In terms of future enhancements for such a system, advanced features could be implemented to further enhance security and efficiency. For instance, machine learning algorithms could be utilized to automatically detect and prevent potential breaches or security threats. Additionally, the system could be designed to provide real-time monitoring and alerts for any unauthorized access attempts or suspicious activities. These enhancements would ensure that the system is continuously adapting to evolving security threats, and providing an even more secure and efficient cloud storage solution.

- [Download Required Softwares](https://www.dropbox.com/s/ktcw6t9qjp347kf/Softwares%20Required.zip?dl=0)
- [Download Code](https://www.dropbox.com/sh/8304d6zk7akpl20/AADnEjFCwZ6t5uZU2wakAnfXa?dl=0)
#

### Team :

- [Karthik](https://github.com/Karthik-Mekala)
- [Mahaboob Basha](https://github.com/Mmabhu)
- [Bindu Shruthika]()
- [Naga Lakshmi]()
- [Mahendra Kumar Reddy]()

# <p align="left">TLTR :stuck_out_tongue_winking_eye: Check the <a href="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/Final%20Year%20Project%20PPT.pptx"> PPT</a> and <a href="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/Documentation/Team%20Documentation/Documentation.pdf">Documentation</a></p>


## How it works :


### Step-1 :
The proposed system involves a secure cloud-based file management solution with multi-level access control. The system comprises a home page, which serves as the initial landing page that provides an abstract, introduction, and details about the organization.

<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/home1.png" alt="home1.png">
<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/home2.png" alt="home2.png">
<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/home3.png" alt="home3.png">
<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/home4.png" alt="home4.png">



### Step-2 :
Owners can register on the owner registration page by providing their name, password, email, mobile number, and multiple keyword attributes, such as branch, department, subdepartment, and job role. After registration, the KGC accepts the owner's request for access, and the owner can log in to the system.

<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/ownerReg.png" alt="ownerReg.png">



### Step-3 :
The Key Generation Center (KGC) page is an administrative page that facilitates access control. The KGC is responsible for granting access to newly registered owners.

<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/kgc.png" alt="kgc.png">

#### ***Activate Owner*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/activateOwner1.png" alt="activateOwner1.png">
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/activateOwner2.png" alt="activateOwner2.png">
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/activateOwner3.png" alt="activateOwner3.png">




### Step-4 :
Once an owner logs in, they can access internal pages, such as uploading files into the cloud, which is stored in a local database. The uploaded files are encrypted in cipher text to ensure that they are secure and cannot be accessed by unauthorized users. Owners can view all the uploaded files from the view uploaded files page.

#### ***I. Owner Login Page*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/ownerLogin.png" alt="ownerLogin.png">

#### ***II. Owner Upload Files Page*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/ownerUploadFiles.png" alt="ownerUploadFiles.png">
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/ownerUploadFiles1.png" alt="ownerUploadFiles1.png">

#### ***III. Owner's Encrypted Files*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/encryptedOwnerFile.png" alt="Owner Login Page">

#### ***IV. View Uploaded Files Page*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/ownerViewUploadedFiles.png" alt="Owner Login Page">




### Step-5 :
Now, Users can register on the user registration page using the same multi-keyword attributes as the owner to access their respective uploaded files. If the multi-keyword attributes of the user and owner do not match, the user cannot access the owner's files.

<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/userReg.png" alt="userReg.png">


### Step-6 :
The Key Generation Center (KGC) page is an administrative page that facilitates access control. The KGC is responsible for granting access to newly registered users and providing three-step verification, which includes public and private keys, file details, and One-Time Password (OTP).

<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/kgc.png" alt="KGC Login Page">


#### ***Activate User*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/activateUser1.png" alt="Activate User">
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/activateUser2.png" alt="Activate User">
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/activateUser3.png" alt="Activate User">


### Step-7 :
After the KGC accepts user registration, the user receives an email with public and secret keys. Upon logging in, the user can access internal pages to search for available files in the cloud using the public and secret keys.

#### ***I. Public & Secret keys*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/mail%20keys%201.png" alt="mail keys1.png">
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/mail%20keys.png" alt="mail keys.png">

#### ***II. User Login Page*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/userLogin.png" alt="userLogin.png">

#### ***III. Search Files Page*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/userSearchFiles1.png" alt="userSearchFiles1.png">



### Step-8 :
If the user and owner have equal multi-keyword attributes, the user can request file details from the KGC to download a specific file uploaded by the owner.

<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/userSearchFiles2.png" alt="userSearchFiles2.png">


### Step-9 :
The KGC accepts and sends the user the file details, including the file name, file key, file ID, and owner parse key, via email. To download the file, the user must enter the correct OTP on the download files page.

#### ***I. KGC Accepting User Request*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/kgcAcceptUserFileDownloadRequest.png" alt="kgcAcceptUserFileDownloadRequest.png">
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/kgcAcceptUserFileDownloadRequest1.png" alt="kgcAcceptUserFileDownloadRequest1.png">

#### ***II. File Details*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/mail%20file%20details1.png" alt="mail file details1.png">
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/mail%20file%20details.png" alt="mail file details.png">

#### ***III. Download Files Page*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/userDownloadFiles1.png" alt="userDownloadFiles1.png">

#### ***IV. OTP*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/mail%20otp%201.png" alt="mail otp 1.png">
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/mail%20otp%202.png" alt="mail otp 2.png">
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/userDownloadFiles2.png" alt="userDownloadFiles2.png">

#### ***V. Download Files*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/userDownloadFiles3.png" alt="userDownloadFiles3.png">


## Note :
For KGC, managing all owners, users, and available files in the database or cloud can be challenging. Hence, the cloud page provides a solution where KGC can see all necessary details in one place instead of accessing the database or cloud repeatedly. The cloud restricts users and owners from obtaining unauthorized access to information, such as passwords, by only displaying essential details.

#### ***I. Cloud Login Page*** :
<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/cloud.png" alt="cloud.png">

#### ***II. View Owners List Page*** :
<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/cloudViewOwnersList.png" alt="cloudViewOwnersList.png">

#### ***III. View Users List Page*** :
<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/cloudViewUsersList.png" alt="cloudViewUsersList.png">

#### ***III. View All Available Files List Page*** :
<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/cloudViewFilesList.png" alt="cloudViewFilesList.png">



## Tech Stack :
- Java Programming Language
- HTML, CSS & JavaScript.
- NetBeans (IDE used for Frontend & Backend)
- MySQL
- SQLyog (IDE used for MySQL)
- GlassFish Server & Apache Tom Cat Server
