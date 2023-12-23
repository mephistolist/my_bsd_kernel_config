# my_bsd_kernel_config
Just my personal kernel config for FreeBSD in virtualbox. Its as minimal as possible and includes vnet support for jails. This is also specifically for AMD processors. 

wget https://raw.githubusercontent.com/mephistolist/my_bsd_kernel_config/main/MINE?token=GHSAT0AAAAAACJ4F52X2QJJTENQBH22NLYUZMGEVYQ -O /usr/src/sys/amd64/conf/MINE
cd /usr/src/
sudo make KERNCONF=MINE kernel
