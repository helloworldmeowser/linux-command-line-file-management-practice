# linux-command-line-file-management-practice
Hands-on Bash lab demonstrating Linux file system navigation, file creation, and directory management in Azure VM

Project Overview

This project demonstrates Linux command-line file management by building and editing a structured zoo file system with the right categorized animal directories and text files.

Skills practiced:
- Linux navigation
- Bash commands
- File Creation
- Directory managment
- Azure VM administration
- Troubleshooting

Commands Used:
- cd
- mkdir
- ls
- pwd
- tree
- echo
- touch

Step 1: create the Zoo Folder

Bash
- cd unit2
- mkdir zoo
- ls

<img width="396" height="150" alt="image" src="https://github.com/user-attachments/assets/421b349e-9f14-4d99-bc3d-8ae504b3150d" />

Step 2: enter Zoo Folder

Bash
- cd zoo
- pwd

<img width="436" height="103" alt="image" src="https://github.com/user-attachments/assets/46ab6ae5-84ae-4956-a1a1-bebaeceb9f8a" />

Step 3: Create Animal Sections

Bash
- mkdir big_cats birds reptiles
- ls

<img width="355" height="264" alt="image" src="https://github.com/user-attachments/assets/e8c87fe5-75eb-4a6c-a3f7-75de80186fe5" />
<img width="399" height="100" alt="image" src="https://github.com/user-attachments/assets/62f95aaa-18bf-4640-874d-ded77e52b464" />

Step 4: Verify Structure

Bash 
- Tree

<img width="355" height="106" alt="image" src="https://github.com/user-attachments/assets/e2eb048d-b86f-4d42-b9f6-5ded3a84d1d9" />

Step 5: Create Animal Files

Bash
- echo "African Lion" > big_cats/African_Lion.txt
- echo "Siberian Tiger" > big_cats/Siberian_Tiger.txt
- echo "Snow Leopard" > big_cats/Snow_Leopard.txt

- echo "African Grey Parrot" > birds/African_Grey_Parrot.txt
- echo "Peregrine Falcon" > birds/Peregrine_Falcon.txt
- echo "Scarlet Macaw" > birds/Scarlet_Macaw.txt

- echo "Blue Tongued Skink" > reptiles/Blue_Tongued_Skink.txt
- echo "Galapagos Tortoise" > reptiles/Galapagos_Tortoise.txt
- echo "Komodo Dragon" > reptiles/Komodo_Dragon.txt

<img width="465" height="223" alt="image" src="https://github.com/user-attachments/assets/26834fa6-d372-4d8e-a058-a6ab3773bb0a" />

Final 

Bash
- Tree
<img width="267" height="144" alt="image" src="https://github.com/user-attachments/assets/d7c13e58-108d-42a6-b495-4888f44c6d55" />








