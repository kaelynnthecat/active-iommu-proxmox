# active-iommu-proxmox
<br>
nano /etc/default/grub
<br>
GRUB_CMDLINE_LINUX_DEFAULT="quiet" > GRUB_CMDLINE_LINUX_DEFAULT="quiet intel_iommu=on iommu=pt kvm.ignore_msrs=1 video=vesafb:off video=efifb:off intremap=no_x2apic_optout"
<br>
update-grub
<br>
reboot
