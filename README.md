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
      
- chmod เป็นคำสั่งบน Linux ที่ใช้สำหรับกำหนดสิทธิ์ read, write หรือ execute ให้กับ file หรือ directory ว่าจะให้มีสิทธิ์ใช้งานแบบไหน และใช้งานโดยใครได้บ้าง
      
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
- https://poundxi.com/%E0%B8%AD%E0%B8%98%E0%B8%B4%E0%B8%9A%E0%B8%B2%E0%B8%A2%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-chmod-%E0%B8%9A%E0%B8%99-linux/#:~:text=chmod%20%E0%B9%80%E0%B8%9B%E0%B9%87%E0%B8%99%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87%E0%B8%9A%E0%B8%99,%E0%B8%87%E0%B8%B2%E0%B8%99%E0%B9%82%E0%B8%94%E0%B8%A2%E0%B9%83%E0%B8%84%E0%B8%A3%E0%B9%84%E0%B8%94%E0%B9%89%E0%B8%9A%E0%B9%89%E0%B8%B2%E0%B8%87
- https://www.liquidweb.com/kb/an-introduction-to-firewalld/#:~:text=firewalld%20uses%20the%20command%20line%20utility%20firewall-cmd%20to,disable%2C%20start%2C%20stop%2C%20and%20restart%20the%20firewalld%20service.
- https://spalinux.com/2015/06/centos-7-basic-configure-firewall-by-firewall-cmd
