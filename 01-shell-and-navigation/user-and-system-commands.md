# User and System Commands

This document covers essential Linux commands related to user identity, privilege management, remote access, and system information. These commands are commonly used in server administration and DevOps workflows.

---

## whoami – Current user

```bash
whoami
```

**Explanation:** Displays the username of the currently logged-in user.

---

## id - User identity details

```bash
id
```

**Explanation:** Shows user ID (UID), group ID (GID), and all groups the user belongs to.

---

## su - Switch user

```bash
su aparna
```

**Explanation:** Switches to another  user account. Requires the target user`s password.

---

## ssh - Remote system access

```bash
ssh aparna@192.168.1.2
```

**Explanation:** Connects securely to a remote Linux system using SSH.

---

## Permission denied example

```bash
ls /root
```

**Explanation:** Regular users are restricted from accessing protected system directories.

---

## sudo - Execute commands as root

```bash
sudo ls /root
```

**Explanation:** Runs a command with superuser (root) privileges.

---

## Download files with curl

```bash
curl http://www.example.com/file.txt -o file.txt
```

**Explanation:** Donwloads a file from a URL and saves it locally.

---

## Download files with wget

```bash
wget http://www.example.com/file.txt
```

**Explanation:** wget http://www.example.com/file.txt

---

## check OS version

```bash
cat /etc/*release*
```

**Explanation:** Displays Linux distribution and version information.

---
