# alfred-workflow-raspberry-pi-4
Alfred Workflow for easy SSH and change in VPN location for Raspberry Pi VPN router

This workflow was created for personal use.
The workflow as of version 1.0 helps to solve two purposes.

1. To SSH into Raspberry connected in local network.

2. To change the VPN location coming through the Raspberry PI Wifi AP.

This Workflow needs the IP address to be changed according to the local network input to the Raspberry Pi. One will also need a seperate VPN subscription which has openvpn configuration files ```.ovpn```. eg: NordVPN, ExpressVPN, VyprVPN.

Follow this site to make VPN Router from Raspberry PI:
``` https://pimylifeup.com/raspberry-pi-vpn-access-point/ ```.

In the above tutorial, use ```uk1770``` in place of ```au120``` for this workflow to work.

To allow the change in location, create a directory in ```/etc/openvpn/``` as ```allvpn```, where you should store all configuration files for different locations and change there name. In this workflow we have ```US```, ```UK```, ```Ireland```, ```India``` and ```Japan```.

The Raspberry Pi needs to be turned on and connected to the same network as the computer which runs this workflow.
