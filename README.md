# Avalanche_Subnet_Project-
This project will guide you through creating a custom EVM subnet on the Avalanche network, defining your own native currency, connecting your EVM subnet to Metamask, and deploying the basic building blocks of your DeFi Kingdom clone game using Solidity and Remix.
## Step 1: Deploy your EVM subnet using the Avalanche CLI
### Step 1: Install Avalanche CLI

`curl -sSfL https://raw.githubusercontent.com/ava-labs/avalanche-cli/main/scripts/install.sh | sh -s`
### Step 2: Create a New Subnet
Use the Avalanche CLI to create a new subnet:

``avalanche subnet create mySubnet``
### Step 3: Configure the EVM
Select the EVM (Ethereum Virtual Machine) as the VM for your subnet:

``avalanche subnet configure mySubnet --evm``

### Step 4: Deploy the Subnet Locally
Deploy your subnet locally to test it:

`avalanche subnet deploy mySubnet --local`


![Screenshot 2024-07-14 224051](https://github.com/user-attachments/assets/a27b54f4-a726-463b-984c-d2f914149418)


![Screenshot 2024-07-14 224105](https://github.com/user-attachments/assets/612fb568-c34a-44e4-a2f9-1a8834ee7ac8)

## Step 2:Add your Subnet to Metamask

To configure MetaMask to connect to your subnet:

* Open MetaMask and go to the "Networks" dropdown.
* Click "Add Network" and fill in the following details:
     * Network Name: Your Subnet Name
     * RPC URL: The RPC URL provided during the deployment process
     * Chain ID: The chain ID of your subnet
     * Currency Symbol: AVAX (or your custom token symbol)
 
  ![image](https://github.com/user-attachments/assets/518aa472-3d77-4659-82b8-3dd11ec4f8ce)

       
## Step 3: Connect Remix to your Metamask
  Use the Injected Provider
  ![image](https://github.com/user-attachments/assets/f2960aa0-8da3-413c-8ecd-be8ff1cd1413)
## Step 4: Deploy the smart-contracts
here are transaction done through this smart contract 

  ![image](https://github.com/user-attachments/assets/82df3337-db1e-4fe5-8dc4-bcd977f3e6fb)

