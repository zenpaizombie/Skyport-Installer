__________________________________________________

# INSTALLATION

Picking A Server OS

Skyport runs on a wide range of operating systems, so pick whichever you are most comfortable using.

__________________________________________________
Ubuntu	24.04,22.04	✅
__________________________________________________
Debian	11,12 ✅
__________________________________________________
CentOS	7,8	✅
__________________________________________________
Windows	10,11 ⚠️ (Support is very limited due to Docker's use of WSL (and LinuxKit VMs on Mac) on the Windows and macOS operating systems. You will have issues connecting to instances ran on a machine with either OS. **You'll only have issues with Skyport Daemon - the Panel will work just fine.**)
__________________________________________________
macOS	10.15+	⚠️
__________________________________________________

# Dependencies
- **Node.js** **``v20``** and higher (**Nodejs** **``v20``** **recommended).
# Example Dependency Installation
The commands below are simply an example of how you might install these dependencies on Ubuntu 24.04. Please consult with your operating system's package manager to determine the correct packages to install.
```
# Ubuntu/Debian/Docker

sudo apt update
sudo apt install -y nodejs git
sudo apt install npm -y
```
__________________________________________________

# Clone The Repo & Access:
```
git clone https://github.com/zenpaizombie/Skyport-Installer.git
cd Skyport-Installer
```
__________________________________________________

# Installation
The following commands will download the Skyport Panel into /etc/skyport and use npm to install the required packages:
```
chmod +x installer.sh
sudo ./installer.sh
```
- Pick 1 To Install The Panel & Deamon Instantly!!
__________________________________________________
