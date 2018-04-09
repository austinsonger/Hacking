# Challenge 009

> **IP ADDRESS:** 10.10.0.2
>
> **OPERATING SYSTEM**: Windows Server 2008 R2

---

## Tools Used:

* NMAP

## Threat Description:

## Methodology:

### NMAP

```ruby
nmap -sS -sU -T4 -A -v -PE -PP -PS80,443 -PA3389 -PU40125 -PY -g 10.10.0.2
```

### NIKTO

![](/assets/009_NIKTO_01.png)

### BURP SUITE

![](/assets/009_BURPSUITE_01.png)

![](/assets/009_BURPSUITE_02.png)

![](/assets/009_BURPSUITE_03.png)

![](/assets/009_BURPSUITE_04.png)

#### Edit URL to include in scope

![](/assets/009_BURPSUITE_06.png)

#### Forwarded the page until the viewstate appeared

![](/assets/009_BURPSUITE_07.png)

### SQLMAP

![](/assets/009_SQLMAP_02.png)

![](/assets/009_SQLMAP_03.png)

![](/assets/009_SQLMAP_04.png)

> **The database version is showed above**
>
> * Microsoft SQL Server 2005

![](/assets/009_SQLMAP_01.png)

![](/assets/009_SQLMAP_07.png)

![](/assets/009_SQLMAP_08.png)

![](/assets/009_SQLMAP_011.png)



#### User Smith 



![](/assets/009_SQLMAP_09.png)

![](/assets/009_SQLMAP_013.png)

#### ![](/assets/009_SQLMAP_010.png)



#### Extract Xsecurity Table

#### ![](/assets/009_SQLMAP_010.png)

#### ![](/assets/009_SQLMAP_014.png)

## Recommendations:



