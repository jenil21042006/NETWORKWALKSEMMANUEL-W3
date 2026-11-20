# 🔐 Password Cracking Lab — README

**📅 Week 3 | Project Modules 1 & 2**  
**🎓 Cybersecurity & Ethical Hacking Project Tasks**

**👨‍💻 Author:** Jenil Patel  
**🔒 Domain:** Cybersecurity | Ethical Hacking | Password Security

---

## 📋 Overview

This project demonstrates two different approaches to recovering the password of a password-protected PDF file (`My Locked PDF1.pdf`) using password recovery techniques.

The project explores offline password recovery using John the Ripper and browser-based password testing using Networkwalks tools.

| Module | Tool Used | Installation Needed? |
|---|---|---|
| 🛠️ **Module 1** | John the Ripper (JTR) + Johnny GUI | ✅ Yes |
| 🌐 **Module 2** | Networkwalks Online Tools | ❌ No |

---

## 🛠️ Module 1: Password Recovery Using John the Ripper

### 1️⃣ Download John the Ripper

📥 Official Website:  
https://www.openwall.com/john/

🔗 Alternative Download:  
https://distro.ibiblio.org/openwall/projects/john/1.9.0/

### 2️⃣ Download Johnny GUI

📥 Official Website:  
https://openwall.info/wiki/john/johnny

### 3️⃣ Extract the Files

📂 Extract the downloaded John the Ripper and Johnny ZIP files.

Keep the extracted folders organized for easy access.

### 4️⃣ Install and Launch Johnny

▶️ Run the Johnny installer and complete the installation.

Open Johnny after installation.

### 5️⃣ Configure John the Ripper

⚙️ Navigate to:

**Settings → Browse → Select John.exe**

Example location:

`john-1.9.0-jumbo-1-win64/run/john.exe`

### 6️⃣ Extract the PDF Hash

🌐 PDF Hash Extractor:  
https://www.onlinehashcrack.com/tools-pdf-hash-extractor.php

- Select the authorized test PDF.
- Extract its password hash.
- Copy the complete hash.

### 7️⃣ Save the Extracted Hash

📝 Open Notepad and save the extracted hash as:

`hash1.txt`

Ensure the hash is copied completely and starts with the appropriate `$pdf$` format.

### 8️⃣ Load the Hash into Johnny

📂 Open Johnny.

- Select **Open Password File**.
- Choose `hash1.txt`.
- Load the hash file.

### 9️⃣ Start Password Recovery

🚀 Select **Start New Attack**.

Use an
