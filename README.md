```
> seedon@osint:~$ whoami
```
**OSINT Researcher** | **Shodan Query Specialist**

```
> seedon@osint:~$ cat shodan-aio.txt
```
🔍 **Comprehensive Shodan Search Filter Reference**  
📍 Geographic targeting capabilities  
🌐 Network infrastructure enumeration  
🛡️ Vulnerability discovery filters  
📊 Organized by category for quick reference  
⚡ Advanced query combinations & operators

```
> seedon@osint:~$ ls categories/
```
📍 `physical-location/`   - Country, city, GPS coordinates  
🖥️ `ip-subnets/`         - IP ranges, ASN, ISP targeting  
⚙️ `products-os/`        - Software versions, OS detection  
🌐 `web-applications/`   - HTTP headers, SSL certs, components  
🔧 `misc/`               - Timestamps, vulnerabilities, screenshots

```
> seedon@osint:~$ ./quick-examples.sh
```

**Basic Targeting:**
```bash
country:"US" + port:"443"              # US HTTPS servers
city:"Bengaluru" + org:"*"            # Corporate infrastructure in Bengaluru
geo:"40.759487,-73.978356,2"          # GPS coordinates with 2km radius
```

**Vulnerability Hunting:**
```bash
product:"nginx" + vuln:"CVE-*"        # Vulnerable nginx instances
ssl.cert.expired:"true"               # Expired SSL certificates
has_screenshot:"true" + port:"3389"   # RDP with screenshots
```

**Network Reconnaissance:**
```bash
net:"192.168.1.0/24"                  # Specific subnet scanning
ASN:"AS8075" + port:"22"              # SSH on specific ASN
org:"Microsoft" + product:"IIS"       # Microsoft IIS servers
```

```
> seedon@osint:~$ cat advanced-operators.txt
```

**Search Operators:**
- `+` Include results (AND)
- `-` Exclude results (NOT)  
- `""` Exact phrase matching
- `*` Wildcard matching

**Example Combinations:**
```bash
+"webcam" -"login"                     # Webcams without login pages
product:"Apache" version:"2.4.*"      # Apache 2.4.x versions
title:"Index of /" + port:"80"        # Directory listings on HTTP
```

```
> seedon@osint:~$ contact --help
```
📧 [LinkedIn](https://www.linkedin.com/in/seedon) • [Twitter/X](https://x.com/SeedonD)  
💡 **Perfect for:** OSINT investigations, threat hunting, infrastructure enumeration  
🎯 **Use cases:** Red team reconnaissance, bug bounty research, security assessments

---

## 📋 Complete Filter Reference

### 📍 Physical Location

| Filter | Description | Usage Example |
|--------|-------------|---------------|
| `country` | Search by country code | `country:"IN"` |
| `city` | Search by city name | `city:"Bengaluru"` |
| `state` | Search by state code (US only) | `state:"NY"` |
| `region` | Same as state filter | `region:"NY"` |
| `postal` | Search by zip code | `postal:"92127"` |
| `geo` | Search by GPS coordinates | `geo:"40.759487,-73.978356"` |
| `geo` | GPS with radius (km) | `geo:"40.759487,-73.978356,2"` |
| `org` | Search by Organization/Company | `org:"Microsoft"` |

### 🖥️ IP Addresses & Subnets

| Filter | Description | Usage Example |
|--------|-------------|---------------|
| IP | Search findings on a single IP | `52.179.197.205` |
| `hostname` | Search for string in any hostname | `hostname:"microsoft.com"` |
| `net` | Search across a specific subnet range | `net:"52.179.197.0/24"` |
| `port` | Find instances where a specific port is open | `port:"445"` |
| `isp` | Search by ISP Name | `isp:"BSNL"` |
| `ASN` | Search by Autonomous System Number | `ASN:"AS8075"` |
| `org` | Search by Organization/Company | `org:"Microsoft"` |

### ⚙️ Products & Operating Systems

| Filter | Description | Usage Example |
|--------|-------------|---------------|
| `os` | Search by operating system type | `os:"Windows Server 2008"` |
| `org` | Search by Organization/Company | `org:"Xiaomi"` |
| `product` | Search by known product name | `product:"Cisco C3550 Router"` |
| `version` | Used with product for specific versions | `product:"nginx" version:"1.8.1"` |
| `category` | Search by Shodan category | `category:"ics"` |
| `smb` | Search for specific SMB server | `smb:"2"` |

### 🌐 Web Applications

| Filter | Description | Usage Example |
|--------|-------------|---------------|
| `title` | Search for text in page title | `title:"Index of /ftp"` |
| `html` | Search for strings in webpage's body | `html:"XML-RPC server accepts"` |
| `http.component` | Search for a specific web technology | `http.component:"php"` |
| `ssl.version` | Search for SSL/TLS versions supported | `ssl.version:"tlsv1.1"` |
| `ssl.cert.expired` | Search for expired HTTPS certs | `ssl.cert.expired:"true"` |

### 🔧 Miscellaneous

| Filter | Description | Usage Example |
|--------|-------------|---------------|
| `after` | Search for findings after a specific date | `after:"01/01/19"` |
| `before` | Search for findings before a specific date | `before:"01/01/19"` |
| `has_screenshot` | Search for results which have a screenshot | `has_screenshot:"true"` |
| `vuln` | Search possible vulnerable devices by CVE ID | `vuln:"CVE-2017-0143"` |
| `tag` | Search based on shodan tagged data | `tag:"honeypot"` |

---

## 🎯 Practical OSINT Workflows

### 🏢 Corporate Infrastructure Assessment
```bash
# Step 1: Find the organization's ASN
org:"Target Company"

# Step 2: Enumerate their IP space  
ASN:"AS12345"

# Step 3: Identify web services
ASN:"AS12345" + port:"80,443"

# Step 4: Look for admin interfaces
ASN:"AS12345" + title:"admin" + port:"443"
```

### 🔍 Vulnerability Research
```bash
# Step 1: Target specific technology
product:"Apache" version:"2.4.49"

# Step 2: Add geographic scope
product:"Apache" version:"2.4.49" + country:"US"

# Step 3: Look for exposed admin panels
product:"Apache" + title:"server-info" + country:"US"
```

### 🌍 Geographic Threat Hunting
```bash
# Step 1: Define geographic area
city:"London" + country:"GB"

# Step 2: Look for exposed services
city:"London" + port:"3389,22,23"

# Step 3: Identify vulnerable systems
city:"London" + vuln:"CVE-2021-44228"
```

---

## 📚 Additional Resources

- 📖 **Reference:** [Shodan QuickStart v1](https://www.uk-osint.net/documents/Shodan_QuickStart_v1.pdf)
- 🔧 **Shodan CLI:** Official command-line interface for automation
- 📊 **Shodan API:** Programmatic access for large-scale queries
- 🎓 **Learning:** Practice with shodan.io/explore for interesting queries

---

*Work in progress - contributions welcome via pull requests!*
