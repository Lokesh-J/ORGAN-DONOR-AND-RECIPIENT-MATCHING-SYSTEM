# ORGAN-DONOR-AND-RECIPIENT-MATCHING-SYSTEM 

We used mac for the installation. Please refer to the installations as per the OS. 
1. Install npm and nodejs:
• brew install node
• node -v
• npm -v

2. Install metamask chrome extension and create an account.

3. Download and install ganache from 

• https://www.trufflesuite.com/ganache

4. Link ganache account to metamask by using the private key through a 
custom rpc at http://127.0.0.1:7545


5. Install truffle 
• npm install -g truffle

6. Create a truffle project
• mkdir DAppLife
• cd DAppLife
• truffle unbox metacoin

7. Once this operation is completed, you will see a project structure with 
following items
• Contracts/: directory for solidity contracts
• Migrations/:directory for scriptable deployment files
• Test/:directory for test files
• Truffle-config.js: truffle configuration files
Copy and paste the files from the folder to its corresponding folder 
location in truffle

8. Compile and run migrations
• truffle compile
• truffle migrate –reset

9. Run your project 
• Npm run dev 


