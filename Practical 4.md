1. Create the /home/consultants directory:
-> sudo mkdir /home/consultants
   ![Screenshot 2025-03-20 161512](https://github.com/user-attachments/assets/318f3108-82bc-4d96-93d0-b9c4ad125f33)

2. Add write permission to the consultants group (symbolic method):
-> sudo chmod g+w /home/consultants
   ![Screenshot 2025-03-20 161557](https://github.com/user-attachments/assets/6ae4802e-a421-4eb2-9dd6-6d9fc1d815ca)

3. Forbid others from accessing the /home/consultants directory (octal method):
-> sudo chmod 750 /home/consultants
   ![Screenshot 2025-03-20 161649](https://github.com/user-attachments/assets/c38b7afa-564e-447e-8a17-6a1100a07216)
   ![Screenshot 2025-03-20 161808](https://github.com/user-attachments/assets/33377dbe-bc9b-43c4-9544-b311f703a125)

4. Change the default umask for the operator1 user:

   (a)Open the user’s .bashrc or .profile file:
     -> sudo nano /home/operator1/.bashrc
   
   ![Screenshot 2025-03-20 162847](https://github.com/user-attachments/assets/7f9eb8ff-b2fa-43b7-ba07-825f21ae20bc)

   (b)Add the following line to set the umask:
   
      umask 0074
   ![Screenshot 2025-03-20 162452](https://github.com/user-attachments/assets/39c0212c-f408-45ae-a304-695ab9213840)
   ![Screenshot 2025-03-20 162602](https://github.com/user-attachments/assets/55d2e6c0-1fff-488d-a75c-4933a1b85999)

5. Confirm the umask:
-> su - operator1
   umask
   
   ![Screenshot 2025-03-20 163027](https://github.com/user-attachments/assets/94a06fbf-a2df-4673-83a7-c2c22925ceda)

