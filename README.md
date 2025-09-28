# Requirements
- Linux OS (I used Linux Mint(Ubuntu))
- Install testdisk
- Install photorec in my case was installed inside testdisk

## Encode the video
![[Handbrake.png]]
# Installation
- You have to run this command to install testdisk.
```
 sudo apt install testdisk
```

# Procedure
- First you should introduce a DVD and mount it in you system, in my case it was mounted immediately.

- Then you should run this command to check the format of the DVD usually is ext4
```
 df -T /mnt
```

- After that you should run testdisk:
```
testdisk
```

- select the partitions in case of DVD, it doesn't have  partition in case of HDD or SSD will have a partition for sure, and make an image of the DVD or disk. It will output a .dd file.

- Then you should run, And select the route that you want to save your file:
```
photorec file.dd
```

# Usefull urls
- https://www.cgsecurity.org/
- https://www.reddit.com/r/computerforensics/comments/ul8e7r/a_starters_guide_on_recovering_damaged_and_rotten/
- https://www.cyberciti.biz/tips/how-do-i-save-recover-data-from-crashed-disks-with-dd-and-ddrescue-command.html
- https://secnigma.wordpress.com/2022/05/08/a-guide-to-recovering-damaged-and-rotten-cds/
