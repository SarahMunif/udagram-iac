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
