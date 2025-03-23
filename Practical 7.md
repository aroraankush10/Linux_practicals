1. chown Command
-> (a)Change the owner of a file:
      sudo chown user1 file.txt
   ![Screenshot 2025-03-20 171224](https://github.com/user-attachments/assets/a3ef268b-42df-4391-b966-2cc60f7c13b3)

   (b)Change the owner and group of a file:
      sudo chown user1:usergroup1 file.txt
   ![Screenshot 2025-03-23 155355](https://github.com/user-attachments/assets/5cd60462-cb77-4f61-b5a6-99ae184222c7)

   (c)Change only the group:
      sudo chown :group1 file2.txt
   ![Screenshot 2025-03-23 155457](https://github.com/user-attachments/assets/ffb1c472-95a6-42f4-b769-410805b638ad)

   (d)Change ownership recursively (for directories):
      sudo chown -R user1:usergroup /path/to/directory
   ![Screenshot 2025-03-23 155551](https://github.com/user-attachments/assets/3c8f5ba1-4caa-4f98-9804-2a652a4d27f9)

   (e)Transfer ownership to root:
      sudo chown root file.txt
   ![Screenshot 2025-03-23 155643](https://github.com/user-attachments/assets/e7172684-a440-472a-920e-bbf1dfcdaf18)

   (f)Use --from to change from a specific owner:
      sudo chown --from=current_owner new_owner file.txt
   ![Screenshot 2025-03-23 155819](https://github.com/user-attachments/assets/011ac0e6-e83f-4ccb-bdd3-f4d47455f08a)

2. chmod Command
-> (a)Give execute permission to the user:
      sudo chmod u+x file.txt
   ![Screenshot 2025-03-23 192222](https://github.com/user-attachments/assets/26e105ff-d39b-4ec5-b931-6fa2ed433cf6)


   (b)Remove write permission for others:
      sudo chmod o-w file.txt
   ![Screenshot 2025-03-23 192319](https://github.com/user-attachments/assets/dab95771-46b5-4c01-9830-dcad19a5df56)

   (c)Give read and execute permission to the group:
      sudo chmod g+rx file.txt
   ![Screenshot 2025-03-23 192427](https://github.com/user-attachments/assets/d24e9be4-a80e-4c79-b215-740e0937fbc1)

   (d)Set specific permissions:
      sudo chmod u=rwx,g=rx,o=r file.txt
   ![Screenshot 2025-03-23 192554](https://github.com/user-attachments/assets/9067517f-f3db-48e8-afee-d22ef5fe04d5)

   (e)Set permissions to rwxr-xr-- using octal mode:
      sudo chmod 754 file.txt
   ![Screenshot 2025-03-23 193330](https://github.com/user-attachments/assets/c9888d43-c0bb-4051-b66e-801e34cd4437)

   (f)Recursive Change of Permissions:
      chmod -R 755 /path/to/directory
   ![Screenshot 2025-03-23 193425](https://github.com/user-attachments/assets/48876d2c-2bd8-405c-823a-53f4ee539d05)

   (g)Change permissions based on existing files:
      chmod --reference=ref_file.txt target_file.txt
   ![Screenshot 2025-03-23 193643](https://github.com/user-attachments/assets/e0f90e0d-2f52-4013-93d2-90b5e173a3ef)
