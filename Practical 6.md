1. Create the operator1 user:
-> sudo useradd -m operator1
   ![Screenshot 2025-03-20 165609](https://github.com/user-attachments/assets/0382907b-0af1-4c13-8ea8-2fb889e2f9ad)

2. Confirm that operator1 exists:
-> cat /etc/passwd | grep operator1
   ![Screenshot 2025-03-20 165658](https://github.com/user-attachments/assets/c3d65538-74c0-4635-b58b-12aa21354c81)

3. Set the password for operator1:
-> sudo passwd operator1
   ![Screenshot 2025-03-20 165943](https://github.com/user-attachments/assets/116f200c-5722-422f-aa48-b70f05fbf403)

4. Create operator2 and operator3 users:
-> sudo useradd -m operator2
   sudo passwd operator2
   sudo useradd -m operator3
   sudo passwd operator3
   
   ![Screenshot 2025-03-20 170109](https://github.com/user-attachments/assets/544f7760-b138-4c62-9cee-22f75f47fc4a)

5. Update the comment for operator1 using usermod -c:
-> sudo usermod -c "System Operator 1" operator1
   ![Screenshot 2025-03-20 170240](https://github.com/user-attachments/assets/f42fb364-f173-492c-a97b-d3fafdf11e33)

6. Remove the operator3 user:
-> (a)To delete operator3 without removing the home directory:
      sudo userdel operator3
    ![Screenshot 2025-03-20 170340](https://github.com/user-attachments/assets/a1192c8e-d740-4140-8dcb-8b3d0ccaebfe)

      (b)To delete operator3 and its home directory:
      sudo userdel -r operator3
    ![Screenshot 2025-03-20 170450](https://github.com/user-attachments/assets/f328c0ad-69b2-48f6-a5f7-3f53ec58bf8e)


