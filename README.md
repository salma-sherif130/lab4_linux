# lab4_linux
# 1. List **all running processes** and save the output to `~/processes.txt`. 
![image](https://github.com/user-attachments/assets/4a32b425-37bf-4b97-aab6-64fec6897dea)

# 2. Find the **PID (Process ID)** of the `sshd` service.  
![image](https://github.com/user-attachments/assets/999e7563-8145-4bbf-92b5-3ef04cadf599)


# 3. Run a `sleep 500` command in the background, then **kill it** after 5 seconds.  

![image](https://github.com/user-attachments/assets/66f9e781-efa9-4a95-abb9-749850472f73)


4. Install `apache2` service, edit the default HTML file (`/var/www/html/index.html`), and verify changes in a web browser.
![image](https://github.com/user-attachments/assets/60b664d2-2597-4eb4-bf8f-a1063d8b5cf9)

![image](https://github.com/user-attachments/assets/0efa2831-cb6a-45fa-878e-d8a1549d8855)

     
5. **Check if `sshd` (SSH service) is running**. If not, start and enable it.
![image](https://github.com/user-attachments/assets/733e99be-ba85-40cd-abdc-adcc408ca927)

  
6. **Restart the `cron` service** and verify its status.

![image](https://github.com/user-attachments/assets/293539ae-2a63-46fa-aa06-4c7bcf370e2e)
 

7. Create a **compressed tarball** (`archive.tar.gz`) of `/var/log` and save it in your home directory.

![image](https://github.com/user-attachments/assets/79bac0ca-59ce-4ed1-8b8c-091836348b61)

     
8. **Extract** the tarball into `~/logs_backup/`.

![image](https://github.com/user-attachments/assets/2c3c6814-803a-428e-ba76-7c91797c027e)

    
9. Create a **non-compressed tarball** (`archive.tar`) of `/etc/ssh` and save it in `/tmp`.  

![image](https://github.com/user-attachments/assets/94768a01-85ce-4b66-a86c-c85a02474b63)

10. Compress `~/processes.txt` using `gzip`.
![image](https://github.com/user-attachments/assets/45bd332e-d8f6-4103-82ce-5dece5723593)

11. **Decompress** it and compare file sizes using `ls -lh`.

![image](https://github.com/user-attachments/assets/537cc321-e28e-4fb9-8619-5d5506701853)

12. **Install `htop`** (a process viewer) using your package manager.

![image](https://github.com/user-attachments/assets/788bec63-2038-4c57-9d1a-b49493704e87)

![image](https://github.com/user-attachments/assets/028f98de-60c5-4ecf-a528-b9e4095e7c89)

  
13. **Search for the package `nginx`** (or `httpd`) but do not install it.

![image](https://github.com/user-attachments/assets/a1d1731d-0592-444a-91be-17e1d8af1d1d)

 
14. **Remove the `vim` editor** (if installed) and then reinstall it.

![image](https://github.com/user-attachments/assets/75564cde-50c9-4e85-b8bb-db44caa9fc62)
![image](https://github.com/user-attachments/assets/29f666f8-94f2-40a0-afe3-aecf154de212)    

15. Use `wget` to download the Linux kernel source:

![image](https://github.com/user-attachments/assets/2fa52cb4-cf55-4914-9db0-9556df52b5e4)

     
16. Use `curl` to fetch **Google’s homepage** and save it as `google.html`.

![image](https://github.com/user-attachments/assets/4d8e6153-3122-43a6-89ab-9f5d84deccce)


28. **Create a new VM** (e.g., VirtualBox/Cloud instance), add a user to the `sudoers` group, and run `apt update && apt upgrade`.  
29. **Generate an SSH key pair** using `ssh-keygen`.  
30. **Copy your public key** to the remote server:  
31. **SSH into the server** and verify with `hostname`.  
32. **Transfer the archived file** (e.g., `archive.tar.gz`) to the remote server using ssh copy way (don’t copy/paste >>> you have to search)
