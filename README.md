# Website Vulnerability Scanner

Website vulnerability scanner written in PHP.

## Disclaimer
* This tool is for testing and educational purposes only. **Don't use it for illegal purposes!** I am not responsible for any misuse or damage caused by this tool.

## Installation

``` git clone https://github.com/CyberCommands/WebScanner.git ```

``` cd WebScanner/ ```

``` php scanner.php ```

## Usage

```
$ php scanner.php
|#############################################################|
[!] WARNING: The Author is not responsible for illegal users.
      __      __      ___             __  __              
     /  \    /  \ ____\_ |__    _____|__|/  |_  ____      
     \   \/\/   // __ \| __ \  /  ___/  \   __\/ __ \     
      \        /\  ___/| \_\ \ \___ \|  ||  | \  ___/     
       \__/\  /  \___  >___  / /___  >__||__|  \___  >    
            \/       \/    \/      \/              \/     
    _________                                            
   /   _____/ ____  _____    ____   ____   ___________    
   \_____  \_/ ___\ \__  \  /    \ /    \_/ __ \_  __ \   
   /        \  \___  / __ \|   |  \   |  \  ___/|  | \/   
  /_______  /\___  >/____  /___|  /___|  /\___  >__|      
          \/     \/      \/     \/     \/     \/          

  Website vulnerable scanner Tools by CyberCommands
|#############################################################|

[Tips] For help, type 'help' and to quit please type 'quit'

> COMMAND $ help
[sql] --------> Scan SQL Injection vulnerable
[xss] --------> Scan XSS(cross site scripting) vulnerable
[rfi] --------> Scan RFI(remote file include) vulnerable
[lfi] --------> Scan LFI(local file include) vulnerable
[pmapwn] -----> Scan phpMyAdmin code injection vulnerable
[full] -------> Grab link from website and start all scan
[google] -----> Grab website from google and start all scan
[getlist] ----> Grab website from file and start all scan
[jump] -------> Find all site hosted on same ip and start all scan
[exploit] ----> Exploit-DB Exploit Finder
[injector] ---> Automatic SQL Injector, work for v4 and v5
[hexstring] --> Convert string to hex (useful for sql injection)
[md5string] --> Convert string to MD5 Hash
[portscan] --> Check port open and close
[wget] -------> Get file from URL

> COMMAND $ 
```
