## Extracting GPS Trace
```bash
/usr/local/mysql/bin/mysql -u root -p
```
## In MySQL
```sql
show databases;
use staff;
desc locations;
select * from  aware_device;
SELECT * from locations WHERE device_id = '0f0b5a35-97ff-4ea6-80c4-d575fea1903d';
SELECT timestamp, double_latitude, double_longitude from locations WHERE device_id = '6ac45b5e-d573-496f-9d8d-a2da414eb4ec';
SELECT timestamp, double_latitude, double_longitude from locations WHERE device_id = '38b7e9ed-43e2-4dd6-8b70-f5508db91322';
```
