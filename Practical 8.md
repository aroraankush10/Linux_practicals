1. Shell Script to Print System Information
-> (a)Create a file named system_info.sh:
   ![Screenshot 2025-03-23 210657](https://github.com/user-attachments/assets/cdccc66f-626d-4ce4-9090-4f9c3f53d3ea)

   (b)Make the script executable:
      chmod +x system_info.sh
   
   (c)Run the script:
      ./system_info.sh
   ![Screenshot 2025-03-23 201454](https://github.com/user-attachments/assets/48c0583a-8ca2-42df-a5b6-60b171083fdb)

2. Shell Script to Perform Basic Mathematical Calculation
-> (a)Create a file named calc.sh:
   ![Screenshot 2025-03-23 201011](https://github.com/user-attachments/assets/c3134103-8e94-4f6b-9231-7f9cfb07db3e)

(b)Make the script executable:
chmod +x calc.sh

(c)Run the script:
./calc.sh

![Screenshot 2025-03-23 201634](https://github.com/user-attachments/assets/42abb80a-974f-4c54-b2cf-c77935fe050b)

3. Use Redirection Operators to Store Output of Commands
-> (a)Redirect stdout to a file:
      ls > output.txt
   ![Screenshot 2025-03-23 201759](https://github.com/user-attachments/assets/728445c7-b42e-4052-bd7b-1b981ab1b79c)

   (b)Append output to an existing file:
      date >> output.txt
   ![Screenshot 2025-03-23 203016](https://github.com/user-attachments/assets/a00793a0-0cde-4b2a-9eb7-9b2f47a98b40)
   ![Screenshot 2025-03-23 203508](https://github.com/user-attachments/assets/20f7176b-978a-4ecb-a131-8852e5426bcb)

   (c)Redirect stderr to a file:
      ls nonexistentfile 2> error.txt
   ![Screenshot 2025-03-23 203633](https://github.com/user-attachments/assets/49fb95e7-2b51-487d-b7f8-3b937b9f28cb)

   (d)Redirect both stdout and stderr to a file:
      ls . nonexistentfile &> all_output.txt
   ![Screenshot 2025-03-23 203724](https://github.com/user-attachments/assets/01d6b49b-0f41-49bf-b23c-9f98c20a1805)
   ![Screenshot 2025-03-23 203803](https://github.com/user-attachments/assets/a298cc9b-d266-4e4f-a575-d7dcd58a8d05)

   (e)Pipe output to another command:
      sudo cat file.txt | grep "keyword"
   ![Screenshot 2025-03-23 204220](https://github.com/user-attachments/assets/67639eb4-99f1-4d24-8c90-2ee5b9f0c8b6)

   
