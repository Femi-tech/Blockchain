# Blockchain


![Configure Genesis](Screenshots/Node-account-setup.PNG)

### Open a terminal window, navigate to the Blockchain-Tools folder and type the following command: ./puppeth
### This should show the following prompt:

![Configure Genesis](Screenshots/puppeth-setup-1.PNG)

### Choose the Clique (Proof of Authority) consensus algorithm.
### Paste both account addresses from the first step one at a time into the list of accounts to seal.
### Paste them again in the list of accounts to pre-fund. There are no block rewards in PoA, so you'll need to pre-fund.
### You can choose no for pre-funding the pre-compiled accounts (0x1 .. 0xff) with wei. This keeps the genesis cleaner.
### Specify your Chain ID.
![Configure Genesis](Screenshots/Configure-Genesis.PNG)
### Next Export your genesis configuration into a your networkname.json file as follows:


### In the puppeth prompt, navigate to the Manage existing genesis by typing 2 and hitting enter.


### You may have to type your network name again first if you're launching puppeth fresh.


### Then, type 2 again to choose the Export genesis configurations option, and continue with the default (current) directory by hitting enter: This will fail to create two of the files, but you only need "networkname.json".
![Configure Genesis](Screenshots/Export-genesis.PNG)

![Configure Genesis](Screenshots/Initialize-Nodes.PNG)

![Configure Genesis](Screenshots/TX-Broadcast.PNG)

![Configure Genesis](Screenshots/UTC-select.PNG)

![Configure Genesis](Screenshots/confirm-transaction.PNG)

![Configure Genesis](Screenshots/homework-node-1-mining.PNG)

![Configure Genesis](Screenshots/homework-node-2-LFP.PNG)

![Configure Genesis](Screenshots/homework-node-2.PNG)

![Configure Genesis](Screenshots/keystore-file-select.PNG)

![Configure Genesis](Screenshots/send-transaction.PNG)

![Configure Genesis](Screenshots/custom-node.PNG)

![Configure Genesis](Screenshots/successful-transaction.PNG)
