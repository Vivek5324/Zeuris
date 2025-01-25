# Zeuris

Zeuris is a bash-based script specifically designed for Termux but also functions seamlessly on both rooted and non-rooted Android devices. This tool simplifies the process of generating phishing pages that can collect information with just a single click. It is tailored for beginners and is an excellent resource for exploring phishing techniques for educational purposes.

---

## Platform Availability
- **Termux**  
- **Kali Linux**

---

## Tested Environments
- Termux  

---

## Requirements
- Internet: 100 MB  
- Storage: 100 MB  
- PHP  
- Port Forwarding  

---

## Features
- **Realistic Pages**: Creates authentic-looking phishing pages.  
- **Updated Maintenance**: Regularly maintained for optimal performance.  
- **Localhost Links**: Allows localhost testing.  
- **Cloudflare Links**: Enables wider access through Cloudflare.  
- **Beginner-Friendly**: Designed with simplicity for those new to cybersecurity.  

---

## Installation (For Termux)

1. Update and upgrade packages:
   ```bash
   apt-get update -y  
   apt-get upgrade -y  
   ```
2. Install required dependencies:
   ```bash
   pkg install git -y  
   pkg install php -y  
   pkg install cloudflared -y  
   pkg install curl -y  
   pkg install openssh -y  
   pkg install chafa -y  
   ```
3. Clone the repository:
   ```bash
   git clone https://github.com/noob-hackers/zeuris  
   ```
4. Navigate to the directory:
   ```bash
   cd $HOME/zeuris  
   ```

Ensure an active internet connection before proceeding with further steps.

---

## Usage Options (Termux)

1. **START**:  
   Generate phishing pattern links to gather information from targeted users.  
2. **ABOUT**:  
   View details about the script and its purpose.  
3. **UPDATE**:  
   Check for and apply updates to the tool.  
4. **EXIT**:  
   Exit the tool safely.  

---

## Important Notes
- Do not delete any script files within the Zeuris directory to avoid errors.  
- This tool is strictly for educational use and should not be employed for unethical activities.  

---

## Disclaimer
This tool is designed purely for educational purposes. Any misuse of this tool for unethical or illegal activities is strictly discouraged and is the sole responsibility of the user. Always use such tools responsibly to enhance cybersecurity knowledge and skills.
