A cross-platform Java tool to detect critical CPU vulnerabilities like **Meltdown** and **Spectre** with improved logic and accuracy.
## 🔍 Features

- ✅ Supports both **Linux** and **Windows**
- ✅ Detects **Meltdown**, **Spectre v2**
- ✅ Uses **PowerShell** for Windows mitigation checks
- ✅ Analyzes `/proc`, `/sys`, `dmesg`, and kernel configs on Linux
- ✅ Displays clear vulnerability status and mitigation presence
- ✅ Provides **confidence scores** and **detailed logging**
- ✅ Useful for **academic**, **research**, and **enterprise** use

---

## 🚀 How to Run

### ✅ Prerequisites

- Java 8 or higher
- For Windows: PowerShell v5+
- For Linux: Access to `/proc`, `/sys`, and kernel logs (`dmesg`)

### 🔧 Compile & Run

#### On Linux:
```bash
javac VulnerabilityDetector_Final.java
java VulnerabilityDetector
