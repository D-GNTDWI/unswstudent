#
//Beginning Cyber Security 

//18 Feb 2021
          
    //I will be using 'DGNTDWI' for anonymity and the repository is my diary.
    
    //Today, I have installed Kali Linux through the Windows Subsystem for Linux 2. 
    //Upon my first install error, I entered into the terminal, "sudo apt-get install dbus-x11" to continue with the installation.
    //Upon installing, I had to reboot and enter the BIOS to enable SVM mode for virtualisation with an AMD processor.
    //Once Kali was running, I first queried my own IP address with "$ ip add" in the Kali terminal. 
    //Then opened Windows' Remote Desktop Connection, entered the IP address and the GUI appeared.
    
    //TIP: Open Kali, then $ sudo service xrdp start ; $ ip add ; "OpenRemoteDesktopConnection"

# Books
//List of books that I began to read.

    ISBN-13:978-1980901754 The Hacker Playbook 3 by Peter Kim
    ISBN 978-1-78216-318-3 Mastering Wireless Penetration Testing for Highly Secured Environments by Aaron Johns
    ISBN 978-1-84969-510-7 Penetration Testing with the Bash shell by Keith Makan
    ISBN 978-1-78216-678-8 Metasploit Penetration Testing Cookbook by Monika Agarwal and Abhinav Singh
    ISBN 978-0-12-411644-3 The Basics of Hacking and Penetration Testing Second Edition by Patrick Engebretson
    ISBN 978-1-849513-94-4 BackTrack 4: Assuring Security by Penetration Testing by Shakeel Ali and Tedi Heriyanto
    ISBN 978-1-78328-041-4 Kali Linux Wireless Penetration Testing Beginner's Guide by Vivek Ramachandran and Cameron Buchanan
    ISBN 978-1-78216-316-9 Web Penetration Testing with Kali Linux by Joseph Muniz and Aamir Lakhani
    ISBN 978-1-78398-852-5 Web Penetration Testing with Kali Linux Second Edition by Juned Ahmed Ansari
    ISBN 978-1-78216-274-2 Linux Shell Scripting Cookbook Second Edition by Shantanu Tushar and Sarath Lakshman
    ISBN 978-1-78528-556-1 Mastering Kali Linux Wireless Pentesting by Brian Sak and Jilumudi Raghu Ram
    ISBN 978-1-78439-643-5 Penetration Testing with Raspberry Pi by Aamir Lakhani and Joseph Muniz
    ISBN 978-1-449-34421-4 Getting Started with Raspberry Pi by Matt Richardson and Shawn Wallace
    ISBN 978-1-78398-214-1 Kali Linux Network Scanning Cookbook by Justin Hutchens
    ISBN 978-1-78328-959-2 Kali Linux Cookbook by Willie L. Pritchett and David De Smet
    ISBN 978-1-78216-312-1 Mastering Kali Linux for Advanced Penetration Testing by Robert W. Beggs
    ISBN 978-1-84969-566-4 Instant Kali Linux by Abhinav Singh
    
# Links subscribed

    https://pentesterlab.com/
    https://www.hackthebox.eu/
    https://tryhackme.com/
    
# 6 March
    //Setup of VirtualBox 6.1 by viewing https://www.virtualbox.org/wiki/Downloads 
    //Also have to install the VB Extension Pack, however my system downloaded the .gz file. 
    //Change the .gz to .vbox-extpack and VB will install the pack.
    //Created a 4gb memory, 10gb storage, VDI with 2 cores and installed Kali Linux OS.

    //With the support of Bombal, I have tinkered around with Wifite below. 
    //Note this doesn't work with WSL2 (due to network adapter access).
    //$ sudo wifite
    //Encountered "Error: airmon-ng did not find any wireless interfaces" etc
    //$ sudo apt update
    //$ sudo apt install hcxdumptool 
    //$ sudo apt-get install libpcap-dev
    //$ sudo apt-get install python2.7-dev libssl-dev zlib1g-dev libpcap-dev
    //$ git clone https://github.com/JPaulMora/Pyrit.git
    //$ cd Pyrit
    //$ sudo python setup.py clean
    //$ sudo python setup.py build
    //$ sudo python setup.py install
    //$ clear
    
# 13 March

    //I received a high unusual phone call so I attempted recon techniques through the PhoneInfoga toolset.
    //curl -L "https://github.com/sundowndev/phoneinfoga/releases/download/v2.0.8/phoneinfoga_$(uname -s)_$(uname -m).tar.gz" -o phoneinfoga.tar.gz
    //tar xfv phoneinfoga.tar.gz
    //./phoneinfoga version
    //./phoneinfoga --help
    //./phoneinfoga scan -n "6104MobileNumber" 
    
