This repo contains a mirror of image Yocto Linux image for Edison from Intel.

You can recreate this repository using:

```
mkdir images && cd images/
wget http://downloadmirror.intel.com/24698/eng/edison-image-ww05-15.zip
unzip edison-image-ww05-15.zip
rm edison-image-ww05-15.zip
mount edison-image-edison.ext4 /mnt
cp -r /mnt/lib/firmware ../firmware
umount /mnt
rm edison-image-edison.ext4
```
