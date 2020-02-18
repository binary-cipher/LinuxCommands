# LinuxCommands
Useful linux commands for setup, config, monitoring, etc

##### Show swap info and usage
```
$ swapon -s
```
```
Filename				Type		Size	Used	Priority 
 /dev/dm-0                              	partition	33418744	0	-2
```
##### Find out more information on the device mappers
```
dmsetup ls
dmsetup info /dev/dm-0
```
##### Block device Information
```
lsblk -a
blkid -i /dev/sda1
```
##### System Monitoring from the console
```
sudo glances
```
