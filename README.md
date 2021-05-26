# Linux for beginners

#### Important things to remember

- Linux มีบัญชีผู้ดูแลระบบขั้นสูง "root"
- "root" เป็น account สูงสุดที่สามารถสร้างบัญชีลบแก้ไขและทำการเปลี่ยนแปลงระบบได้

#### Linux File System

![linux-filesystem](https://user-images.githubusercontent.com/15135199/100316088-66e4f380-2fec-11eb-9566-b1bea2de44bb.png)

- / คือ root directory สำหรับไฟล์และโฟลเดอร์ทั้งหมดใน Linux
- /root คือ home directory สำหรับ root user
- Commands = /usr/bin
- Attached Device = /dev
- Applications = /etc, /var

#### Permissions and ownership of the files

| 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 10 | 
| <strong>-</strong> | - | - | - | - | - | - | - | - | - |


- e (Execute)
- r (Read)
- w (Write)
- d (Directory)
- l (Symbolic link)
- <string>-</strong> (non)


### Reference

- https://en.wikipedia.org/wiki/List_of_Unix_commands
- https://linuxize.com/post/how-to-remove-files-and-directories-using-linux-command-line/
- https://www.youtube.com/watch?v=XiPJkdwrFnA
- https://www.tecmint.com/start-stop-disable-enable-firewalld-iptables-firewall/
- https://poundxi.com/%E0%B8%AD%E0%B8%98%E0%B8%B4%E0%B8%9A%E0%B8%B2%E0%B8%A2%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87-chmod-%E0%B8%9A%E0%B8%99-linux/#:~:text=chmod%20%E0%B9%80%E0%B8%9B%E0%B9%87%E0%B8%99%E0%B8%84%E0%B8%B3%E0%B8%AA%E0%B8%B1%E0%B9%88%E0%B8%87%E0%B8%9A%E0%B8%99,%E0%B8%87%E0%B8%B2%E0%B8%99%E0%B9%82%E0%B8%94%E0%B8%A2%E0%B9%83%E0%B8%84%E0%B8%A3%E0%B9%84%E0%B8%94%E0%B9%89%E0%B8%9A%E0%B9%89%E0%B8%B2%E0%B8%87
- https://www.liquidweb.com/kb/an-introduction-to-firewalld/#:~:text=firewalld%20uses%20the%20command%20line%20utility%20firewall-cmd%20to,disable%2C%20start%2C%20stop%2C%20and%20restart%20the%20firewalld%20service.
- https://spalinux.com/2015/06/centos-7-basic-configure-firewall-by-firewall-cmd ( firewall-cmd commands)
- https://linuxhint.com/cat_command_linux/ ( cat commands)
- https://www.dwthai.com/dwarticle/?t=4&aid=165&atitle=CHMOD+%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%84%E0%B8%A7%E0%B8%A3%E0%B8%A3%E0%B8%B9%E0%B9%89%E0%B8%88%E0%B8%B1%E0%B8%81+%28Permission+on+Web+Hosting%29 (permission)
