# Linux POC Project

## 📌 Objective

This Proof of Concept (POC) project showcases foundational skills in Linux system administration, networking, shell scripting, and automation. The project includes hands-on tasks that demonstrate proficiency in real-world system operations and monitoring tasks using Linux command-line tools.

---

## 📂 Project Structure

The project contains the following scripts and configuration setups:

### ✅ Task 1: Linux Essentials & File Permissions
- Create user `studentuser`
- Create project directories and a `welcome.txt` file
- Set permissions
- Script: `backup.sh` - backups `welcome.txt` with timestamps

### 🌐 Task 2: Networking Toolkit
- Script: `netinfo.sh` - Displays IP, gateway, open ports, ping test, and DNS lookup
- Output: `network_report.txt`

### 🖥️ Task 3: Mini Server Monitor
- Script: `monitor.sh` - Checks `nginx`, system stats (CPU, memory, disk)
- Scheduled with `cron` every 5 minutes

### 🔍 Task 4: File Watcher
- Script: `watch_dir.sh` - Monitors `.txt` file creation in `logs` directory
- Logs changes with timestamps into `log_monitor.txt`

### 🔐 Task 5: SSH Login Audit
- Parses `/var/log/auth.log` or `journalctl`
- Logs last 5 successful & failed login attempts into `ssh_audit.txt`

### ⏰ Task 6: Crontab Practice
- Job 1: `echo "Good morning!"` at 8 AM daily
- Job 2: Backup `projectX` every Sunday
- Job 3: Delete `.log` files older than 7 days every Friday midnight

### 🔎 Task 7: Port Scanner
- Script to scan ports 20–25 on a user-supplied IP using `nc` or `timeout`

### 🌐 Task 8: Website Availability Checker
- Reads URLs from `sites.txt`
- Checks availability using `curl` or `ping`
- Logs results into `site_status.log`

### 📊 Task 9: System Environment Report
- Gathers current user, uptime, mounted filesystems, environment variables

### 🗜️ Task 10: Archive Automation
- Finds `.log` files >10MB
- Compresses them into `archive_<date>.tar.gz`
- Moves archive to `/home/studentuser/projectX/backup/`

---

## 🛠️ Requirements

- Bash shell (Linux environment)
- `cron`, `ping`, `curl`, `netstat`/`ss`, `nslookup`, `nc`, `tar`, etc.
- Root or sudo privileges for some tasks

---

## 📅 Author & Date

- **Author**: [Your Name]
- **Date**: July 2025

---

## 📝 Notes

This lab was created for educational purposes to demonstrate practical system administration tasks. All scripts are tested in a standard Ubuntu-based environment.
