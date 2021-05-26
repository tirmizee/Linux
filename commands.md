
### Commands

      root@630a1f8f0dcd 
   
- root คือ user 

- 630a1f8f0dcd คือ hostname

#### echo command

คำสั่งสำหรับใช้แสดงข้อความ

      echo $SHELL
      echo $0
      
- ใช้ $ เพื่อระบุ system variable ที่ชื่อ SHELL

#### uname command

คำสั่งที่พิมพ์ข้อมูลพื้นฐานเกี่ยวกับชื่อระบบปฏิบัติการและฮาร์ดแวร์ระบบ

      uname
      uname -a

#### uptime command

      uptime
      
#### w commad

คำสั่งแสดงว่าผู้ใช้รายใดถูกล็อก

      w

#### ps command

      ps

#### ls command

คำสั่งแสดงรายการไฟล์และไดเร็กทอรีย่อยภายในไดเร็กทอรีปัจจุบัน

      ls
      ls .
      ls /bin

#### ln command

#### pwd command

#### which command

คำสั่งแสดงเส้นทางของ executable file.


#### hostname

      hostname -i

#### mkdir command

- สร้าง directory

      mkdir test
      
- สร้าง directory พร้อม subdirectory

      mkdir -p test/test2

#### kill command

      kill 62514

#### cat command

      cat logs.txt


#### head command

- แสดงข้อมูลจาก large-file.txt 2 บรรทัดแรก

      head -n 2 large-file.txt

#### tail command

- แสดงขอมูลจาก log.txt แบบ realtime

      tail -f log.txt

- แสดงข้อมูลจาก large-file.txt 5 บรรทัดแรก

      tail -n 5 large-file.txt

#### grep command

- xxx

      cat large-file.txt | grep days

- xxx

      grep days large-file.txt

- filter text ที่ขึ้นต้นด้วย l

      ls -l | grep ^l

- filter text ที่สิ้นสุดด้วย ch

      ls -l | grep ch$

#### more command

#### rm command

- ลบไฟล์เดียว

      rm log.txt
      
- ลบไฟล์ทั้งหมดที่มีนามสกุล .txt โดยใช้ wildcard

      rm *.txt

- ลบ directory

      rm -r test

#### cp command

- copy file source.txt ไปยัง file backup.txt

      cp source.txt backuo.txt

- copy file จาก path /etc/host.conf ไปยัง file backup.conf

      cp /etc/host.conf backup.conf

- copy /etc directory ไปยัง etc-backup directory

      cp -r /etc etc-backup

#### mv command

#### touch command

#### find command

- ค้นหาชื่อ file ที่เป็น txt จาก directory ปัจจุบัน

      find . -name "*.txt"

- size

      find / -type f -size +1M -ls

#### tar command

#### history command

#### man command

ใช้เพื่อแสดง user manual ของคำสั่งใด ๆ ที่เราสามารถใช้บนเทอร์มินัล

#### command option

- ใช้ - ตามด้วยชื่อย่อ
- ใช้ -- ตามด้วยชื่อเต็ม

      ls -a
      ls --all
      ls -l
      ls -la

### Shortcut

- Ctrl + a เลื่อน cursor ไปที่จุดเริ่มต้นของ command 
- Ctrl + e เลื่อน cursor ไปที่จุดสิ้นสุดของ command 

### Reference

- https://linux.die.net/man
