# Linux CLI – File and Directory Operations Lab

Hands-on laboratory documenting practical Linux CLI exercises focused on navigation and file system management.

---

## Environment
- User: thor
- OS: Linux
- Shell: Bash

---

## Lab Tasks and Execution

### 1. Inspect directory contents
**Goal:** Count directories and files inside `/home/thor/test_dir`.

```bash
ls /home/thor/test_dir
```
**Result:**
- Directories: 3
- Files: 3

---

### 2. Identify missing file
**Goal:** Determine which text file is missing.

**Result:**
- test_file3.txt

---

### 3. Create empty file

```bash
touch /home/thor/empty_file.txt
```

---

### 4. Create file with content

```bash
cat > /home/thor/contents_file.txt
This is not empty file
# Press CTRL + D to save and exit
```

---

### 5. Create empty directory

```bash
mkdir /home/thor/empty_dir
```

---

### 6. Create directory hierarchy

```bash
mkdir -p /home/thor/asia/india/bangalore
```

**Note:** The -p flag (parents) ensures all intermediate directories are created if they do not exist, preventing errors.

---

### 7. Copy file to target directory

```bash
cp /home/thor/asia/bangalore.txt /home/thor/asia/india/bangalore
```

**Verification:** 
```bash
ls /home/thor/asia/india/bangalore
# Output: bangalore.txt
```

---

### 8. Copy directory recursively

```bash
cp -r /home/thor/asia/india/bangalore /home/thor/
```

**Note:** The -r flag (recursive) is required when copying directories to include all subdirectories and files.

---

### 9. Remove file

```bash
rm /home/thor/asia/bangalore.txt
```

---

### 10. Remove directory recursively
```bash
rm -r /home/thor/asia/india/bangalore
```

---

