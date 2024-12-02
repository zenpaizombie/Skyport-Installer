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
# Ubuntu/Debian
sudo mkdir -p /etc/apt/keyrings
curl -fsSL https://deb.nodesource.com/gpgkey/nodesource-repo.gpg.key | sudo gpg --dearmor -o /etc/apt/keyrings/nodesource.gpg
echo "deb [signed-by=/etc/apt/keyrings/nodesource.gpg] https://deb.nodesource.com/node_20.x nodistro main" | sudo tee /etc/apt/sources.list.d/nodesource.list

sudo apt update
sudo apt install -y nodejs git
```
__________________________________________________

# Clone The Repo:
```
git clone https://github.com/zenpaizombie/Skyport-Installer.git
```
__________________________________________________

# Installation
The following commands will download the Skyport Panel into /etc/skyport and use npm to install the required packages:
```
chmod +x installer.sh
sudo ./installer.sh
```
- Pick Whatever You Want!!
__________________________________________________
