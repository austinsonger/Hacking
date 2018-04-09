# Challenge 008

> **IP ADDRESS:** 172.19.19.3
>
> **OPERATING SYSTEM:** Windows Server 2008 R2

---

## Tools Used:

* NMAP

## Threat Description:

## Methodology:

### NMAP

```ruby
nmap -sS -sU -T4 -A -v -PE -PP -PS80,443 -PA3389 -PU40125 -PY -g 172.19.19.3
```

### HPING3

![](/assets/008_HPING3_01.png)

### 

### HYDRA

## ![](/assets/008_HYDRA_01.png)

### 

### CAIN AND ABEL ON WINDOWS

![](/assets/008_CAIN&ABEL_01.png)

![](/assets/008_CAIN&ABEL_02.png)

![](/assets/008_CAIN&ABEL_03.png)

![](/assets/008_CAIN&ABEL_04.png)

![](/assets/008_CAIN&ABEL_05.png)

#### Extraction of Active Directory Users

> Used the following command line to extract the active directory admin users to desktop

```ruby
CSVDE -f aduser.csv
```

![](/assets/008_CAIN&ABEL_06.png)

### METASPLOIT

![](/assets/008_METASPLOIT_01.png)![](/assets/008_METASPLOIT_02.png)

![](/assets/008_METASPLOIT_03.png)

![](/assets/008_METASPLOIT_04.png)

![](/assets/008_METASPLOIT_05.png)

![](/assets/008_METASPLOIT_06.png)

![](/assets/008_METASPLOIT_07.png)![](/assets/008_METASPLOIT_08.png)

#### NAVIGATE THROUGH SHELL

![](/assets/008_METERPRETER_01.png)

##### DOWNLOAD

> Download the aduser.csv from meterpreter

![](/assets/008_METERPRETER_02.png)

## Recommendations:



