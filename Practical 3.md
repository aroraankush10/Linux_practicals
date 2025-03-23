1. Open the editing_final_lab.txt file in Vim and Nano:
-> VIM- vim editing_final_lab.txt
   NANO- nano editing_final_lab.txt
   ![Screenshot 2025-03-20 155742](https://github.com/user-attachments/assets/a3c6930b-4c81-4d81-a6b6-031f818f5fd0)
   ![Screenshot 2025-03-23 161446](https://github.com/user-attachments/assets/c9c1fbce-34ab-4f63-a0ad-ad49453f79ba)
   ![Screenshot 2025-03-20 160807](https://github.com/user-attachments/assets/eec2af0d-8a3a-4656-8004-d3e5d6d392fc)
   ![Screenshot 2025-03-20 160422](https://github.com/user-attachments/assets/8bd170a7-5911-4732-a424-bc09ee7effbf)
   
2. Use the lab_file shell variable:
-> lab_file="editing_final_lab.txt"
   vim $lab_file
   ![Screenshot 2025-03-20 160947](https://github.com/user-attachments/assets/7c3fad60-00ef-468e-b312-96360ce78b16)

3. Enter visual mode in Vim:
-> Open Vim.
   Press v to enter visual mode.
   ![Screenshot 2025-03-23 161844](https://github.com/user-attachments/assets/5d7e6d0a-4fc1-4c77-bb74-895b218b50dd)

4. Remove the last seven characters from the first line:
-> Press ^ (caret) to go to the beginning of the line.
   Press v to start selecting characters.
   Move to the end of the line using $.
   Press d7 to delete the last 7 characters.

5. Preserve only the first four characters of the first column:
-> Go to the beginning of the line using 0.
   Press v and move to the 4th character using l (right arrow).
   Press d to delete everything after the 4th character.

6. Save and exit:
-> :wq
