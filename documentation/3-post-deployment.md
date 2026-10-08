Now a post deployment configuration is required, need to promote the server to a domain controller.


As this is the first deployment process is been run, “add a new forest”, also entered the “Root domain name”, can also use. local as this domain is not on the internet.

The password is entered and also confirm for the domain controller.


The NETBIOS domain name is entered for the name that would be seen for old application 

The location for the database folder, Log file folder and SYSVOL folder are all confirm (normally this should be saved in a separate hard disk).

Reviewing all selections before moving forward

Prerequisite check was successful, the install button can now be click.

Installation has begun, need to wait.

Windows will then need to restart after the installation

Checking the system info again now, the full computer name(fully qualified domain name) is now “DC01JK.domainJK.com” and also the system is no longer in a workgroup , but in a domain “DomainJK.com”.