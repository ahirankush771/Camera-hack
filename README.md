# Camera-Hack 🔒 Ethical Penetration Testing Tool

**Created by: Ankush Kumar**  
*Passionate Cybersecurity Enthusiast | Ethical Hacker | Developer*  
* Persuing Diploma in computer science and engineering *
* Government Polytechnic Khagaria (2025-28) Batch *
[GitHub Profile](https://github.com/ahirankush771) | [LinkedIn](https://linkedin.com/in/ahirankush771) *(optional)*

---

## 📋 Overview

**Camera-Hack** is an **ethical penetration testing tool** designed for authorized security professionals to assess webcam and camera security vulnerabilities in controlled environments. This tool demonstrates common camera access techniques used in ethical hacking assessments, helping cybersecurity professionals identify and mitigate webcam-related risks.

**⚠️ LEGAL DISCLAIMER**: This tool is for **authorized penetration testing only**. The author has explicit permission to perform security assessments. Unauthorized use against systems without permission is illegal and unethical. Always obtain written authorization before testing.

## ✨ Features

- 🎥 Local camera access and stream capture
- 🔍 Real-time video feed analysis
- 📱 Cross-platform compatibility (Desktop & Termux)
- 🛡️ Educational focus on ethical hacking techniques
- 💻 Simple Python-based implementation

## 🛠️ Technical Stack
Language: Python Frontend: HTML5, CSS, JavaScript Backend: Flask (or similar) Requirements: OpenCV, NumPy Compatible: Kali Linux, Termux, Windows
## 📱 Prerequisites

Before using Camera-Hack, ensure you have:

```bash
# Python 3.8+
python3 --version

# Required packages
pip install opencv-python numpy flask

# For Termux (Android)
pkg install python opencv-python
```
🚀 Installation & Setup
Method 1: Git Clone (Recommended)
```
git clone https://github.com/ahirankush771/Camera-hack.git
cd Camera-hack
pip install -r requirements.txt
```
Method 2: Manual Setup
1. Download the repository ZIP
2. Extract to your working directory
3. Install dependencies: pip install -r requirements.txt

🎯 Step-by-Step Usage
Step 1: Start the Server
```
# Navigate to project directory
cd Camera-hack

# Run the main server
python3 main.py
```
Server will start on: http://localhost:5000
Step 2: Access Web Interface
1. Open your browser
2. Navigate to http://localhost:5000
3. Grant camera permissions when prompted
Step 3: Camera Controls
🔴 RED Button: Start Camera Stream
⏹️  STOP Button: End Stream
📸 SNAP Button: Capture Screenshot
📹 RECORD Button: Start/Stop Recording
Step 4: Analyze Results
• Screenshots saved to /screenshots/
• Recordings saved to /recordings/
• Logs available in /logs/camera.log

🌐 Termux (Android) Usage
# Install dependencies
```
pkg update && pkg upgrade
pkg install python git
pip install opencv-python flask numpy
```
# Clone & run
```
git clone https://github.com/ahirankush771/Camera-hack.git
cd Camera-hack
python main.py
```

# Access via browser: http://127.0.0.1:5000

##🔒 Security Assessment Checklist
#Before Testing:
• Obtain written authorization
• Define scope of assessment
• Verify target ownership
• Backup target systems
• Document Rules of Engagement
##During Testing:
• Monitor only authorized targets
• Respect privacy boundaries
• Log all activities
• Report findings immediately
#After Testing:
• Clean up all artifacts
• Securely delete recordings
• Deliver comprehensive report
• Verify remediation

##📊 Sample Pentest Report Template
Vulnerability: Webcam Access Bypass
Severity: HIGH (CVSS 7.5)
Affected: Target System Webcam
#Reproduction: 
1. Access http://target:5000
2. Grant permissions
3. Stream captured successfully

#Recommendation: 
- Disable webcam when not in use
- Implement endpoint protection
- Browser sandboxing
#Troubleshooting
  Issue,Solution
Permission Denied,Grant camera access in browser
ModuleNotFoundError,pip install -r requirements.txt
Port Already in Use,python main.py --port 5001
Termux Camera Fail,termux-camera-info

📄 License:
✓✓Educational & Authorized Pentesting License
© 2026 Ankush Kumar
For authorized security assessments only
🛡️ Responsible Disclosure:
✓✓Found a security issue? Report responsibly:
Email: ahirankush771@gmail.com
PGP Key Available
