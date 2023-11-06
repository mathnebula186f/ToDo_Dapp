# ToDo DApp


A simple decentralized TodoList application built using React in the front end and Move for the smart contract in the backend. This project demonstrates the basic integration of a frontend application with a blockchain backend.



## Features

- Create, read and checkMark todo items.
- All data is securely stored on the Aptos blockchain.
- App.js in the frontend is used for interacting with the smart contract.
- User-friendly interface for managing your tasks.


### Installation

1. Clone the repository to your local machine:

```bash
git clone https://github.com/your-username/todo-list-dapp.git
```
### How to Run
1.Install Aptos dependency  using following Command and Add it to environment Variable of your device.

    iwr "https://aptos.dev/scripts/install_cli.py" -useb | Select-Object -ExpandProperty Content | python3

2. Compile the smart Contract.

    ```
    cd move
    aptos move compile
    ```
3. Publish the Smart Contract on the Aptos Blockchain.

    ```
    aptos move publish
    ```
4. Make an Account on the aptos DevNet and Install the DevNet Extension.
5. Start the Front End

  ```
     cd ..
     cd client
     npm start
  ```
6.Now you can add and Complete tasks

    
