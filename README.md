# 🐧 Linux Task 02 - Users, Groups & File Permissions 🔐

## 👤 Student Information

**🧑 Name:** Soheet Patil

---

## 🎯 Objective

The objective of this task is to understand Linux users, groups, file ownership, and file permissions. These concepts are essential for Linux administration and cybersecurity 🛡️

---

## 📚 Topics Covered

- 👤 Linux Users  
- 👥 Linux Groups  
- 🆔 User IDs (UID)  
- 🆔 Group IDs (GID)  
- 📁 File Ownership  
- ⚙️ `chmod` Command  
- 👑 `chown` Command  
- 🔐 Linux Security Basics  
- ⚖️ Principle of Least Privilege  

---

## 💻 Commands Used

```bash
whoami
id
cat /etc/passwd

groupadd interns
groupadd cyberteam

useradd -m student1
useradd -m student2
useradd -m student3

usermod -aG interns student1
usermod -aG cyberteam student2
usermod -aG interns,cyberteam student3

ls -l
chown
chmod
```

---

## 📂 Folder Structure

```
Linux_Task_02_SoheetPatil/

├── 📸 Screenshots/

├── 📄 README.md

├── 🔐 Permission_Analysis.md

├── 🧠 Security_Challenge.md

└── 📊 Research_Answers.md
```

---

## ✅ Conclusion

This task provided practical experience with Linux user management, file ownership, and permissions. Understanding these concepts is important for maintaining secure Linux systems 🐧🔐
```
