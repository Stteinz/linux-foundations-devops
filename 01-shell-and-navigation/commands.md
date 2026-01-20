# Linux Fundamentals – Shell and Navigation

## Identify current shell
```bash
echo $SHELL
```

Output example:
```
/bin/bash
```

Explanation:
Shows which shell is currently running. Bash is the industry standard on Linux servers.

---

## pwd – Print working directory
```bash
pwd
```

Output example:
```
/home/gabriel
```

Explanation:
Shows the absolute path of the current directory.

---

## mkdir – Create directories
```bash
mkdir -p /tmp/devops/project/logs
```

Output example:
(no output)

Explanation:
Creates nested directories in a single command. Very common in DevOps setups.

---

## touch – Create empty files
```bash
touch script.sh
```

Explanation:
Creates an empty file, usually used to start scripts or config files.

