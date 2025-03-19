Experiment 4

Question: Create the /home/consultants directory.
Add write permission to the consultants group. Use the symbolic method for setting the appropriate permissions.
Forbid others from accessing files in the /home/consultants directory. Use the octal method for setting the appropriate permissions.
Change the default umask for the operator1 user. The new umask prohibits all access for users that are not in their group. Confirm that the umask is changed.

Step1:- Creating the /home/consultants Directory: The mkdir command is used to create the directory.

![WhatsApp Image 2025-03-19 at 21 35 26_3a6cb22d](https://github.com/user-attachments/assets/aca53a5d-9cb7-40f3-abb2-8c79a44f6936)

Step2:- Adding Write Permission to the consultants Group: The chmod command with the symbolic method is used to grant write permissions to the group.

![WhatsApp Image 2025-03-19 at 21 40 47_ea88624d](https://github.com/user-attachments/assets/4db012f8-1ae1-4b07-a885-4648b671c247)

Step3:- Restricting Access for Others: The chmod command with the octal method is used to restrict access for others.

![WhatsApp Image 2025-03-19 at 21 46 24_9d2f0f5f](https://github.com/user-attachments/assets/7f971129-6e1d-4b34-a6dd-b51313a4f054)

Step4:- Modifying the Default umask for a User: The umask determines the default permissions for newly created files and directories.

![WhatsApp Image 2025-03-19 at 21 58 11_b1d15c92](https://github.com/user-attachments/assets/023842fd-29e7-486f-be78-36867a2091ae)

Explanation: 
umask 007: 
0 (owner): Full permissions.
0 (group): Full permissions.
7 (others): No permissions.

Step5:- Confirming the Updated umask: To confirm the new umask, create a file and a directory, then check their permissions.

![WhatsApp Image 2025-03-19 at 22 04 15_c207c6ba](https://github.com/user-attachments/assets/5b47cf08-e5fe-4b53-9501-feff9bf18923)

Conclusion:- 
In this lab, we practiced: 
Creating directories and managing their permissions using symbolic and octal methods.
Restricting access to specific users and groups.
Configuring the umask to control default permissions for files and directories.
