<!-- Header banner -->

<p align="center">
  🇬🇧 English · <a href="README.fr.md">🇫🇷 Français</a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Shyber&fontSize=44&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Detect%20%C2%B7%20Analyse%20%C2%B7%20Respond%20%C2%B7%20Secure&descAlignY=58&descSize=18" alt="Cybersecurity student banner" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=22D3EE&center=true&vCenter=true&width=640&lines=Hi+there!+%F0%9F%91%8B;Curious+about+every+side+of+security;Learning+something+new+every+day;SOC+%C2%B7+Network+Security+%C2%B7+GRC+%26+Compliance" alt="Typing animation" />
</p>

---

## 👋 Hi there

I'm **Shyber**, a **cybersecurity engineering student**. Security is the field I chose, and I work on it all the time: labs, network builds, incident write-ups and team projects. What keeps me going is understanding how an attack really unfolds, and then how to spot it, stop it and explain it clearly.

My main focus is the **Blue Team**: **SOC and detection**, **risk and compliance**, **network security**, **cloud security**, **incident response** and **vulnerability management**.

And I enjoy the **offensive** side too. I'm learning it step by step through labs and CTF challenges, because knowing how attackers think makes me a better defender.

---

## 🎯 Areas of interest

<table align="center">
  <tr>
    <td align="center" width="20%">
      <h3>🛡️</h3>
      <b>SOC & Detection</b><br>
      <sub>Log analysis, SIEM queries, intrusion detection rules</sub>
    </td>
    <td align="center" width="20%">
      <h3>🚨</h3>
      <b>Incident Response</b><br>
      <sub>Investigation, playbooks, clear incident reports</sub>
    </td>
    <td align="center" width="20%">
      <h3>🌐</h3>
      <b>Network Security</b><br>
      <sub>Traffic analysis, firewalls, segmentation, hardening</sub>
    </td>
    <td align="center" width="20%">
      <h3>☁️</h3>
      <b>Cloud Security</b><br>
      <sub>Cloud workloads, containers, logging and access</sub>
    </td>
    <td align="center" width="20%">
      <h3>📋</h3>
      <b>Risk & Compliance</b><br>
      <sub>Security audits, NIST CSF, GDPR, PCI DSS</sub>
    </td>
  </tr>
</table>

---

## 🧰 Toolbox

**Detection & analysis**

<p>
  <img src="assets/badges/splunk.svg" alt="Splunk">
  <img src="assets/badges/google-chronicle.svg" alt="Google Chronicle">
  <img src="assets/badges/suricata.svg" alt="Suricata">
  <img src="assets/badges/wireshark.svg" alt="Wireshark">
  <img src="assets/badges/tcpdump.svg" alt="tcpdump">
  <img src="assets/badges/virustotal.svg" alt="VirusTotal">
</p>

**Networking**

<p>
  <img src="assets/badges/cisco.svg" alt="Cisco">
  <img src="assets/badges/gns3.svg" alt="GNS3">
  <img src="assets/badges/eve-ng.svg" alt="EVE-NG">
  <img src="assets/badges/bgp-mpls-ospf.svg" alt="BGP MPLS OSPF">
  <img src="assets/badges/vlan-vrf.svg" alt="VLAN VRF">
</p>

**Cloud & systems**

<p>
  <img src="assets/badges/google-cloud.svg" alt="Google Cloud">
  <img src="assets/badges/docker.svg" alt="Docker">
  <img src="assets/badges/proxmox.svg" alt="Proxmox">
  <img src="assets/badges/linux.svg" alt="Linux">
  <img src="assets/badges/github-actions.svg" alt="GitHub Actions">
  <img src="assets/badges/gitlab.svg" alt="GitLab">
</p>

**Programming**

<p>
  <img src="assets/badges/python.svg" alt="Python">
  <img src="assets/badges/go.svg" alt="Go">
  <img src="assets/badges/c.svg" alt="C">
  <img src="assets/badges/bash.svg" alt="Bash">
  <img src="assets/badges/sql.svg" alt="SQL">
  <img src="assets/badges/mongodb.svg" alt="MongoDB">
</p>

---

## 🔬 Projects I've worked on

<details open>
<summary><b>🛡️ Detection & incident analysis</b></summary>
<br>

