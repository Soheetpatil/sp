# 🔐 Security Challenge Answers

| 📄 File                | 🔑 Recommended Permission | 🧠 Reason                                      |
| --------------------- | ------------------------ | --------------------------------------------- |
| password_backup.txt   | 600                      | Contains sensitive password information       |
| public_notice.txt     | 644                      | Everyone should be able to read it            |
| system_log.txt        | 640                      | Admin can modify, authorized users can read   |
| personal_notes.txt    | 600                      | Personal and confidential information         |

---

## 🧾 Explanation

🔒 Sensitive files should have restricted access to prevent unauthorized viewing or modification.

🌍 Public files can have read access for all users because they do not contain confidential information.

🛠️ System logs should only be accessible to administrators and authorized personnel.

🧑‍💻 Personal notes should remain private and only accessible by the owner.
```
