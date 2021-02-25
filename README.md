# system.new.dat.br
sudo mount -t ext4 -o loop system.img system/

# repack .img
sudo make_ext4fs -s -l 6361350144 -a system system_new.img system/
