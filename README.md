## Best Practices for Backups
Some recommendations to consider for a good scheduled backup regime:

You should be able to completely recover from a catastrophic failure from at least two previous full backups. Just in case the most recent full backup is damaged, lost, or corrupt,
Your backup should contain at least one full backup within a chosen cycle, normally weekly,
Store backups away from the current data location, preferably off site,
Use a mixture of mysqldump and Xtrabackup for extra safety, and not rely on one method,
Test restore your backups on a regular basis, e.g. every two months.
A weekly full backup combined with daily incremental backup is normally enough. Keeping a number of backups for a period of time is always a good plan, maybe keep each weekly backup for one month. This allows you to recover an older database in case of emergencies or if for some reason you have local backup file corruption

<img src=./img/1.png></img>
## change ip for backup db
###### step1i:
cd /mysql/
##### vim inventory
ip1

ip2

ip3
