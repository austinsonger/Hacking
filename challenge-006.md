# Challenge 006

> **IP ADDRESS:** 172.17.0.2
>
> **OPERATING SYSTEM:** Windows Server 2008 R2

---

## Tools Used:

* NMAP

## Threat Description:

## Methodology:

### NMAP

```
nmap -sS -sU -T4 -A -v -PE -PP -PS80,443 -PA3389 -PU40125 -PY -g 172.17.0.2
```



### NIKTO

![](/assets/006.NIKTO.png)

### SQL INJECTION

![](/assets/006.SQL.01.png)



![](/assets/006.SQL.03.png)

### XSS IN COMMENT SECTION

![](/assets/006.XSS.01.png)

![](/assets/006.XSS.02.png)





## Recommendations:



