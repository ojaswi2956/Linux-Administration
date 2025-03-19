Experiment 3

Question:- Use Vim,nano, to edit the editing_final_lab.txt file. Use the lab_file shell variable. 
Enter the visual mode of Vim. Remove the last seven characters from the first column on the first line. 
Preserve only the first four characters of the first column.

Step1: Preparing the Lab File:- Ensure the file editing_final_lab.txt exists. If not, create it using: touch editing_final_lab.txt

![WhatsApp Image 2025-03-19 at 20 41 05_823d93ed](https://github.com/user-attachments/assets/bd5db063-f344-4272-a15d-9892c483eaea)

Step2: Editing with Nano:- Nano is a beginner-friendly text editor.

![WhatsApp Image 2025-03-19 at 20 50 42_b7d217b3](https://github.com/user-attachments/assets/d3c016eb-0d63-47ca-9f4e-5c8a0a8179b6)
![WhatsApp Image 2025-03-19 at 20 51 31_d7fb819f](https://github.com/user-attachments/assets/bf9e72e7-f227-4af8-bb0c-00011c9a30fd)

Step3: Editing with Vim:- Vim is a powerful text editor with advanced features.
1. Open the file in Vim: vim $lab_file
2. Delete the Last Seven Characters of the First Line:
3. Enter visual mode (v), highlight the last seven characters, and press d.
4. Keep Only the First Four Characters of the First Line:
5. Move to the start of the line, press 4l, enter visual mode (v), highlight the rest, and press d.
6. Save and exit: Press ESC, type :wq, and press Enter.

![WhatsApp Image 2025-03-19 at 20 57 10_76601b95](https://github.com/user-attachments/assets/2cfd8fe7-0a28-4492-a754-b69a097d8bb5)

Step4: Verifying Command Execution:- To confirm the changes, display the file's contents: cat $lab_file

![WhatsApp Image 2025-03-19 at 21 04 20_84372ef6](https://github.com/user-attachments/assets/2ddd06da-454c-4872-9b1f-46ec50226279)

Step5: Conclusion:- 
In this lab, you learned how to:
Use Nano for basic file editing.
Use Vim for advanced text manipulation, including deleting specific characters and retaining selected portions of text.
