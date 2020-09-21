# MyFails
```bash
#How to use sepolicy writer script

wget or curl that logcat.txt (if using server) then

cat logcat.txt | grep avc | ~/romfoldername/external/selinux/prebuilts/bin/audit2allow -p sepolicy > denials.tx
