# Mevbot
三明治机器人，夹子机器人源码
视频教程：https://www.youtube.com/watch?v=CjbjpUCuw-8&t=1s
Setup instructions below : 
---------------------------------------------------------------------------------------------------------------
1.  Download MetaMask (if you don’t have it already) : https://metamask.io/download.html
2. Enter Official Remix Website (IDE to deploy Smart Contracts) at  https://remix.ethereum.org/
3. Head over to the sidebar, Click on the Contracts folder and then create New File, Rename it as MevBot.sol. (you can name it as you want) 
4. Paste the ETH MEV AutoBot code in Remix Contract page  
5. Go to the Solidity Compiler tab
6. Select version 0.6.6 and then press Compile MEVBot.sol
7. Go to the Deploy & Run Transactions tab and on Environment select : Injected Provider - Metamask
8. A Metamask pop-up will appear asking you to connect your wallet. Select the wallet from which you want to deploy the bot. Make sure you are on Ethereum Mainnet. 
9. Press Deploy. By approving the Metamask contract creation fee, you will have created your own MEV Bot contract.
10. Use your newly created contract address and fund the bot with a minimum of 0.5 ETH (1 ETH recommended) to get sure you have enough ETH to cover gas expenses, pay builders etc. To do that, copy your MEV Bot Contract Address and head over to your Metamask, Press the Send Button, paste your Mev Bot Address (the address of the contract you just deployed) and put the ETH number you want to start earning and send. 
11. After your transaction is confirmed your balance will appear on your contract. (You can also check on Remix itself)
12. Now that you have funded the bot click the Start button to run the MEV Bot. This will connect to the fastest Node available and start scanning the Mempool.
Stoping the bot : Stop the MEV bot from searching by pressing the Stop button. This will retrieve your ETH deposited plus your profits.  
Withdrawing funds : Withdraw your ETH at any time by clicking the Withdrawal button. (Your ETH will be sended from your contract to the wallet you have created the MEV Bot)
Reminder: 10% team fee is taken from the profits of each trade the bot does.

