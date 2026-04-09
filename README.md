## 2. Install Git CLI

### Windows -- upload with ssh 

**Option A winget (Windows 10/11, recommended)**
```powershell
winget install --id Git.Git -e --source winget
```

**Option B Direct installer**
1. Download from **[https://git-scm.com/download/win](https://git-scm.com/download/win)**
2. Run the installer
3. Recommended settings to change from defaults:

**Verify (PowerShell or Git Bash):**
```powershell
git --version
# git version 2.45.2.windows.1
```

> **WSL (Windows Subsystem for Linux):** If you use Ubuntu on WSL, follow the Linux section below inside your WSL terminal.

---
