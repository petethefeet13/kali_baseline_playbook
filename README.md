# kali_baseline_playbook

 Handy Ansible script to install a number of tools.
 I have a number of files locally that I upload, Cobalt Strike
 Burp Installer and some launchers.
 
 These are in the following structure:

 /Files
  |- Burp
   - burpsuite_pro_linux_v2020_5.sh
  |- Cobalt
   |- Cobaltstrike-v3
   |- Cobaltstrike-v4
    - .cobaltstrike.licence
    - cobalt.desktop
  |- Misc
   - postman.desktop

 Make sure your SSH keys are in for root user and you have PermitRootLogin to 'yes' or 'prohibit-password'
 kali_baseline_playbook
