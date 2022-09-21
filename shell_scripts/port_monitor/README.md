# README #

* You can run this scrpt

### Requirements ###

* You should have your own Telegram bot to use the script talert
* Alternatively you could use your own talert script/program to customize how you would want to be alerted if a service is UP/DOWN


### How to use? ###
* Update **port_monitor.cfg** with a list of services you would like to monitor
* Keep/Save **port_monitor.cfg** in the same directory as the main script **port_monitor** 
* Keep/Save **z.functions** in the same same directory as the main script **port_monitor**
* Run the script manually or via cron. Or any other regular to invoke this shell script

### port_monitor.cfg ###
* Column #1: FQDN or IPADDRESS of the target machine
* Column #2: PORT Number of the target machine 
* ALERT_COUNT = No of times the script will send the alert

### TRACKING and HISTORY ###
* The script maintains an active tracker in /tmp/port_monitor.tracker
* The script maintains an alert history in /tmp/port_monitor.history
* The script maintains a complete UP/DOWN history in /tmp/svc.history
* You can change these settings under the VARIABLES section of the script

### Tested on ###
* Linux: CentOS/RHEL/Ubuntu/Debian

### DISCLAIMER ###
* You are free to use the scripts for your lab/work as it is or modified to suit your needs
* I don't intend to or have the time to work via contributions in this repo at this time (maybe in the future if needed)



