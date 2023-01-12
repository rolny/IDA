# IDA Installation
## Install main program
    ./idaprofl_hexarm64fl.run
During installing, you should input "installation password"
<img src="images/installation_password_1.png"></img>
You can find password in e-mail
<img src="images/installation_password_2.png"></img>
## Import license
### Install license server
Require java  
```commandline
sudo apt-get install openjdk-19-jre-headless
```
Second execute *lmadmin.bin* file    
```commandline
./lmadmin-x64_lsb-11_19_1_0.bin
```
### Starting server
1. starting web UI
    ```commandline
    /opt/FNPLicenseServerManager/lmadmin
     ```
2. Move *hexrays.bin* to "FNPLicenseServerManager" directory
3. Open browser *127.0.0.1:8090*(Default port 8090), and consider security, 
  should Enable HTTPS
4. Under *Vendor Daemon* page, import license *ida.lic*
### Starting main program
```commandline
~/idapro-8.1/ida64
```
