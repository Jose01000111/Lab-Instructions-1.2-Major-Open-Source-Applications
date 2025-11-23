## 🛠️Lab Instructions — 1.2 Major Open Source Applications

>💬 **Tip:** Paste this study guide into ChatGPT and ask for **more instructions** by specifying:  
>- “Provide step-by-step lab instructions for this objective.”  
>- “Include which Linux distro to use (Debian/Ubuntu or RHEL/Fedora).”  
>- “Show examples of installing, verifying, and managing desktop and server applications.”  
>- “Include minimal command-line practice for package management and development tools.”  
>- “Focus only on what is most important for passing the LPI Linux Essentials exam.”  

>This will prompt ChatGPT to give **practical, exam-focused lab steps** for each section.


### 🐧 **Debian / Ubuntu-based Distros**
- **Update package lists**: `sudo apt update`  
- **Install desktop apps**: LibreOffice, Firefox, Thunderbird, GIMP  
  - Example: `sudo apt install libreoffice firefox thunderbird gimp`  
- **Install server apps**: Apache, MariaDB, Nextcloud  
  - Example: `sudo apt install apache2 mariadb-server nextcloud`  
- **Install dev languages/tools**: Python, Perl, PHP, Java  
  - Example: `sudo apt install python3 perl php openjdk-17-jdk`  

### 🐓 **Red Hat / CentOS / Fedora**
- **Update packages**: `sudo dnf update` (or `yum` on older versions)  
- **Install desktop apps**: LibreOffice, Firefox, Thunderbird, GIMP  
  - Example: `sudo dnf install libreoffice firefox thunderbird gimp`  
- **Install server apps**: Apache, MariaDB, NGINX  
  - Example: `sudo dnf install httpd mariadb-server nginx`  
- **Install dev languages/tools**: Python, Perl, PHP, Java  
  - Example: `sudo dnf install python3 perl php java-17-openjdk`  

### 📝 **Practice Focus**
- Start & stop services (Apache/Nginx, MariaDB)  
  - `sudo systemctl start apache2` / `httpd`  
- Verify installations (check versions): `python3 --version`, `java -version`  
- Explore directories: `/etc/apache2/`, `/var/www/html/`, `/etc/mysql/`  
- Open apps (desktop): LibreOffice, Firefox, Thunderbird, GIMP  

### ⚡ **Notes**
- Use **Debian/Ubuntu** for APT practice, server apps, cloud-style setup  
- Use **RHEL/Fedora/CentOS** for RPM/YUM/DNF practice, enterprise-style setup  
- Focus labs on **installation, verification, basic service management**
