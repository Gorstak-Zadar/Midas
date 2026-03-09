# 🛡️ Midas

> PowerShell **FileSystemWatcher** that locks down permissions on new/changed `.exe` files in Users, Program Files — Console Logon (S-1-2-1) only.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 📂 **Paths** | `C:\Users\`, `C:\Program Files\`, `C:\Program Files (x86)\` |
| 🔍 **Filter** | `*.exe` only |
| 🔒 **takeown + icacls** | Grants full control to S-1-2-1 (Console Logon) only |
| 📝 **Logging** | `%windir%\Temp\MidasLog.txt` |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **Privileges** | Administrator |

---

## 🚀 Usage

```powershell
.\Midas.ps1
```

---

<p align="center">
  <sub>🛡️ Gorstak Security Hardening</sub>
</p>
