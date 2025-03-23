1. ps Command
-> (a)Display all running processes:
      ps aux
   ![Screenshot 2025-03-20 163139](https://github.com/user-attachments/assets/f8e99fa3-fe74-48c8-bc75-fb1df3b2bc95)

   (b)Show processes for the current terminal session:
      ps
   
   ![Screenshot 2025-03-20 163207](https://github.com/user-attachments/assets/c1c91547-5791-4766-93aa-991a88c4dc6a)

   (c)Display a process tree:
      ps -e --forest
   ![Screenshot 2025-03-20 163322](https://github.com/user-attachments/assets/bffd9c4c-37b9-4cae-a14f-4934aec9de4c)

   (d)Filter by process name:
   
      ps -C firefox
   
   ![Screenshot 2025-03-20 163511](https://github.com/user-attachments/assets/d0a7072d-7cbe-4e07-b656-80e943be897c)

   (e)Show detailed information of a specific process:
      ps -p 1234 -o pid,ppid,cmd,%mem,%cpu
   ![Screenshot 2025-03-20 163651](https://github.com/user-attachments/assets/9fedebe6-ba2b-465a-82fc-81b9b4f9ca4e)

2. kill Command
-> (a)Find the PID: 
      ps aux | grep firefox
   ![Screenshot 2025-03-20 163729](https://github.com/user-attachments/assets/0eaefb41-2519-47b4-87c0-d10866793a59)

   (b)Kill a process by PID:
      kill 1234

   (c)Force kill a process: 
      kill -9 1234

   (d)Kill by process name: 
      killall firefox

3. top Command
-> top
   Sort by memory usage: Press M
   Sort by CPU usage: Press P
   Kill a process: Press k → Enter the PID
   Exit top: Press q
   ![Screenshot 2025-03-20 163858](https://github.com/user-attachments/assets/febe0535-6d11-491e-a9a4-95e6ba3d1bc4)

4. apt-get Command
-> (a)Update package list:
      sudo apt-get update
   ![Screenshot 2025-03-20 164051](https://github.com/user-attachments/assets/0bc5cb50-ac56-40a8-9e11-e7a971ab6bf9)

   (b)Upgrade installed packages:
      sudo apt-get upgrade
   ![Screenshot 2025-03-20 164810](https://github.com/user-attachments/assets/f1b02a40-e5c9-4805-a5b8-ed9ca8ae6bc0)

   (c)Install a package:
      sudo apt-get install vim
   ![Screenshot 2025-03-23 164806](https://github.com/user-attachments/assets/0cc32ff8-5619-43f5-a136-eae78f17c459)

   (d)Remove a package:
      sudo apt-get remove vim
   ![Screenshot 2025-03-20 165223](https://github.com/user-attachments/assets/0484da9f-a878-4b3f-b1e5-805eddf51086)
   
   (e)Remove package along with configuration files:
      sudo apt-get purge vim
   ![Screenshot 2025-03-20 165253](https://github.com/user-attachments/assets/afe3d448-9910-4bfd-9645-67d58d042ab0)

   (f)Clean up unused packages:
      sudo apt-get autoremove
   ![Screenshot 2025-03-20 165347](https://github.com/user-attachments/assets/cedfa393-7568-4bf6-a9bc-8e2e64ae6c8a)

   (g)Clean package cache:
      sudo apt-get clean
   ![Screenshot 2025-03-20 165459](https://github.com/user-attachments/assets/19a6099f-de43-495c-ac66-8f1d3404d8e6)

