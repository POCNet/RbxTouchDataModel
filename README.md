# RbxTouchDataModel
RbxTouchDataModel is an open source project dedicated to creating a virtual machine on the ROBLOX host and running RCC and Arbiter on the virtual machine. RbxTouchDataModel is dedicated to 2016M-2018L Clients as hosting servers for revival / ORC might be difficult. We offer you the opportunity to host servers for free, with access to the VM / Server you created on OUR platform.

# How it works, what it uses
How RbxTouchDataModel works:

* RbxTouchDataModel uses an L7 protected WebServer to request a new VM using a new property / compatibility feature in the ROBLOX client
* The WebServer assigns a name, port and IP address for the VM / server.
* The ROBLOX VM platform assigns the files for the server / VM.
* ROBLOX runs a Service Pack (SP1) on Windows Service Pack 2008
* The ROBLOX VM platform runs RDP / UDP access to the server / VM using SOAP and RCCService.
* ROBLOX transfers ownership to your DESKTOP ID (Machine Signature, WindowsVista -> Windows 10+)


What RbxTouchDataModel uses:

* ROBLOX VM platform
* ROBLOX RCC and SOAP protocols
* Files edited by ui0ppk (https://github.com/ui0ppk/roblox-master)
* POCNet Virtual Machine Hosting Platform
* Network cluster platform
* RCC Render & Arbiter
