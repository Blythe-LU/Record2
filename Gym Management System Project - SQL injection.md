# Gym Management System Project Login page has SQL injection

[College Attendance System (CAS)](https://www.sourcecodester.com/visual-basic-net/15538/college-attendance-system-cas.html) Released by SourceCodester Has SQL Injection in the admin login page and the add coach page

An attacker can obtain database information and modify the database content through this vulnerability, which is extremely harmful.

## There is sql injection in the following paths

The following paths have post-type injection

```
/mygym/admin/login.php
```

The following paths have get-tpye injection

```
/mygym/admin/index.php?edit_tran
```



## sql post-type injection

### The admin login page is as follows

![image-20220809113141195](Gym%20Management%20System%20Project%20-%20SQL%20injection.assets/image-20220809113141195.png)

![image-20220809113524845](Gym%20Management%20System%20Project%20-%20SQL%20injection.assets/image-20220809113524845.png)

![image-20220809160800613](Gym%20Management%20System%20Project%20-%20SQL%20injection.assets/image-20220809160800613.png)



#### There are 2 fields with injection points

```
admin_email
admin_pass
```

![image-20220809160732750](Gym%20Management%20System%20Project%20-%20SQL%20injection.assets/image-20220809160732750.png)







## sql get-type injection

### The /mygym/admin/index.php?edit_tran    page is as follows

![image-20220809145603247](Gym%20Management%20System%20Project%20-%20SQL%20injection.assets/image-20220809145603247.png)



![image-20220809145548944](Gym%20Management%20System%20Project%20-%20SQL%20injection.assets/image-20220809145548944.png)



![image-20220809154840926](Gym%20Management%20System%20Project%20-%20SQL%20injection.assets/image-20220809154840926.png)

















## LINK

https://www.sourcecodester.com/php/15515/gym-management-system-project-php.html