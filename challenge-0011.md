# Challenge 0011

> **IP ADDRESS:** 10.10.0.3
>
> **OPERATING SYSTEM**: Windows Server 2008 R2

---

## Tools Used:

* NMAP

## Threat Description:

## Methodology:

### NMAP

```ruby
nmap -sS -sU -T4 -A -v -PE -PP -PS80,443 -PA3389 -PU40125 -PY -g 10.10.0.3
```

### NIKTO

![](/assets/0011_NIKTO_01.png)

### CHECK SOURCE CODE

![](/assets/0011_SOURCECODE_01.png)

### METASPLOIT

![](/assets/0011_METASPLOIT_01.png)

## ![](/assets/0011_METASPLOIT_02.png)

![](/assets/0011_METASPLOIT_03.png)

![](/assets/0011_METASPLOIT_04.png)

![](/assets/0011_METASPLOIT_05.png)

![](/assets/0011_METASPLOIT_06.png)

![](/assets/0011_METASPLOIT_07.png)

## Recommendations:



