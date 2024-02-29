# -RTL8125B-on-Proxmox
list of steps to install  Realtek RTL8125B 2.5gbe nic on proxmox

1. download drivers from
   https://www.realtek.com/en/component/zoo/category/network-interface-controllers-10-100-1000m-gigabit-ethernet-pci-express-software
2. tar vjxf "filename"
3. apt install build-essential
4. apt install pve-headers-6.5.13-1-pve // check version with "uname –r"
5. cd driver's folder
6. ./autorun.sh
