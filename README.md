3proxy install script for Debian / Ubuntu VPS (ver 0.8.10)
======================================================

**HOW TO :**

Download, make executable and run with these lines :

    wget --no-check-certificate https://raw.github.com/h1777/3proxy/master/3proxyinstaller.sh
    chmod +x 3proxyinstaller.sh
    ./3proxyinstaller.sh

After install : CHANGE DEFAULT USERNAME AND PASSWORD !!! 

Example: johndoe:CL:johndoepassword123

    nano /etc/3proxy/.proxyauth
      
Once you've change the username / password you can start the proxy 
(or reboot the VPS as 3proxy has been added to the init scripts and will autostart)

    /etc/init.d/3proxyinit start




You can also change the port, default is 3128 (OPTIONAL)

    nano /etc/3proxy/3proxy.cfg
    	
For Uninstall Download, make executable and run with these lines :

	wget --no-check-certificate https://raw.github.com/h1777/3proxy/master/3proxyuninst.sh
	chmod +x 3proxyuninst.sh
	./3proxyuninst.sh

**Script tested on May 2017 on the following fresh VPS install distros :**

- Ubuntu 16.04 64bit (Vmware)
- Ubuntu 17.04 64bit (KVM)
- Debian 8 64bit (Vmware)


**Script will run on :**
- ?
