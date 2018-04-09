# Challenge 001

---

## Tools Used:

* NMAP

## Threat Description:

Information gathering provides an indicator of the amount of organizational information available in the public domain that could help an attacker compromise the network. We obtained Internet Protocol \(IP\) address blocks assigned to the organization and queried for other indications of IP address ownership.

The purpose of scanning is to discover exploitable communication channels, probe as many listeners as possible, and keep track of the ones that are responsive or useful to an attacker’s particular needs. In the scanning phase of an attack, the attacker tries to find various ways to intrude into a target system. The attacker also tries to discover more about the target system by finding out what operating system is used, what services are running, and whether or not there are any configuration lapses in the target system. The attacker then tries to form an attack strategy based on facts learned during the scan.

## Methodology:

### NMAP

![](/assets/List_of_IP_Addresses.png)

**NMAP Command**

```
nmap -sS -sU -T$ -A -v -iL list.txt
```

![](/assets/NMAP_All_IP_Addresses.png)

> This NMAP command reads off of the list of IP addresses included in the Pentest. This allows me of running NMAP once instead of multiple times throughout the pentesting process.

The results took a long time.

### NETDISCOVER

## Routing IP Addresses

### ![](/assets/Routing IP Addresses.png)System IP Addresses

| IP Addresses | Operating System | Ports Open |
| :--- | :--- | :--- |
| 10.0.0.2 |  |  |
| 10.0.0.3 |  |  |
| 10.0.0.4 |  |  |
| 10.10.0.2 |  |  |
| 10.10.0.3 |  |  |
| 172.19.19.2 |  |  |
| 172.19.19.3 |  |  |
| 172.19.19.4 |  |  |
| 172.19.19.5 |  |  |
| 172.19.19.6 |  |  |
| 172.19.19.7 |  |  |
| 172.19.19.8 |  |  |
| 172.19.19.9 |  |  |
| 172.19.19.10 |  |  |

### Services Running

| IP Address | Services Running |
| :--- | :--- |
|  |  |

After discovering live systems, we started port scanning to detect the open ports and identify the services running on these hosts. Port scanning is the process of checking the services running on the target computer by sending a sequence of messages in an attempt to break in. Port scanning involves connecting to or probing TCP and UDP ports on the target system to determine if the services are running or are in a listening state. The listening state gives an idea of the operating system and the application in use. Sometimes, active services that are listening may allow unauthorized user access to systems that are misconfigured or running software that has vulnerabilities.

## Recommendations:



