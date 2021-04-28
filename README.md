# Linux

#### Important things to remember

- Linux เป็นระบบที่คำนึงถึงตัวพิมพ์เล็กและใหญ่
- Linux มีบัญชีผู้ดูแลระบบขั้นสูง "root"
- "root" เป็น account สูงสุดที่สามารถสร้างบัญชีลบแก้ไขและทำการเปลี่ยนแปลงระบบได้

#### Linux File System

![linux-filesystem](https://user-images.githubusercontent.com/15135199/100316088-66e4f380-2fec-11eb-9566-b1bea2de44bb.png)

- Commands = /usr/bin
- Attached Device = /dev
- Applications = /etc, /var

### Commands

- Check if port is in use

      sudo lsof -i -P -n | grep LISTEN

- คำสั่งสำหรับแสดง Directory ที่เราใช้งานอยู่ (pwd ย่อมาจากคำว่า Print Working Directory)

      pwd 

- Find Out My Machine Name/Hostname

      hostname 
      hostnamectl
      
 - Vim

![Capture](https://user-images.githubusercontent.com/15135199/111895488-6e218880-8a45-11eb-9dfe-5ad21f8ea040.JPG)

 
### Yum command

[rh_yum_cheatsheet_1214_jcs_print-1.pdf](https://github.com/tirmizee/Linux-Command/files/6177563/rh_yum_cheatsheet_1214_jcs_print-1.pdf)

### Netstat command

- -a : Shows all sockets
- -p : Show related PID
- -t : TCP
- -u : UDP

      netstat -ptau

### Reference

- https://en.wikipedia.org/wiki/List_of_Unix_commands
- https://linuxize.com/post/how-to-remove-files-and-directories-using-linux-command-line/
- https://www.youtube.com/watch?v=XiPJkdwrFnA
- https://www.tecmint.com/start-stop-disable-enable-firewalld-iptables-firewall/
