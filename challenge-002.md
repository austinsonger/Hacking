# Challenge 002

> **IP ADDRESS:** 172.19.19.8
>
> **OPERATING SYSTEM: **Windows XP

---

## Tools Used:

* NMAP
* HPING3
* HYDRA
* METASPLOIT

## Threat Description:

FNB management has discovered one of their employees has transferred sensitive information outside the organization using their machine. The network admin tried to ascertain this but could not find anything concrete. He however did discover some large images in a folder named Personal. This was in violation to the organization’s policy of not storing any personal information on office computers. As a penetration tester, your task is to verify if these images were used to send sensitive information and present the hidden message in the pen testing report.

## Methodology:

### NMAP

```py
nmap -sS -sU -T4 -A -v -PE -PP -PS80,443 -PA3389 -PU40125 -PY -g 172.19.19.8
```

### HPING3

### HYDRA

![](/assets/002_Hydra_1.png)

![](/assets/002_Hydra_02.png)

### METASPLOIT

![](/assets/002_Metasploit_1.png)

![](/assets/002_Metasploit_02.png)

![](/assets/002_METASPLOIT_03.png)

![](/assets/002_METASPLOIT_04.png)

![](/assets/002_METASPLOIT_5.png)

![](/assets/002_METASPLOIT_05.png)

![](/assets/002_METASPLOIT_7.png)

![](/assets/002_METASPLOIT_09.png)

#### QUICKSTEGO

![](/assets/002_Q_01.png)

![](/assets/002_Q_02.png)

![](/assets/002_Q_03.png)

![](/assets/002_Q_04.png)

![](/assets/002_Q_05.png)

![](/assets/002_Q_06.png)

## Recommendations:



