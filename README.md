# project-ansible

roles:
  - docker
  - nvidia-smi
  - nvidia-docker
  - nginx
  - posgresql
  
- Docker Version :18.06.0
- Docker Config : data-root /data
- Nvidia Driver  : Geforce 1050 TI
- Add Grub Line  :
  GRUB_CMDLINE_LINUX="modprobe.blacklist=nouveau"
- Nvidia Docker Version 2
