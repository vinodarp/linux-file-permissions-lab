## Linux File Permissions Management

**Overview:**  
This project was part of my Cybersecurity coursework and focuses on exploring Linux file system navigation and permission management using command-line tools. Through hands-on exercises, I practiced core commands used in everyday cybersecurity roles and learned how permissions impact system security.

---

### Objectives

- Learn and apply Linux commands to navigate directories.
- View and interpret file contents using basic commands.
- Understand and modify file permissions using `chmod`.
- Analyze permission structures to ensure secure file access.

---

### Key Commands Used

| Command | Purpose |
|---------|---------|
| `cd`    | Change directory |
| `pwd`   | Print working directory |
| `ls`    | List files and directories |
| `cat`, `head` | View file contents |
| `chmod` | Change file permissions |

---

### Highlights

- Navigated through nested directories and located specific user files.
- Viewed and interpreted the contents of employee records.
- Applied permission changes using `chmod` to restrict group access to sensitive files.
- Confirmed permission changes with `ls -la`.

---

### Sample Output

```bash
chmod g-r project_m.txt
chmod o-w project_k.txt
ls -la
