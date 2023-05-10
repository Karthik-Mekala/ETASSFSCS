# ETASSFSCS
***Efficient Traceable Authorized Search System for Secure Cloud Storage*** 😄
#

### Team :

- [Karthik](https://github.com/Karthik-Mekala)
- [Mahaboob Basha](https://github.com/Mmabhu)
- [Bindu Shruthika]()
- [Naga Lakshmi]()
- [Mahendra Kumar Reddy]()

# <p align="left">TLTR :stuck_out_tongue_winking_eye: Check the <a href="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/Final%20Year%20Project%20PPT.pptx"> PPT</a> or <a href="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/Documentation/Team%20Documentation/Documentation.pdf">Documentation</a></p>


## How it works :
- [Download Softwares](https://www.dropbox.com/s/ktcw6t9qjp347kf/Softwares%20Required.zip?dl=0)
- [Download Code](https://www.dropbox.com/sh/8304d6zk7akpl20/AADnEjFCwZ6t5uZU2wakAnfXa?dl=0)

#### Step-1 :
The proposed system involves a secure cloud-based file management solution with multi-level access control. The system comprises a home page, which serves as the initial landing page that provides an abstract, introduction, and details about the organization.

<table>
  <tr>
    <th><img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/home1.png" alt="Home Page"></th>
    <th><img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/home2.png" alt="Home Page"></th>
  </tr>
</table>

#### Step-2 :
The Key Generation Center (KGC) page is an administrative page that facilitates access control. The KGC is responsible for granting access to newly registered owners and users and providing three-step verification, which includes public and private keys, file details, and One-Time Password (OTP).

#### Step-3 :
Owners can register on the owner registration page by providing their name, password, email, mobile number, and multiple keyword attributes, such as branch, department, subdepartment, and job role. After registration, the KGC accepts the owner's request for access, and the owner can log in to the system.

#### Step-4 :
Once an owner logs in, they can access internal pages, such as uploading files into the cloud, which is stored in a local database. The uploaded files are encrypted in cipher text to ensure that they are secure and cannot be accessed by unauthorized users. Owners can view all the uploaded files from the view uploaded files page.

#### Step-5 :
Users can register on the user registration page using the same multi-keyword attributes as the owner to access their respective uploaded files. If the multi-keyword attributes of the user and owner do not match, the user cannot access the owner's files.

#### Step-6 :
After the KGC accepts user registration, the user receives an email with public and secret keys. Upon logging in, the user can access internal pages to search for available files in the cloud using the public and secret keys.

#### Step-7 :
If the user and owner have equal multi-keyword attributes, the user can request file details from the KGC to download a specific file uploaded by the owner.

#### Step-8 :
The KGC sends the user the file details, including the file name, file key, file ID, and owner parse key, via email. To download the file, the user must enter the correct OTP on the download files page.

### Note :
For KGC, managing all owners, users, and available files in the database or cloud can be challenging. Hence, the cloud page provides a solution where KGC can see all necessary details in one place instead of accessing the database or cloud repeatedly. The cloud restricts users and owners from obtaining unauthorized access to information, such as passwords, by only displaying essential details.





### ***Home Page*** :
<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/home1.png" alt="Home Page">
<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/home2.png" alt="Home Page">
<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/home3.png" alt="Home Page">
<img src="https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/home4.png" alt="Home Page">


## ***Owner Page*** :

##### 1. Owner Login Page :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/dataOwner.png" alt="Data Owner Login Page">

##### 2. Owner Registration Page :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/ownerReg.png" alt="Data Owner Registration Page">


## ***User Page*** :

##### 1. User Login Page :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/dataUser.png" alt="Data User Login Page">

##### 2. User Registration Page :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/userReg.png" alt="Data User Registration Page">

## ***KGC Page*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/kgc.png" alt="KGC Login Page">

## ***Cloud Page*** :
<img src = "https://github.com/Karthik-Mekala/ETASSFSCS/blob/main/screenshots/cloud.png" alt="Cloud Login Page">
