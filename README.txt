created 4 virtual hard disks in virtualbox
 mdadm --create --verbose /dev/md0 --level=5 --raid-devices=3 /dev/sdb /dev/sdc /dev/sdd --spare-devices=1 /dev/sde
which put all the disks into raid 5
mounted the disk with GParted
Copied save.png onto the raided drive. 

MCA-flag is: MCA{RA1D3rs_0f_the_L0sT_bits}