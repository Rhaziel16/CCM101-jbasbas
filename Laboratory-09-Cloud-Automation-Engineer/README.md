# Laboratory 09 - Cloud Automation Engineer

## Mission Overview

This mission focuses on automating data backups using a Bash script and scheduling the task with Cron. The goal is to back up application data automatically without running the script manually every time.

## Objectives

* Understand Bash scripts, variables, and Cron jobs.
* Create a script that compresses application data.
* Use chmod to allow script execution.
* Schedule an automatic backup using Cron.
* Document the commands and results in GitHub.

## Commands Executed

```bash
mkdir app-data
echo "This is critical client data." > app-data/data.txt
nano backup.sh
chmod +x backup.sh
./backup.sh
ls -l backups/
crontab -l
env EDITOR=nano crontab -e
```

## Skills Learned

I learned how to create and run a Bash script, manage file permissions, compress files, and schedule automatic tasks in Linux. I also learned how automation can help prevent missed backups.
