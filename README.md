# PHP
<< Run PHP Built-in Web Server Local on Windows 10/11 Computer >>
php.exe -S localhost:8000 
* which will process display .php source code within same directory for examples:
  G:\DevTest\PHP\php.exe, index.php, phpinfo.php
  
test it out http://localhost:8000 display default index.php,
http://localhost:8000/phpinfo.php "shows PHP Version 8.2.11, etc."

* To Stop or Exit PHP Built-in WebServer currently running on Port 8000
  type Control-C or CTRL-C
  
<< Download run PHP Built-in Web Server >>
https://windows.php.net/download#php-8.2
"choose below example for download 
php-8.2.11-nts-Win32-vs16-x64.zip"

VS16 x64 Non Thread Safe (2023-Sep-26 15:55:26)
Zip [30.24MB]
sha256: 2f603db80f0e4ffd0330140d12926a822e47f9825fd0adbb55611857aa1b4109

extract in G:\DevTest\PHP now has G:\DevTest\PHP\php.exe, php8.dll, php-cgi.exe etc
