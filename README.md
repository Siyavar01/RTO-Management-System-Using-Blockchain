# RTO-Management-System-Using-Blockchain

Abstract
 
As the population is growing the number of vehicles is increasing. Keeping the valid license and vehicle papers is mandatory. It is very tedious to keep all these documents with us always and also it is difficult and time consuming for traffic police to check and verify these documents and maintain the challan regarding the vehicles. Therefore, we proposed a system in which the work of traffic police and driver (user) is simplified. In this system the driver will register to RTO services and the login credentials will be provided to the driver to login. The driver will upload document details like RTO driving license etc. therefore it is not necessary for him to carry a hard copy driving license with him and also users can raise a complaint against the police. At the RTO traffic police end the police will open the application and enter the vehicle number and the data from the server will be fetched and documents details like Emission, Insurance etc., for verification will be shown. The traffic police will be able to generate the challan through the application and it will be linked to the vehicle and the driver has to pay the challan online. This application provides services to drivers (users) and traffic police.



Motivation 
RTO vehicle inspection is an web application to inspect vehicle documents like registration card, driving license, emission test and insurance copy through application. This application contains users or drivers’ registration by entering details and uploading the all-vehicle details to the application will generate a unique personal id for all users. All users can login to the application using username and password to update the documents regularly.
Digital vehicle inspector application has admin or generally traffic police login to verify or check all users details with documents. This application is mostly useful for traffic police to check vehicle owner details in public premises and put the fine for false details or wrong vehicle owners or drivers without DL and also to catch vehicle thieves. This application will send the fine notifications to individual owners.
Bitcoin, a decentralized global currency cryptosystem, was introduced in 2008 by Satoshi Nakamoto, based on the Blockchain technology. In Bitcoin, Blockchain is used to Sensors 2020, 20, 3928 4 of 27 ensure secure exchange of digital money for goods and services without a central authority through a trusted peer-to-peer network in a pseudo-anonymous way. Blockchain or public ledger contains a record of all transactions, accessible by all participants in the network, as they are publicly announced. More precisely, each participant possesses the exact copy of the Blockchain. Individual transactions are separated into blocks, which are time-stamped and published. Subsequently, transactions cannot be modified or reversed, as the hash of the previous blocks is included in the next successors in each block of the chain. Accordingly, there is a consensus about the participants about the history of transactions. Following its successful use in bitcoin, Blockchain as a distributed ledger technology or, more precisely, a distributed database of records, has gained wide application not only in the current digital economy, but in non-financial fields as well.
 
 
Literature review

Research of evaluation of Real Face Mask Detection
In this section, we have studied the various attempts made by researchers to design and develop a technology assisted solution for the ease of traffic police and RTO. To start with, Avanish et. al. [6] proposed a system where a traffic police officer scans the license of the driver with the help of a Smart Card Reader. Here the license is kind of a smart card which contains an embedded micro module consisting of a microprocessor and memory. As the officer scans the license, the application installed on the officer's device displays the details of the driver. Meanwhile, the system verifies the license and on the basis of violated rules selected by the officer, a penalty of corresponding amount is charged to the driver and the record of the same is updated on the main server. Limitations of this system are
i. Additional cost incurred due to overhead of designing smart card based licenses.
ii. In densely populated countries like India, it is not feasible to replace all regular licenses with new one.

Smart RTO web and android application, discussed in [7], includes user module, traffic module and RTO admin module. In this system, the user module consists of forms i.e. license registration, vehicle registration and insurance forms which are to be filled by the user. The traffic module focuses mainly on providing the information to the traffic police officers which consists of license check, vehicle information check and insurance check and also generate fines in case some driver violates the rules. And the RTO admin verifies the information filled within the forms by the user to generate license and vehicle number. Limitation of the system is data security measures to avoid data leakage or alteration is not discussed E-RTO management system [8] includes registration of vehicle and storing of related data such as insurance, license plate number, etc. of the vehicle and its owner. It also includes authentication of vehicles using RFIDs which are issued by the RTO after successful verification. Here, RTO is a power user who has the power to verify and process the data provided by the user (vehicle owner/driver). Manjunath et. al. [9] proposed a system which provides services using cellular phones.

 
The architecture consists of three modules namely RTO module, Flex module and Court module. In this architecture, the RTO module is used to store data such as user license, vehicle information, vehicle insurance information, and vehicle emission information. Flex module is used by the Traffic Police officer to perform verification of Vehicle and Driver License information. It also provides a facility to generate fine amounts on the same system. Court module contains information regarding Officer Id, Date, Vehicle Registration, list of Offences, Fine Amount, and Payment Status. A. Choudhury et. al. [10] discussed the number plate identification method based on horizontal and vertical edge processing and zone detection. This method proved to be an effective way to predict the number of the vehicle from the image of number plate capture from any angle or with any background. Ayman Rabee et. al. [11] has put forth a robust license plate recognition system. In the pre-processing part, the color image is converted to a grayscale using a weighted sum method. Then contrast enhancement is applied for extracting License plate number from poor illumination which is then followed by mathematical morphology and segmentation using eight connected component algorithms. Then character segmentation is carried out and finally characters are recognized using support vector machines (SVMs).
 
Here the author has achieved the character recognition accuracy of 97.89%. The RTO verification system is proposed by Amruta et. al. [12] in which the authors have suggested maintaining a centralized RTO database containing the information about vehicles and drivers. Using an android application, traffic police can retrieve vehicle and license information. They have not considered the data security aspect of centralized databases. The proposed system [13] first detects any vehicle which violates traffic rules and then captures the vehicle image. From the captured image, using image segmentation technique the license number plate region will be extracted. And the technique used for the character recognition on the number plate is Optical character recognition. The system is implemented and simulated using Matlab. Using the feedback system, the extracted license plate number is then given to GSM modem for further SMS feedback system to the user and concerned authority.

