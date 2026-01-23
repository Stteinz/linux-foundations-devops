# Lab – VI Editor Fundamentals

Hands-on laboratory focused on understanding and practicing core operations of the `vi` / `vim` text editor.

---

## Environment
- Editor: Vim
- OS: Linux
- Shell: Bash

---

## 1. Default editor
**Question:** What is the default editor configured in the lab?  
**Answer:** Vim

---

## 2. Open a file with Vim
**Question:** What command opens a file using Vim?  
**Answer:** `vi <filename>` or `vim <filename>`

---

## 3. Operation modes
**Question:** What are the operation modes in vi editor?  
**Answer:**
- Command mode
- Insert mode
- Last line mode (command-line mode)

---

## 4. Default mode
**Question:** What is the default mode when opening a file?  
**Answer:** Command mode

---

## 5. Incorrect statement (mode switching)
**Answer:** Pressing capital letter `T` switches to insert mode (incorrect)

---

## 6. Task – Create and edit file

```bash
vi kodekloud.txt
```

**Steps executed:**
- Default mode: command mode
- Enter insert mode: 'i'
- Typed: 'Hello world!'
- Return to command moe: 'Esc'
- Save and exit: ':wq!'

---

## 7. Copy a line

```bash
yy
```

---

## 8. Incorrect statement (commands)

**Answer:** 'dd' highlights a line (incorrect- it deletes the line)

---

## 9. Correct command mapping

**Correct answers:**
- u -> undo
- Ctrl + r -> redo

---

## 10. Move line inside a file

```bash
vi /home/bob/testfile.txt
```
**Steps:**
```bash
:set number
:9m 4
```

**Verification:** The line "you found me" is now at line 5.
```bash
:wq!
```

---

## 11. Delete first three lines

```bash
:1,3d
:wq!
```

---

**Learning Outcome**
By completing this lab, I am able to efficiently navigate, edit, manipulate, and restructure files ussing the vi editor- a critical skill for Linux servers and DevOps workflows.

---
