# Oracle VirtualBox Server Setup

- Download Oracle VirtualBox Windows Host from offcial site [https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)

- Download Windows Server 2022 from Microsoft Evaluation Site [https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022](https://www.microsoft.com/en-us/evalcenter/evaluate-windows-server-2022)

- *After Setup Success Homepage of Windows Server 2022*

![VirtualBox Setup Screen](./Images/WelcomeServer.png)

## Extending Windows Server 2022 Trial for 3 Years

Open CMD and enter **' slmgr.vbs /rearm '** to extend it for 1 year and this command can be used 3 times hence extending it to 3 years.

Verify the same using **' slmgr.vbs /xpr '** which will give expiry date.

Other Commands: **' slmgr.vbs /dlv '** gives current license state.
                **' slmgr.vbs /ato '** syncs License to Microsoft Server.

## Windows 11 Pro Client Setup
