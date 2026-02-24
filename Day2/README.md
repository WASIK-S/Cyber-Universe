# DAY 2 – Users, Permissions & Important Directories

## 1. What permissions did you modify?

I changed the permissions of `file1.txt` for the owner, group, and all users from **664** to **777**.

- **664** =  
  - Owner: Read and Write  
  - Group: Read and Write  
  - Others: Read only  

- **777** =  
  - Owner: Read, Write, Execute  
  - Group: Read, Write, Execute  
  - Others: Read, Write, Execute  

---

## 2. What happened when the write permission was removed?

When I removed the write permission from the file, I was not able to write anything to that particular file.

---

## 3. Difference Between a Normal User and Root User

In my view, there are some differences between a root user and a normal user:

- **Root User**  
  - Can access and modify anything in the system  
  - Has full control over all files and folders  

- **Normal User**  
  - Can access files and folders based on given permissions  
  - Some files owned by root can only be accessed using the root password  

---

## 4. Why Are Linux Permissions Important?

Linux permissions are important because they protect files and folders from unauthorized access, modification, or deletion.  

They help maintain system security and prevent misuse by restricting access to sensitive data.
