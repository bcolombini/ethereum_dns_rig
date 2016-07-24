ETHEREUM DNS NO-IP
===================

Hi, this repository help you to install **DNS Server** in your **RIG** with **Ubuntu** for access with **ssh**.

----------


Install
-------------

 1. Create account in [NO-IP](https://www.noip.com/).
 2. Create a host in [ADD A HOST](https://www.noip.com/members/dns/).
 3. Clone this repository in your Desktop.
 4. Execute  *install_noip.bash* with sudo.
> sudo sh ethereum_dns_rig/install_noip.bash

 5. Put your e-mail that use to sign up in **no-ip** and your password.
 6. Move *rcX.d to /etc/init.d/* for startup with **Ubuntu**.  
> sudo mv  ethereum_dns_rig/rcX.d /etc/init.d/
 
 7. Reboot system


