Prerequisites
AWS CLI installed and configured.

Deployment Scripts
The project includes three helper scripts to automate the stack lifecycle. Make sure to give them execution permissions: chmod +x create.sh update.sh delete.sh

1. Create Infrastructure

To deploy the stacks for the first time:

Bash
./create.sh <stack-name> <template-file> <parameters-file>
Example:

Bash
./create.sh udagram-network network.yml network-params.json
2. Update Infrastructure

To apply changes to an existing stack:

Bash
./update.sh <stack-name> <template-file> <parameters-file>
3. Delete Infrastructure

dete stack :
Bash
./delete.sh <stack-name>
Infrastructure Components


##  Infrastructure Diagram

You can view the full infrastructure diagram for this project here:

👉 [View Infrastructure Diagram (Lucidchart)](https://lucid.app/lucidchart/4e17d975-c0dc-4f76-8255-8c99418dfa80/edit?viewport_loc=-13144%2C-7533%2C21947%2C15714%2C0_0&invitationId=inv_84a5e66c-e8c9-4374-b669-f3e3267c0551)
##  Output screenshot 
<img width="1510" height="251" alt="Screenshot 2025-12-28 at 10 25 16" src="https://github.com/user-attachments/assets/ebbda952-2e48-42e6-b233-68657e974e89" />
<img width="1506" height="947" alt="Screenshot 2025-12-28 at 10 23 19" src="https://github.com/user-attachments/assets/1a0da684-00d8-468f-a3be-3a6d94e9b738" />

<img width="1506" height="947" alt="Screenshot 2025-12-28 at 10 23 11" src="https://github.com/user-attachments/assets/af0c9c0a-bb44-4a0c-b8d4-5835300c94fd" />
<img width="1508" height="703" alt="Screenshot 2025-12-28 at 10 21 42" src="https://github.com/user-attachments/assets/a1995a52-175d-46f6-afef-a73b9a91f9c5" />




