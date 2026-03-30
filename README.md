
# 🧩 The Open Source Audit — Python

The project aims to analyze **Python** as an open-source software — covering its **origin, licensing, ethics, Linux integration, ecosystem, and comparison with proprietary alternatives**.  
It also includes **five shell scripts** demonstrating practical open-source automation on Linux.

---

## 🧠 Why Python Was Chosen
- Community-driven development, not controlled by a single corporation.  
- Educational and research significance — used globally in web, AI, and automation.  
- Licensed under the **PSF License**, enabling deep insight into permissive open-source models.  
- A prime example of how **collaboration fuels innovation.**

---

## 🏗️ Project Structure

| Folder/File | Description |
|--------------|-------------|
| `oss-audit - 24BCY10344.pdf` | Full project report |
| `scripts/script1_system_identity.sh` | Displays system identity report |
| `scripts/script2_package_inspector.sh` | Checks installation and license info for FOSS packages |
| `scripts/script3_disk_permission_auditor.sh` | Audits key system directories |
| `scripts/script4_logfile_analyzer.sh` | Searches for errors in log files |
| `scripts/script5_manifesto_generator.sh` | Generates a personal open-source manifesto |
| `README.md` | Project documentation (you are here) |

---

## 🧩 Project Parts Summary

### 🏁 Part A — Origin and Philosophy
- Created by **Guido van Rossum (1989)** to make programming simpler than C and more open than ABC.  
- Licensed under the **Python Software Foundation (PSF) License** — permissive, BSD/MIT-style.  
- Explores philosophical and ethical aspects of open source.

### 🐧 Part B — Linux Footprint
- Python comes pre-installed in many Linux distributions (e.g., Ubuntu).  
- Located typically at `/usr/bin/python3`.  
- Updates and patches delivered via community-maintained repositories.  
- Demonstrates system commands for version checking, path verification, and service management.

### 🌍 Part C — FOSS Ecosystem
- Python relies on **C and GCC** and inspires frameworks like Django, Flask, Pandas, NumPy, TensorFlow, etc.  
- Supported and governed by the **Python Software Foundation** and its Steering Council.  
- Connected through mailing lists, forums, IRC channels, and large global conferences like **PyCon**.

### ⚖️ Part D — Open Source vs Proprietary
| Aspect | Python (Open Source) | MATLAB (Proprietary) |
|--------|----------------------|----------------------|
| Cost | Free | Paid |
| Openness | Source visible to all | Closed source |
| Support | Community-driven | Vendor-based |
| Control | PSF (community) | MathWorks |
| Verdict | Great for AI, web, education | Great for specific engineering uses |

---

## 💻 Shell Script Highlights

Each script demonstrates Linux automation concepts — loops, variables, conditionals, logs, text parsing, and philosophy reflection.

| Script | Purpose |
|---------|----------|
| `system_identity.sh` | Displays OS info, kernel, and uptime |
| `package_inspector.sh` | Checks if `python3` or another FOSS package is installed |
| `disk_permission_auditor.sh` | Lists permissions and sizes of key directories |
| `logfile_analyzer.sh` | Detects errors or warnings in log files |
| `manifesto_generator.sh` | Generates a personal open-source manifesto automatically |

---

## ⚙️ How to Run the Scripts

Clone this repository and run scripts as follows:

```bash
git clone [github.com](https://github.com/)<your-username>/open-source-audit-python.git
cd open-source-audit-python/scripts

# Make scripts executable
chmod +x *.sh

# Run an individual script
./script1_system_identity.sh
