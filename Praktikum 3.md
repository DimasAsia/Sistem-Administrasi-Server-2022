# Adminitration System Practical Reports 3
Muhammad Rafi Irzam (1202190063) & Galih Dimas Prastowo (1202190018)
## Practical Question
https://github.com/aldonesia/Sistem-Administrasi-Server-2021/blob/master/modul-3/silabus.md
## 1. mengautomasikan subdomain dev.vm.local dengan ansible
   ```bash
   Cd ansible/Sistem-Administrasi-Server-2022/ansible/Laravel
   nano deploy-tambahan.yml
   ```
   ![13](https://user-images.githubusercontent.com/92965284/146410110-86f40965-6820-4a0f-af18-052951b6ac7c.png)
   
   ```bash
   ansible-playbook -i hosts deploy-tambahan.yml -k
   ```
   ![14](https://user-images.githubusercontent.com/92965284/146410473-9efe3de1-6601-4be5-a5b5-a62509cca2ec.png)

   ```bash
   nano etc/hosts
   ```
