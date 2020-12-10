# ifup-vxlan
Extend the ifup script of centos for vxlan supporting.


install:
1.Copy ifup-vxlan file to /etc/sysconfig/network-script
cp ifup-vxlan /etc/sysconfig/network-script/
2.change the mode of ifup-vxlan file
cd /etc/sysconfig/network-script/
chmod 755 ifup-vxlan
3、create a ifcfg file for the vxlan
