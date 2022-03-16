Pre-Requisites:

1) Run 'WinServer_Discovery_C2C.exe'

NOTE- 
*** Run the exe as 'Run as Administrator'

2) Check whether the host is in "Domain" OR "Workgroup".

3) If the host is in workgroup, run the exe locally (Select Option 2 after running).
*** Windows Remote Managment service should be Running in your services

4)If the hosts are in Domain, insert the hosts details (can discover multiple hosts)for the discovery(Select Option 1 after running).

NOTE- 
*** Credentials provided must be an Admin user(User must be in administrator group). 
*** If you are not aware of the host name, kindly run 'Collect Host name.bat' file.(IP, domain\username and password is required.) [Run as Administrator]

Example:
------------------------------------------------------------------------------------------------
Host Name 	||			Username with Domain			||	Password
------------------------------------------------------------------------------------------------
MECM		||			domain1\username			||	xyz@123
HYPER-V		||			domain2\username			||	xyz@321
------------------------------------------------------------------------------------------------

5) The generated discovery report will be created on the same machine where the exe is run.
Location: C:\Users\[user.name]\Documents\Physical-WinServer_Inventory