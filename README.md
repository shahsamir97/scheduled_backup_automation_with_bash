Automated File Backup with Bash

Overview

A Bash-based backup automation script that identifies files modified within the last 24 hours, compresses them into a timestamped .tar.gz archive, and schedules daily backups using cron.

Features

Validates source and destination directories.

Detects files modified within the last 24 hours.

Creates timestamped compressed backup archives.

Automates daily execution using cron.

Tech Stack

Bash, Linux, Cron, tar, gzip, Unix Commands

Usage

Make the script executable:

chmod +x backup.sh

Run a backup manually:

./backup.sh important-documents .

Schedule daily backups using crontab -e:

0 0 * * * /usr/local/bin/backup.sh /home/project/important-documents /home/project

Outcome

Built an automated backup workflow that reduces manual effort, minimizes human error, and ensures recently modified files are backed up daily.

Acknowledgment

Developed as part of the IBM Hands-on Introduction to Linux Commands and Shell Scripting course.