| Project | What I did | Tools |
|---|---|---|
| **SYN flood analysis** | Analysed a TCP capture, traced the attack to an external IP, measured the impact on legitimate clients and wrote an incident report. | `Wireshark` `TCP` |
| **DDoS on a DNS server** | Analysed the captured packets, documented the incident and proposed remediation. | `tcpdump` |
| **Spear phishing investigation** | Spotted the indicators (spoofed domain, spelling errors, credential-harvesting URL), checked a suspicious file hash and followed a response playbook. | `VirusTotal` `Playbook` |
| **Custom detection rules** | Wrote my own rules, ran packet captures through them and analysed the logs they produced. | `Suricata` |
| **Log investigation** | Searched and correlated security events with two different query languages. | `Splunk (SPL)` `Chronicle (YARA-L)` |
| **SOC lab** | Team project, which we keep growing by combining several of our projects. We built a monitored network (a SIEM, a firewall, Windows and Linux endpoints, vulnerable targets, an attacker machine and a cloud part), and we research and test attack scenarios to see how each one gets detected. We learn as we go and share what each of us finds: every idea is welcome. | `Wazuh` `pfSense` `Sysmon` `Kali Linux` `DVWA` `Metasploitable 2` `Docker` `Portainer` `Ubuntu Server` `Windows` `Google Cloud` |

</details>

<details open>
<summary><b>🌐 Networks & network security</b></summary>
<br>

| Project | What I did | Tools |
|---|---|---|
| **Secure 3-tier network** | Designed a full campus architecture with two Internet links: routing at the edge, redundancy in the core and distribution, segmented VLANs at access. | `BGP` `OSPF` `VRRP` `NAT` |
| **Device hardening** | Locked down switches and routers: port security, BPDU Guard, ACLs, SSH limited to strong ciphers, encrypted passwords. | `Cisco IOS` |
| **MPLS VPN** | Built a provider network where two customers share the same routers without ever seeing each other's traffic. | `MPLS` `MP-BGP` `VRF` |
| **VRF-Lite** | One topology, many routing variants (static, RIP, OSPF, EIGRP, BGP, IS-IS, IPv4/IPv6), plus inter-VRF routing. | `VRF` `IPv6` |

</details>

<details open>
<summary><b>☁️ Cloud & DevOps</b></summary>
<br>

| Project | What I did | Tools |
|---|---|---|
| **Task scheduling on cloud VMs** | Wrote a branch and bound scheduler to spread tasks over several cloud VMs. It finished about 22% faster than Round-Robin. | `Go` `Google Cloud` |
| **CI pipeline for an API** | Team project: a small web API with a pipeline that runs linting, automated tests and a coverage report on every push. | `GitHub Actions` `Node.js` |

</details>

<details open>
<summary><b>⚙️ Systems & data</b></summary>
<br>

| Project | What I did | Tools |
|---|---|---|
| **Low-level systems programming** | Processes, threads, memory management, synchronisation and inter-process communication. | `C` `Linux` |
| **Custom Linux-based OS** | Team project: built an operating system from a Linux distribution and the Linux kernel, adapted to our needs. | `Linux` |
| **Crowdfunding database** | Team project: from the client's brief to a working database and a Python app to use it, in a relational and a NoSQL version. | `SQL` `MongoDB` `Python` `PlantUML` |
| **Fraud detection (ML)** | Trained models on a highly imbalanced dataset, where the cases that matter are rare. | `Python` `scikit-learn` |

</details>

<details open>
<summary><b>📋 Risk & compliance</b></summary>
<br>

| Project | What I did | Frameworks |
|---|---|---|
| **Internal security audit (fictional company)** | Assessed compliance, completed a controls checklist from the risk assessment and wrote recommendations. | `NIST CSF` `GDPR` `PCI DSS` `SOC 1 & 2` |

</details>

---

## 🔄 How I think about an incident

```mermaid
flowchart LR
    A([🔍 Detect]) --> B([⚖️ Triage])
    B --> C([🧪 Analyse])
    C --> D([🧱 Contain])
    D --> E([📝 Report])
    E --> F([📈 Improve])
    F -.-> A
```

A good report matters as much as the analysis: it lets someone else understand what happened and act on it quickly.

---

## 🏅 Certifications

<p>
  <img src="assets/badges/google-cybersecurity-professional-certificate.svg" alt="Google Cybersecurity Professional Certificate">
  <img src="assets/badges/cisco-ccna-courses-1-3.svg" alt="CCNA courses 1 to 3">
</p>

---

## 🌱 On my radar

- ☁️ Cloud security: securing cloud workloads and containers, and bringing cloud logs into our SOC lab
- 🧪 Adding new scenarios to our SOC lab and publishing a write-up for each one
- 🎯 Detection engineering: writing and tuning rules, mapping them to MITRE ATT&CK
- 🚩 More hands-on labs and capture-the-flag challenges
- 🤖 Cybersecurity and AI

---

<p align="center">
  <i>"Curious by nature, careful by habit."</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" alt="footer" />
</p>
