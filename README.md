# pike

Customer analytics based on timestamp.

Using Sqoop incremental append & Hive managed & external tables for staging & target.

Execution Instruction:
- Checkout & execute init.sh
- Create cron job to import data on 21:30 (local time)
<code>
crontab -e
30 21 * * * sh /home/cloudera/exec.sh
</code>
