## Step - 1 : Install Ganache
- Go to https://trufflesuite.com/ganache/
![Ganache](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2006-59-11.png)
- Download the latest version of Ganache
- Go to the folder where you have downloaded Ganache
- Open a terminal from the folder
  
1. Change the execution mode

``` sudo chmod a+x ganache-2.7.1-linux-x86_64.AppImage ```

![terminal_0](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2006-56-06.png)

2. Install libfuse2

``` sudo apt-get install fuse libfuse2 ```

![terminal_1](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2006-55-47.png)

3. Run the Ganache Image

``` ./ganache-2.7.1-linux-x86_64.AppImage ```

![terminal_2](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2006-54-59.png)

- Flash Screen of Gananche

![gananche](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2006-42-35.png)

- Click on QuickStart

![gananche](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2006-43-08.png)

- Accounts created in Gananche

![gananche](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2006-43-25.png)

- Genesis Block created

![ganache](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2006-43-37.png)

- Contents of Block 0

![gananche](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2006-44-23.png)

- Log

![gananche](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2006-44-06.png)

## Step - 2 : Connect Metamask with Ganache

1. Login to Metamask Wallet
2. Add Ganache Test Network with the following credentials
   - Network Name : **Ganache**
   - New RPC URL : **HTTP://127.0.0.1:7545**
   - Chain ID : **1337**
   - Currency Symbol : **ETH**

![Ganache](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2011-09-24.png)

3. Add Accounts from Ganache into Metamask
   
- Open the Ganache IDE, clicl on the privatre key for any account. Copy the Private Key

![Ganache](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2011-18-12.png)

- Go to Matamask, select **Import Account** option. 

![Ganache](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2011-30-40.png)

- Paste the Private Key of the Account. Click on **Import** button.

![Ganache](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2011-32-17.png)

- Check the status of Account added to the Metamask
  
![Ganache](https://github.com/LifnaJos/develop-test-and-deploy-smart-contract-using-Ganache/blob/main/Screenshot%20from%202023-09-18%2011-32-30.png)
 
## Step - 3 : Connect Remix IDE with Metamask
1. 
