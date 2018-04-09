# Challenge 004

> **IP ADDRESS**: 172.17.0.3
>
> **OPERATING SYSTEM:** Linux CentOS 6.4

---

## Tools Used:

* NMAP
* HYDRA

## Threat Description:

## Methodology:

### NMAP

```ruby
nmap -sS -sU -T4 -A -v -PE -PP -PS80,443 -PA3389 -PU40125 -PY -g 172.17.0.3
```

### HYDRA

![](/assets/04_HYDRA_01.png)

### NCRACK

![](/assets/004_NCRACK_01.png)

![](/assets/004_SCP.png)

### HASH FILE

![](/assets/Hash.png)

## Recommendations:



