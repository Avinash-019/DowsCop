# 🕵️‍♂️ DowsCop — Windows Forensic Artifact Collector

DowsCop is a modular Windows-based digital forensics tool designed to automate the collection and analysis of critical system artifacts. It generates structured JSON outputs and detailed PDF reports to support digital investigations, incident response, and security analysis.

---

## 🚀 Features

* 🔹 Modular architecture (12 forensic collectors)
* 🔹 System & hardware information collection
* 🔹 User accounts and privilege enumeration
* 🔹 Network artifacts (active connections, ports, ARP cache)
* 🔹 Registry analysis (autoruns, persistence mechanisms)
* 🔹 Event log extraction (Security, System, PowerShell, Defender)
* 🔹 Browser artifacts (history, downloads, login traces)
* 🔹 Prefetch, ShimCache, and Amcache analysis
* 🔹 USB device history tracking
* 🔹 File system artifact collection
* 🔹 Memory artifact collection
* 🔹 Artifact hashing for integrity verification
* 🔹 Automatic PDF report generation
* 🔹 Structured JSON output for further analysis

---

## 📂 Output

After execution, the tool generates:

* 📁 **Raw Artifacts Folder**

  * Contains all collected data in structured format
* 📄 **PDF Report**

  * Human-readable forensic report
* 🧾 **JSON Files**

  * Machine-readable data for analysis or SIEM integration

---

## ⚙️ How It Works

1. Performs privilege check
2. Creates a case directory
3. Executes multiple forensic collection modules
4. Collects artifacts from different system layers
5. Computes hashes for collected data
6. Generates structured outputs (JSON + PDF)

---

## 🧪 Modules Included

* System Information
* Users & Accounts
* Network Artifacts
* Process Artifacts
* Registry Artifacts
* Event Logs
* Browser Artifacts
* Prefetch / ShimCache / Amcache
* Persistence Mechanisms
* File System Artifacts
* Memory Artifacts
* USB Device History

---

## ▶️ Usage

```bash
python main.py
```

> ⚠️ Run with administrator privileges for complete artifact collection.

---

## ⚠️ Notes

* Some artifacts may not be accessible due to permission restrictions
* Certain logs (e.g., Sysmon) may not be available if not configured on the system
* Results may vary depending on system configuration and user privileges

---

## 🎯 Use Cases

* Digital forensic investigations
* Incident response
* System auditing
* Security research

---

## 🔐 Disclaimer

This tool is intended for educational and authorized forensic investigations only. Do not use it on systems without proper permission.

---

## 👨‍💻 Author

**Avinash Prajapati**

---

## ⭐ Contribution

Contributions, issues, and feature requests are welcome.
