_Simple MessageSender_Solidity_<br>
<h6>This is a smart contract written in the Solidity programming language for a decentralized message storage system on the Ethereum blockchain. The purpose of the contract is to store a single message, and allow the owner of the contract to update it.<br>

The contract has three public state variables:

"changeCounter" - An unsigned integer that keeps track of the number of times the message has been updated.<br>
"owner" - The Ethereum address of the contract owner.<br>
"theMessage" - The message being stored in the contract.<br>
The contract has a constructor function that is called when the contract is deployed on the blockchain. This function sets the "owner" variable to the address of the contract deployer.<br>

The contract also has a function called "updateTheMessage", which allows the owner to update the message stored in the contract. The function takes in a new message as an argument, and updates the "theMessage" variable. The "changeCounter" is also incremented every time the message is updated. The update can only be made if the sender of the message is the same as the owner of the contract, as indicated by the if statement in the function.</h6>
