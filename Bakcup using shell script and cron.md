#Example:
#!/bin/bash
tar -czf /var/tmp/kafka.tar.gz /home/dell/Desktop/kafka
#        ----Destinatin Dir---  ------Source Dir-----

echo "Backup Perform at:$(date)" >> /var/backup/bup.log
#                                    --creat log file----

#in crontab
:~$ crontab -e
*	*	*	*	* /bin/bash /root/demo.sh
					   ---above .sh file path---
# 1 Star for minutes
# 2 Star for hours
# 3 Star for day of month
# 4 Star for month in number
# 5 Star for day of week (0 for sunday --- 6 for saturday)
# Set date and time as per requirment
