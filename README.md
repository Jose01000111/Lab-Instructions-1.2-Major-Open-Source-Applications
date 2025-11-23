## 🛠️Lab Instructions — 1.2 Major Open Source Applications

>💬 **Tip:** Paste this study guide into ChatGPT and ask for **more instructions** by specifying:  
>- “Provide step-by-step lab instructions for this objective.”  
>- “Include which Linux distro to use (Debian/Ubuntu or RHEL/Fedora).”  
>- “Show examples of installing, verifying, and managing desktop and server applications.”  
>- “Include minimal command-line practice for package management and development tools.”  
>- “Focus only on what is most important for passing the LPI Linux Essentials exam.”  

>This will prompt ChatGPT to give **practical, exam-focused lab steps** for each section.


## 🛠️ Quick Lab Instructions — 1.2 Major Open Source Applications

### 1️⃣ Prepare Your System
- **Choose your distro**:
  - Debian/Ubuntu → APT-based practice  
  - RHEL/Fedora/CentOS → RPM/YUM/DNF practice  
- **Update system packages**:
  - Debian/Ubuntu: `sudo apt update && sudo apt upgrade`  
  - RHEL/Fedora/CentOS: `sudo dnf update` (or `yum update` on older systems)

---

### 2️⃣ Install Desktop Applications 💻
- **Goal**: Practice installing productivity & communication tools  
- **Debian/Ubuntu**: LibreOffice, Firefox, Thunderbird, GIMP  
  - `sudo apt install libreoffice firefox thunderbird gimp`  
- **RHEL/Fedora/CentOS**: LibreOffice, Firefox, Thunderbird, GIMP  
  - `sudo dnf install libreoffice firefox thunderbird gimp`  
- **Verify installation**: Open apps via GUI or `which firefox`, `which libreoffice`

---

### 3️⃣ Install Server Applications 🖥️
- **Goal**: Set up basic web, database, and cloud servers  
- **Debian/Ubuntu**:
  - `sudo apt install apache2 mariadb-server nextcloud`  
- **RHEL/Fedora/CentOS**:
  - `sudo dnf install httpd mariadb-server nginx`  
- **Practice**:
  - Start/stop services: `sudo systemctl start apache2` / `httpd`  
  - Verify service status: `sudo systemctl status apache2` / `httpd`

---

### 4️⃣ Install Development Tools & Languages 🛠️
- **Goal**: Practice installing programming languages and scripting tools  
- **Debian/Ubuntu**: Python, Perl, PHP, Java  
  - `sudo apt install python3 perl php openjdk-17-jdk`  
- **RHEL/Fedora/CentOS**: Python, Perl, PHP, Java  
  - `sudo dnf install python3 perl php java-17-openjdk`  
- **Verify versions**: `python3 --version`, `perl -v`, `php -v`, `java -version`

---

### 5️⃣ Explore & Verify 🔍
- Check important directories:
  - Web servers: `/var/www/html/`, `/etc/apache2/` or `/etc/httpd/`  
  - Databases: `/etc/mysql/`, `/var/lib/mysql/`  
- Open desktop apps and confirm they launch successfully  
- Ensure services are running and accessible  

---

### ⚡ Notes
- Focus on **installation, verification, and basic service management**  
- Use **Debian/Ubuntu** for APT package manager practice and cloud-style setups  
- Use **RHEL/Fedora/CentOS** for RPM/YUM/DNF practice and enterprise-style setups  
- Labs should emphasize **just enough practice to pass the exam**
