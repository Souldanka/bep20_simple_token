# bep20_simple_token
Simple BEP20 token contract
1. Set your MetaMask wallet to the main BSC network.
2. Open the Remix online application to help deploy and develop a smart contract on the BNB Chain network. Select the "Contracts" folder and create a new file.
3. Give your file a name. Then check that you have the correct programming language installed. In this case, it is Solidity, without it your smart contract will not work.
4. Copy the BEP-20 smart contract code into your document.
5. Change the name, symbol, number of decimal places and general offer according to the parameters of your coin. As an example, we have chosen Dimasik Coin (DMSK) with 18 decimal places and a total supply of 100,000,000 tokens. Don't forget to add zeros to cover 18 decimal places.
6. After the completed steps, compile your smart contract. To do this, check the box Auto Compile and Enable Optimization, then click the 7. Compile button. Next, you will see a window where you need to click on the ABI button to compile the ABI of the contract.
8. Click on the broadcast icon on the left side of the screen. Select [injected Web3] as the environment and then connect MetaMask to the Remix application. Make sure you have selected a BEP20 contract and click [Deploy]. To do this, you will have to pay a transaction fee.
9. After running the smart contract, check the publication of the source code.
10. Go to BSC Scan in the Verify Contract section. Copy the address of the contract into BscScan, select [Solidity (Single)] as the compiler type, and select the compiler version you had in the remix application. We press continue.
11. Then right click BEP20.sol in Remix and click [Flatten]. You will then need to give Remix permission to optimize the code.
12. Copy the code from BEP20_flat.sol into the box and make sure [Optimization] is set to Yes. Click the [Verify and Publish] button at the bottom of the page.
13. You can now mint your token via BscScan using the _mint call function found in the contract. Go to your BscScan contract address and click [Write Contract], then click [Connect to Web3] to connect your MetaMask account.
14. Scroll down to Mint and enter the number of tokens you want to mint. We are going to mint 100,000,000 DMSK. Don't forget to add decimal places in this case 18. Click [Write] and pay the fee in MetaMask.
