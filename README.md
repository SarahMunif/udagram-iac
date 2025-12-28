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
