# [CVE-2024-24488](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2024-24488)
An issue in Shenzen Tenda Technology CP3V2.0 V11.10.00.2311090948 allows a local attacker to obtain sensitive information via the password component.

# Tested Versions
CP3V2.0 - V11.10.00.2311090948

# CWE
CWE-313: Cleartext Storage in a File or on Disk

## Vulnerability Overview

Devices affected by this vulnerability can access the passwords of WiFi routers they are connected to through a specific file path. The path in question contains a file where sensitive information, including the WiFi router's password, is stored in plaintext.

### Vulnerable File Path

The sensitive information can be found at:

```/app/userdata/ifcfg.wlan0```


