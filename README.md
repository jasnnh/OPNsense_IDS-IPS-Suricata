# OPNsense_IDS-IPS-Suricata
Using Suricata IDS/IPS plugin on OPNsense to block and log attacks and using Kali-Linux to do nmap scans.

So first i ran Kali Linux on stand-by to do a network scan.

![image](https://github.com/jasnnh/OPNsense_IDS-IPS-Suricata/assets/54391730/4c352e07-09ed-45b4-8261-99ebe0e1afa3)

Next i installed the Suricata through the plugins in OPNsense and configure and enabled the service then under Services > Intrusion Detection > Alerts tab find the Event ID you want to enable and set to block

![image](https://github.com/jasnnh/OPNsense_IDS-IPS-Suricata/blob/main/1.PNG)

![image](https://github.com/jasnnh/OPNsense_IDS-IPS-Suricata/blob/main/image3.png)