Problem formulation/Objectives

Here, we are developing a web application for RTO so here we give a brief description of our project overview. First, providing a familiar environment means the needy user can access this site for their work purpose related to RTO. First the user needs to fill the registration form so that we provide authentication to him. If a user wants to pass his vehicle number then also it takes time in the old system . The administrator is provided for authentication purposes as well as it handles all the databases of RTO and manages all the processes. He has authority to approve learning license number, permanent license number;pass the vehicle registration number, etc. Users have to find the police station and then raise the complaint. This takes time to pay the fine and they have to go to the RTO office. This also is a waste.


Methodology/ Planning of work

SYSTEM ARCHITECTURE
The system consists of three main modules i.e. admin, traffic police & user. The user registers at admin for the service and admin verifies the user and registers the user’s information in the RTO database. The traffic police are also registered by the admin. After registering the user logins to the user app code for the license.. The traffic police and enter vehicle number to check the license and all vehicle documents. The traffic police determine the challan and apply it to the driver and the challan data will be updated to the RTO database. The admin has all the rights to view, update and insert data into the RTO database. It involves identifying the major components of the system and communications between these components. The following subsections delve into the design aspects and the sub systems involved in this software package.
 
“RTO Management System” is an Automation of the Road Transport Department through Cellular Network. We are proposing a model in which we aim to provide better services through cellular phones. The architecture mainly consisting three modules:
1.  R.T.O module: In this module, it consists of the database of user License, Vehicle information, vehicle Insurance information, & the vehicle Emission information. The License module includes all the information regarding applicants personal details like Name, DOB ,Address, Contact no. Identity marks, photo and also license details such as Type of license, License status and Validity of the license. It is also responsible for adding and managing license related records to the database.
 

2. Flex module: This module is used by the Traffic Police officer [3]; it is mainly used to perform verification of Vehicle and Driver License information. It also provides a facility to generate finesfines on the same system . The Vehicle module includes all the information regarding Vehicle details like Vehicle Registration no., Manufacturer Name, Model Name, Purchase Date, Fuel Type and so on. It also includes the Vehicle Owner details like Name, Address, Contact no.. It is also responsible for adding and managing vehicle related records to the database.
 3.  Court module: It contains information regarding Officer Id, Date, Vehicle Registration, list of Offenses, Fine Amount, and Payment Status. The Insurance module includes all the information regarding Vehicle details like Vehicle Registration no., Manufacturer Name, Model Name, Purchase Date, Fuel Type and so on. It also includes the Vehicle Owner details like Name, Address, Contact no.. It also includes Insurance related information like Company Name, Policy no., Validity. It is also responsible for adding and managing insurance related records to the database
4. The Emission module includes all the information regarding Vehicle details like Vehicle Registration no., Manufacturer Name, Model Name, Engine Capacity, Fuel Type and so on. It also includes the Emission details like Center Name, Emission Id and Validity. It is also responsible for adding and managing emission related records to the database. 
SYSTEM DESIGN
Data Flow Diagram
Data flow diagrams are used to graphically represent the flow of data in a business information system. DFD describes the processes that are involved in a system to transfer data from the input to the file storage and reports generation. Data flow diagrams can be divided into logical and physical. The logical data flow diagram describes flow of data through a system to perform certain functionality of a business. The physical data flow diagram describes the implementation of the logical data flow.

This are the flow of our diagram:
This data flow diagram has four levels at the first level RTO database will work
 In the second level there are three main division
1.   	User:
In the third level user can register by giving personal credentials and login
Login have its own criteria at fourth level were user have to upload the vehicle document and view the document
 User can raise a complaint against police if they have abused
 User can also pay fine through our application 
 
2.       Admin
 
In the third level Admin can register by giving personal credentials and login
 Admin can verify the vehicle documents which has been uploaded by the user
 Admin can view the complaints registered by the user 
 
3.   	Police  
In the third level Police can login by the provided login credentials
 Police can view the vehicle documents which has been verified by the RTO officer
 Police can view the old fines which have not paid
 Police can create a new fine
 
Use Case Diagram
 
A use case diagram is a low-level diagram which is used to illustrate the different ways in which the user can interact with the proposed system. It represents the way in which the system is expected to behave. It is important to help in designing the system from the perspective of the user. It therefore provides the behavior of the system on the exterior. It does not specify the order in which the events occur.
 
The figure depicts the use case diagram for our proposed system.The action performed at the admin level are admin can register himself and login, then he/she can create police login id ,approve the users vehicle document and view the complaint.Police can login using provided login credentials and create fine and view the fine.User can register himself and login ,then pay fine ,upload vehicle document,raise complaint and view documents


 
Facilities required for proposed work

The hardware and software requirements of the proposed system are as follows:
Hardware Requirements
l, Processor :   	Pentium –IV Speed -1.1Ghz
2.  RAM :          	256MB
3.  Hard disk : 	20GB
4.  Mouse :        	Two or Three button mouse
Software Requirements
 
1.  Operating System :  	Windows 10, 64 – bit.
2.  Front End :               	HTML5, CSS ,Bootstrap
3.  Back End :                	Python, Solidity
4.  Tools :                        	Robo3T, Sublime, Ganache, Remix, Mongodb
