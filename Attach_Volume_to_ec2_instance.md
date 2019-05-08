# commands

lsblk

df -h

# create file based on volume type

sudo file -s /dev/xvdf

# create filesystem

sudo mkfs -t ext4 /dev/xvdf

lsblk

# Mount volume to directory

sudo mount /dev/xvdf dirname

# unmount the volume

sudo umount dirname

