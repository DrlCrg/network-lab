# network-lab
This is the process of creating a small network for our lab

#We were given this scenario:
![Screenshot 2024-02-22 161302](https://github.com/DrlCrg/network-lab/assets/160629376/201a3bd8-2c2c-4638-8353-9aa7ffcf3289)

#stage 0

This is what we started with: the WAN-cloud and the WAN-Switch.
![Stage0-NT](https://github.com/DrlCrg/network-lab/assets/160629376/5ddedfa0-6eee-4ebe-adf9-a7f125ab2be6)


#stage 1 

![Stage01-NT](https://github.com/DrlCrg/network-lab/assets/160629376/2ad93266-929a-4eb0-aaa6-63dfb67fbebf)

We reserved 10.128.0.0/24 for our LAN. 
This is where we also set up our DHCP server and set up our DNS.
We then added the Windows 10 (win10) user to the LAN and modified our firewall settings using the GUI via our win10 workstation.

#Stage 2

![STAGE02-NT](https://github.com/DrlCrg/network-lab/assets/160629376/4d6074b3-cc5c-43de-b18b-4037b4c7dc63)

Next we added a Windows server to the network. This entailed connecting it to the workspace, installing Active Directory Domain Services and joining it to the domain. Then we added administrative and user accounts. Once the accounts were set up we joined win10 to the widgets.localdomain domain.

#Stage 3

![STAGE03-NT](https://github.com/DrlCrg/network-lab/assets/160629376/2244c423-8be7-4396-86dd-fd10c352cb22)

We added another Win2012 server to the workspace and joined it with the domain, installed the Internet Information Services role, and added a test web page to make sure we could access it via LAN.

#Stage 4

![STAGE04-NT](https://github.com/DrlCrg/network-lab/assets/160629376/03b3808a-b796-47bb-a878-f3f7c5ff4b64)

An Ubuntu server was set up and linked to the DMZ-SWITCH. DOKU-WIKI was also installed and configured. Then a VIP was set up for the webserver.

#Stage 5

![STAGE05-NT](https://github.com/DrlCrg/network-lab/assets/160629376/eb89ef6b-bdd4-4016-9db0-aca040f819d4)

Here is where we added an FTP server and configured it so we could join it with the domain. 
