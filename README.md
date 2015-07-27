# my-linux-tools
I have started learning Linux.There are shell scripts at "/bin" I have wrote.
## loginBUPT
ITS NOT MY ORIGINAL WORK.I just close the output.  
This script can login BUPT network account without browser like "firefox".
## download-from-vm
usage: download-from-vm [filename]  
This script can download from my virtual machine by `wget`.  
The http server on my virtual machine is tomcat, and the download website is examples/download  
WHY I use this script:  
The network accounting of BUPT is a traffic accounting.The tool "mashang6" can download anything through IPv6.So that we need not  to pay.But that tool can only supported on Windows.So I create a windows xp virtual machine to solve this problem.I download file on the virtual machine by IPv6, and the Linux machine download it from the virtual machine through http protocol.
