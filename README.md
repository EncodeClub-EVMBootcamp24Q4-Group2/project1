# Encode Club EVM Bootcamp, Q4 2024, Group 2, Homework #1

## Summary
This project represents Homework #1 for Group #2 for the Encode Club EVM Bootcamp.  The assignment is defined as:
* Interact with “HelloWorld.sol” within your group to change message strings and change owners
* Write a report with each function execution and the transaction hash, if successful, or the revert reason, if failed

## Members of Group 2

    [ExqPpl](./users/ExqPpl/) - @Kai
    [tJnNuQ](./users/tJnNuQ/) - @xiaodragon9589
    [R9dhTD](./users/R9dhTD/) - @Brian Blank
    [DAaJDn](./users/DAaJDn/) - @💫StarfleetCommand💫
    [lofjwH](./users/lofjwH/) - @zzlovecoffee
    [Mn8EN0](./users/Mn8EN0/) - @ethalorian | KEEZ
    [HPJ2do](./users/HPJ2do/) - @DiegoB

## Contract Information

For this project, we are leveraging the contract provided by the instructor.  Here is the [link to the source code](./scripts/HelloWorld.sol).

The contract was deployed via transaction [0x4537bb7da871ea42111232bce500b874deeb1fed916f54316e59b16b8c77ee31](https://sepolia.etherscan.io/tx/0x4537bb7da871ea42111232bce500b874deeb1fed916f54316e59b16b8c77ee31)

The Smart Contract Address is [0x9cde9097fa2d1c93a0971029e1ab5f93c7898fa3](https://sepolia.etherscan.io/address/0x9cde9097fa2d1c93a0971029e1ab5f93c7898fa3)

## Deployment Process

1. Using https://remix.ethereum.org/ we paste the code in the code editor from [HelloWorld.sol](./scripts/HelloWorld.sol).

2. The solidity code is compiled using the latest Solidity compiler using the Compile Tab.

![Remix Compiler Screen][01RemixCompilerScreen]

3. Next we deploy the compiled bytecode to the Sepolia testnet, leveraging Metamask accounts.

![Remix Deployment Screen][01RemixDeploymentScreen]
![MetaMask Contract Submission Approval Request][01MetaMaskContractSubmissionApprovalRequest]
![MetaMask Contract Deployment Confirmation Dialog][01MetaMaskContractDeploymentConfirmationDialog]
![MetaMask Contract Deployment Confirmation][01MetaMaskContractDeploymentConfirmation]
![MetaMask Contract Transaction List][01MetaMaskContractTransactionList]

4. For the “At Address” field, we populate that by taking the address from the transaction visible at etherscan.  After specifying the “At Address” with the correct address, the contract interface becomes visible in the Remix editor.

![Remix Interface][01RemixInterface]


[01MetaMaskContractDeploymentConfirmation]: ./img/01MetaMaskContractDeploymentConfirmation.png "MetaMask Contract Deployment Confirmation"
[01MetaMaskContractDeploymentConfirmationDialog]: ./img/01MetaMaskContractDeploymentConfirmationDialog.png "MetaMask Contract Deployment Confirmation Dialog"
[01MetaMaskContractSubmissionApprovalRequest]: ./img/01MetaMaskContractSubmissionApprovalRequest.png "MetaMask Contract Submission Approval Request"
[01MetaMaskContractTransactionList]: ./img/01MetaMaskContractTransactionList.png "MetaMask Contract Transaction List"
[01RemixCompilerScreen]: ./img/01RemixCompilerScreen.png "Remix Compiler Screen"
[01RemixDeploymentScreen]: ./img/01RemixDeploymentScreen.png "Remix Deployment Screen"
[01RemixInterface]: ./img/01RemixInterface.png "Remix Interface"
