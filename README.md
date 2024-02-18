# active-iommu-proxmox

START

1. nano /etc/default/grub
2. GRUB_CMDLINE_LINUX_DEFAULT="quiet" > GRUB_CMDLINE_LINUX_DEFAULT="quiet intel_iommu=on iommu=pt kvm.ignore_msrs=1 video=vesafb:off video=efifb:off intremap=no_x2apic_optout"
3. update-grub
4. reboot

END
