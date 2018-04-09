# Challenge 003

> **IP ADDRESS: **172.19.19.5
>
> **OPERATING SYSTEM:** Linux Ubuntu

---

## Tools Used:

* NMAP
* NIKTO
* DIRBUSTER

## Threat Description:

## Methodology:

### NMAP

```
nmap -sS -sU -T4 -A -v -PE -PP -PS80,443 -PA3389 -PU40125 -PY -g 172.19.19.5
```

![](/assets/003_NMAP_Shellshock_1.png)

![](/assets/003_NMAP_Shellshock_02.png)

### DIRBUSTER

![](/assets/003_DIRBUSTER_01.png)

![](/assets/003_DIRBUSTER_03.png)

### METASPLOIT

![](/assets/004_METASPLOIT_01.png)



![](/assets/004_METASPLOIT_02.png)

![](/assets/004_METASPLOIT_03.png)

![](/assets/004_METASPLOIT_04.png)



![](/assets/004_METASPLOIT_05.png)

## Recommendations:



