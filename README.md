# Linux-Command

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

### Netstat command

- -a : Shows all sockets
- -p : Show related PID
- -t : TCP
- -u : UDP

      netstat -ptau

### Reference

- https://en.wikipedia.org/wiki/List_of_Unix_commands
