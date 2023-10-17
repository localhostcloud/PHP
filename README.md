# PHP
<< Run PHP Built-in Web Server Local on Windows 10/11 Computer >>
php.exe -S localhost:8000 
* which will process display .php source code within same directory for examples:
  H:\DevTest\PHP\php.exe, index.php, phpinfo.php
  
test it out http://localhost:8000 display default index.php,
http://localhost:8000/phpinfo.php "shows PHP Version 8.2.11, etc."

* To Stop or Exit PHP Built-in WebServer currently running on Port 8000
H:\DevTest\PHP>php.exe -S localhost:8000
[Sun Oct 15 06:10:15 2023] PHP 8.2.11 Development Server (http://localhost:8000) started
[Sun Oct 15 06:10:25 2023] [::1]:50951 Accepted
[Sun Oct 15 06:10:25 2023] [::1]:50951 [200]: GET /phpinfo.php
[Sun Oct 15 06:10:25 2023] [::1]:50951 Closing
[Sun Oct 15 06:10:25 2023] [::1]:50952 Accepted

type Control-C or CTRL-C and bring back to cmd line (CLI) below 
H:\DevTest\PHP

<< Download run PHP Built-in Web Server >>
https://windows.php.net/download#php-8.2
"choose below example for download 
php-8.2.11-nts-Win32-vs16-x64.zip"

VS16 x64 Non Thread Safe (2023-Sep-26 15:55:26)
Zip [30.24MB]
sha256: 2f603db80f0e4ffd0330140d12926a822e47f9825fd0adbb55611857aa1b4109

extract in H:\DevTest\PHP now has G:\DevTest\PHP\php.exe, php8.dll, php-cgi.exe etc

**** Please contact RMDH if you need steps to configure run PHPInfo.php on below Platforms 

<< Microsoft Windows Server Platform >>
https://www.microsoft.com/en-us/windows-server/

<< Red Hat OpenShift Container Platform >>
https://www.redhat.com/en/technologies/cloud-computing/openshift/container-platform

<< AWS Cloud Platform >>
https://aws.amazon.com/

<< Microsoft Azure Cloud Platform >>
https://azure.microsoft.com/en-us/

<< Linux, Virtual Machine Platform >>

===================================================================
* Author/Coder/Engineer/Programmer/Technical Support: RMDH


