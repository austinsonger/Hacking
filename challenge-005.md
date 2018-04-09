# Challenge 005

> **IP ADDRESS:** 172.19.19.2
>
> **OPERATING SYSTEM:** Windows 7 Ultimate

---

## Tools Used:

* NMAP

## Threat Description:

## Methodology:

### NMAP

```ruby
nmap -sS -sU -T4 -A -v -PE -PP -PS80,443 -PA3389 -PU40125 -PY -g 172.19.19.2
```

### HPING3

```
hping3 --scan 1-1000 -S 172.19.19.2
```

![](/assets/005_HPING3_01.png)

### NIKTO

![](/assets/005_NIKTO.png)

### VISIT IP ADDRESS IN BROWSER

![](/assets/VISIT IP IN BROWSER.png)

### HYDRA

![](/assets/005_HYDRA.png)

### METASPLOIT

```
msf > search windows/ssh/freesshd_authbypass
```

![](/assets/005.METASPLOIT.png)

![](/assets/005_METASPLOIT_SET.png)

![](/assets/005.METASPLOIT.02.png)

![](/assets/005_METASPLOIT_HASHDUMP_X.png)

![](/assets/005.METASPLOIT.03.png)

![](/assets/005.METASPLOIT.04.png)

![](/assets/005.METASPLOIT.06.png)

![](/assets/005.METASPLOIT.07.png)

### REMOTE DESKTOP

![](/assets/005_RDESKTOP_01.png)

![](/assets/005_RDESKTOP_02.png)

## Recommendations:



