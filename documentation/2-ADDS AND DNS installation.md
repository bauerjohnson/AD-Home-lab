To start the installation, 
Step 1) On the existing windows server , the server manager is launched to start the installation of Active Directory Domain Services (ADDS) and Domain Name System (DNS).
i)	To begin installation, click on “Add roles and features


Specific task should be confirm before starting the installation, strong password for the admin, most current security updates from windows update installed and also network settings.

The installation is for role-based or featured based installation.


A server should be selected or a virtual hard disk for installation, by default, the IP address and the operating system (Data center evaluation) are captured.

For server roles, Active Directory Domain Services and DNS server should be selected

Active Directory Domain Services is selected and the features are been added, ADDS uses domain controllers to give network users access to permitted resources anywhere on the network through a single logon process.


DNS server is selected and the features are been added, DNS servers provides name resolution for TCP/IP network.

.NET framework 4.7 and group policy management are selected for in features, Group policy management is the standard tool for managing group policy and .NET framework 4.7 provides a comprehensive and consistent programming model for quickly and easily building and running applications.


Both ADDS and DNS installation should be done together, to help ensure that users can still log on to the network in the case of severe outage.