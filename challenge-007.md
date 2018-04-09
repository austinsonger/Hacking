# Challenge 007

> **IP ADDRESS:** 172.19.19.6
>
> **OPERATING SYSTEM:** Windows Server 2012

---

## Tools Used:

* NMAP
* WPSCAN
* METASPLOIT

## Threat Description:

ECSA Website has a content management system vulnerability. The Inboundio Marketing plugin is susceptible to attackers being able to upload arbitrary files, because the application is unable to sanitize user-supplied input. An attacker could exploit the vulnerability of uploading arbitrary code and run it in the context of the webserver process.

## Methodology:

### NMAP

```
nmap -sS -sU -T4 -A -v -PE -PP -PS80,443 -PA3389 -PU40125 -PY -g 172.19.19.6
```

### VIST SITE IN BROWSER

![](/assets/007_BROWSER_01.png)

### WPSCAN

![](/assets/006.WPSCAN.01.png)

![](/assets/007_WPSCAN_02.png)





![](/assets/006.WPSCAN.02.png)

### METASPLOIT

![](/assets/007_METASPLOIT_01.png)![](/assets/007_METASPLOIT_02.png)

![](/assets/007_METASPLOIT_03.png)![](/assets/007_METASPLOIT_04.png)

![](/assets/007_METASPLOIT_05.png)![](/assets/007_METASPLOIT_06.png)

![](/assets/007_METASPLOIT_07.png)![](/assets/007_METASPLOIT_08.png)

#### ENTER METERPRETER SESSION

![](/assets/007_METASPLOIT_09.png)![](/assets/007_METASPLOIT_010.png)

![](/assets/007_METASPLOIT_011)

![](/assets/007_METASPLOIT_012.png)

#### DOWNLOAD AND HASHFILE

![](/assets/007_METASPLOIT_013.png)

![](/assets/007_METASPLOIT_015.png)

## Recommendations:



