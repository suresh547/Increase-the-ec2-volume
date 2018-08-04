# Increase-the-ec2-volume4

to resize the ebs volume to instance

1.attach the volume to ec2 instance 
2.modify the ebs volume 
3. create the file system to that ebs
with the help of 

command: mkfs -t ext4 /dev/xvdf

then mount to ec2  
for that need to create the directory

then mount 

mount /dev/xvdf suresh

to check the size for that directory

df -h

to resize the ebs in ec2 online
resize2fs /dev/xvdf

then check the file size df -h


to check the file system to that device

file -s /dev/xvdf


for root volume modification u need to reboot the ec2


 
