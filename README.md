# my-linux-tools
I have started learning Linux.There are shell scripts at "/bin" I have wrote.
## loginBUPT
ITS NOT MY ORIGINAL WORK.I just close the output.  
This script can login BUPT network account without browser like "firefox".
## download-from-vm
This script can download from my virtual machine by `wget`.  
WHY I use this script:  
The network accounting of BUPT is a traffic accounting.The tool "Mashang6" can download anything through IPv6.So that we need not  to pay.But that tool is only supported on Windows.So I create a Windows XP virtual machine to solve this problem.I download file on the virtual machine by "Mashang6", and the Linux machine downloads it from the virtual machine through HTTP protocol.The HTTP server on my virtual machine is tomcat, and the download website is examples/download.
