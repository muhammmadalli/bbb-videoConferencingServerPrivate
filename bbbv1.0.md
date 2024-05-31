Go to https://sourceforge.net/projects/bigbluebutton-vm/files/
Download any version you like, beta - if you can handle it. I chose BigBlueButton 1.0.zip.
Direct download link for v1.0: https://sourceforge.net/projects/bigbluebutton-vm/files/BigBlueButton%201.0.zip/download
The zip package conatins pre-installed BigBlueButton vmware image.

username: bigbluebutton
password: default

After downloading the zip file.
1. Extract the content.
2. Open with VMware or VMware ESXi.
3. Start the virtual machine and wait till the machine creation is finished.
4. Login using following user/pass: bigbluebutton/default .
5. Enter "ifconfig" to get current ip address (example: 192.168.1.133), or set address of your choice, ( e.g. root# ifconfig 192.168.1.2 netmask 255.255.255.0 )
6. Enter "sudo bbb-conf --setip <ip>" and wait for bigbluebutton to restart, ( e.g. root # sudo bbb-conf --setip 192.168.1.2 )
7. Open browser and enter http://<ip>/ to check if server is working properly, ( e.g. http://192.168.1.2 )
