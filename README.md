# 🔒 Akm Nizum - Cybersecurity Portfolio

**Interactive Linux-style portfolio showcasing cybersecurity projects, CCNA labs, and professional presentations**

🌐 **Live Demo:** https://anizum1.github.io/Akm_Portfolio/
🔐 **Login Password:** `password`

---

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Portfolio Contents](#portfolio-contents)
- [Folder Structure](#folder-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Contact](#contact)

---

## 👤 About

I'm Akm Nizum, a cybersecurity specialist with expertise in:
- **Network Security** - CCNA certified with hands-on router/switch configuration
- **Incident Response** - Real-world experience responding to security incidents
- **Digital Forensics** - Electronic evidence collection and analysis
- **Security Research** - Data breach analysis and critical infrastructure protection
- **Python Development** - Security automation and OSINT tools

**Education:** Bachelor of Applied Technology in Cybersecurity (Collin College - NSA CAE-CD Validated Program)

**Certifications:**
- NSA Validated Program (CAE-CD)
- CCNA (Cisco Certified Network Associate)
- Information Systems Cybersecurity Certificate
- Cybersecurity Infrastructure Technician Certificate

---

## ✨ Features

### 🖥️ Interactive Linux Desktop
- Authentic Kali Linux-style interface
- Login screen with password authentication
- Boot sequence animation
- Full graphical desktop environment
- Task bar with window management
- Multiple applications and folders

### 💻 Working Terminal
- Full CLI with working commands
- Command history (↑/↓ arrows)
- File system navigation
- Color-coded output
- System information display

### 📂 Organized Content
- **Projects** - 18 cybersecurity projects
- **Cisco Labs** - 17 Packet Tracer network configurations
- **Presentations** - 6 professional PowerPoint presentations
- **Certifications** - 4 certificates with PDF viewer
- **Skills & Tools** - Comprehensive technology proficiency
- **Experience** - Professional work history

---

## 📦 Portfolio Contents

### 🔐 Security Projects (18)
- Python security tools
- OSINT investigations
- Web application security scanners
- Malware analysis scripts
- Vulnerability assessment tools
- Network forensics utilities

### 🌐 Cisco CCNA Labs (17)
Located in `cisco-labs/` folder:
- **Exam Labs**: MIDTERM and FINAL demonstration labs
- **Practice Labs**: Multiple practice scenarios
- **Specialized**: IPv6, VLAN configuration
- **Curriculum**: Labs 3.6.2, 4.2.8, 4.5.2, 6.4.2, 7.4.2, 15.6.2

**Skills Demonstrated:**
- Router & Switch Configuration
- VLAN Design & Trunking
- Static & Dynamic Routing (OSPF, EIGRP)
- IPv4 & IPv6 Addressing
- Network Services (DHCP, DNS, NTP)
- ACLs & Security
- Network Troubleshooting

### 📊 Professional Presentations (6)
Located in `presentations/` folder:

1. **Oracle Health Data Breach (2025)** - Incident analysis & case study
2. **Cybersecurity Part 4** - Educational training series
3. **Electronic Evidence from ISPs** - Digital forensics & legal procedures
4. **Security Audit Final** - Comprehensive audit findings
5. **Water Infrastructure Security** - Critical infrastructure protection
6. **Networking Fundamentals** - Technical training presentation

---

## 📁 Folder Structure

```
akm-portfolio/
├── index.html                          # Main portfolio website
├── README.md                           # This file
│
├── assets/
│   ├── images/                         # Website images
│   │   ├── dragon-logo-blue.png
│   │   ├── dragon-logo-purple.png
│   │   ├── wallpaper-code.png
│   │   ├── wallpaper-ai.png
│   │   └── wallpaper-hacker.png
│   │
│   └── docs/                           # PDF documents
│       ├── Akm_Nizum_Resume__1_.pdf
│       └── Certs.pdf
│
├── cisco-labs/                         # 17 Packet Tracer labs (.pkt files)
│   ├── MIDTERM-Demo-Lab.pkt
│   ├── FINAL-Demo-Lab.pkt
│   ├── IPv6-Configuration-Lab.pkt
│   ├── VLAN-Configuration-Lab.pkt
│   └── ... (13 more labs)
│
└── presentations/                      # 6 PowerPoint presentations
    ├── Oracle-Health-Data-Breach-2025.pptx
    ├── Cybersecurity-Part4-Presentation.pptx
    ├── Electronic-Evidence-ISP-Best-Practices.pptm
    ├── Security-Audit-Final-Presentation.pptx
    ├── Water-Infrastructure-Security.pptx
    └── Networking-Fundamentals-Presentation.pptx
```

---

## 🚀 Installation

### Option 1: GitHub Pages (Recommended)

1. **Fork or clone this repository**
```bash
git clone https://github.com/YOUR-USERNAME/akm-portfolio.git
```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to Pages section
   - Source: Deploy from branch
   - Branch: `main` / `(root)`
   - Click Save

3. **Access your portfolio**
   - URL: `https://YOUR-USERNAME.github.io/akm-portfolio/`
   - Login password: `password`

### Option 2: Local Setup

1. **Clone the repository**
```bash
git clone https://github.com/YOUR-USERNAME/akm-portfolio.git
cd akm-portfolio
```

2. **Serve locally**
```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js
npx http-server

# Using PHP
php -S localhost:8000
```

3. **Open in browser**
   - Navigate to `http://localhost:8000`
   - Login password: `password`

---

## 💡 Usage

### Navigating the Portfolio

1. **Login Screen**
   - Enter password: `password`
   - Watch the boot sequence

2. **Desktop Environment**
   - Click any of the 12 desktop icons
   - Use the Applications menu (top bar)
   - Open multiple windows simultaneously

3. **Terminal Commands**
   - `help` - Show all commands
   - `ls` - List files
   - `cd <folder>` - Change directory
   - `cat <file>` - View file contents
   - `neofetch` - System information
   - `download` - Download resume
   - `clear` - Clear screen

4. **Viewing Files**
   - **Certificates** - Click to view PDF in browser
   - **Cisco Labs** - Click to download .pkt files (requires Cisco Packet Tracer)
   - **Presentations** - Click to download PowerPoint files
   - **Projects** - View descriptions and details

### Customization

**Change Password:**
Edit `index.html` line containing:
```javascript
if (password === 'password') {
```

**Change Content:**
Edit the `fileSystem` object in `index.html` to add/modify content

**Change Wallpapers:**
Replace image files in `assets/images/`

---

## 🛠️ Technologies

**Frontend:**
- HTML5, CSS3, JavaScript (Vanilla)
- No frameworks or dependencies
- Fully client-side (no server required)

**Design:**
- Custom Kali Linux-inspired theme
- Responsive layout
- Professional cybersecurity aesthetic

**Compatibility:**
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive
- Works offline after initial load

---

## 📧 Contact

**Akm Nizum**

- 📧 Email: zanzorofel@gmail.com
- 📱 Phone: +1 984 484 4916
- 📍 Location: Dallas, TX
- 🐙 GitHub: [github.com/anizum1](https://github.com/anizum1)
- 💼 LinkedIn: [linkedin.com/in/akm-nizum-open-t0-w0rk](https://www.linkedin.com/in/akm-nizum-open-t0-w0rk/)

---

## 📜 License

This portfolio is created by Akm Nizum. Content is for demonstration purposes.

**Cisco Labs:** Original coursework from Collin College CCNA program  
**Presentations:** Original research and analysis  
**Projects:** Original development work  

---

## 🎯 Why This Portfolio?

This portfolio demonstrates:

✅ **Technical Proficiency** - Real working projects and configurations  
✅ **Hands-On Experience** - Actual Cisco labs and security tools  
✅ **Research Skills** - Professional presentations on security topics  
✅ **Communication** - Ability to present complex technical concepts  
✅ **Creativity** - Unique Linux-style interactive interface  
✅ **Attention to Detail** - Professional, polished presentation  

**Perfect for:**
- Job applications (Cybersecurity Analyst, Network Engineer, SOC Analyst)
- Showcasing skills to recruiters
- Professional networking
- Portfolio reviews
- Technical interviews

---

## 🔥 Highlights

- **🎓 NSA Validated Program** - Collin College CAE-CD designation
- **📜 CCNA Certified** - With 17 documented lab configurations
- **💼 Real Experience** - Incident Response Specialist at Technauf IT
- **🔒 18 Security Projects** - Python tools, OSINT, web security
- **📊 6 Professional Presentations** - Research, analysis, training
- **🌐 Live Interactive Portfolio** - Unique Linux desktop interface

---

## 🙏 Acknowledgments

- **Collin College** - Cybersecurity program and CCNA training
- **Technauf IT Service** - Incident response experience
- **NSA** - Validated program designation

---

**© 2025 Akm Nizum | Cybersecurity Specialist**

*Built with passion for security and dedication to excellence*

---

### 📌 Quick Links

- 🌐 [Live Portfolio](https://YOUR-USERNAME.github.io/akm-portfolio/)
- 📄 [Download Resume](assets/docs/Akm_Nizum_Resume__1_.pdf)
- 🏆 [View Certificates](assets/docs/Certs.pdf)
- 🐙 [GitHub Profile](https://github.com/anizum1)

---

**⭐ If you find this portfolio impressive, please star the repository!**
