# Lab – More Linux Commands

Hands-on lab focused on user identification, privilege escalation, remote access, file downloads, and OS inspection.

---

## Environment
- User: thor
- OS: CentOS Stream 9
- Shell: Bash

---

## 1. Identify current user

```bash
whoami
```

**Output:**
```bash
Thor
```

---

## 2. Display user ID information

```bash
id
```

**Output:**     
```bash
uid=1001(thor) gid=1001(thor) groups=1001(thor),10(wheel)
```

---

## 3. Switch to another user

```bash
su ansible
```

**Explanation:** Switches to the ansible user account.

---

## 4. Remote login to another server

```bash
ssh thor@172.16.238.3
```

**Explanation:** Connects to a remote server via SSH using the thor user.

---

## 5, List files in /root directory (with elevated privileges)

```bash
sudo ls /root
```

**Output:** 
```bash
anaconda-ks.cfg
anaconda-post-nochroot.log
anaconda-post.log
original-ks.cfg
```

**Explanation:** Access to /root requires superuser privileges.

---

## 6. Command that cannot download files

**Answer:** ping

**Explanation:** ping is used for network connectivity testing, not file transfer.

---

## 7. Download file using curl

```bash
curl https://www.w3.org/WAI/ER/tests/xhtml/testfiles/resources/pdf/dummy.pdf -o dummy.pdf
```

**Verification:**
```bash
ls dummy.pdf
```

---

## 8. Locate OS release information

**Answer:**
```bash
/etc/*release*
```

---

## 9. Check OS version

```bash
cat /etc/*release*
```

**Result:** CentOS Stream 9

---

## 10. Identify CentOS version

**Answer:** CentOS Stream 9

---
