#### command chmod 

chmod ย่อมาจาก "change mode"

#### ownership

- a = All
- u = User 
- g = Group
- o = Other

#### file type

- <strong>-</strong> = File
- d = Directory
- l = Symbolic link

#### permission code

- 0 = No Permission
- 1 = x = Execute หากเป็น file จะสามารถ run หรือ execute ได้ หากเป็น directory จะสามารถ cd เข้าไปได้
- 2 = w = Write
- 4 = r = Read


#### วิธีเปลี่ยน permission directory ใน Linux

    u หมายถึง user owner เจ้าของไฟล์
    g หมายถึง user group
    o หมายถึง other user ผู้ใช้อื่นๆ
    + หมายถึงเพิ่มสิทธ
    - หมายถึงลบสิทธ
    
    เพิ่มสิทธ read, write, execute file
    chmod +rwx <filename>
  
    ลบสิทธ read, write file
    chmod -rw <filename>
  
    เพิ่มสิทธ write file ให้กับ group user 
    chmod g+w <filename>
    
    เพิ่มสิทธ read execute file ให้กับ user owner 
    chmod u+rx <filename>
    
    ลบสิทธ read, write, execute file ให้กับ other user
    chmod o-rwx <filename>
  
### Reference

- https://www.pluralsight.com/blog/it-ops/linux-file-permissions
