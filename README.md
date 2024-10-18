Before a teacher is able to effectively deliver her/his lessons, the classroom must be properly arranged to make it conducive for teaching and learning. 
The situation isn't diffrent when it comes to writing smart contracts on Remix IDE. The following steps are how I managed to set up the development environment;

I. I searched and navigated to Remix IDE in my browser (chrome).
II. I used the file explorer on the interface to create a folder (MyFirstSmartContract) to represent my workspace.
III. In that folder, I created a solidity file named (SimpleStorage.sol) to pave the way for writing my first smart contract.

I started writing the smart contract by stating a license identifier (// SPDX-License-Identifier:  MIT).
I then wrote the compiler directive version (pragma solidity ^0.8.25) whihch will be used to compile my code.
After that, I defined my contract (contract SimpleStorage).
Finally, I concluded by stating a variable (unsigned-integer, uint256 favoriteNumber; and making it public to be accessible by everyone and also declaring 
that variable with a (function store) to be able to test the contract.
I then compiled the contract by utilizing the solidity compiler from the sidebar by clicking on it after ensuring that the compiler version matches the one specified
in my solidity file. I realised there were no issues with my contract when i noticed a green checkmark on the compiler symbol.
The deployment of my contract was done with the aid of the (Deploy & run transactions) symbol from the sidebar. I used the Remix VM (Cancun) and the simulated account for testing locally in the browser.
I then tested the contract by entering the value (1500) into the contract funtion and observed how it responded.

The challenges I faced include, how to add a function to the contract, how to declare the state variable (favoriteNumber), how to connect my GitHub account to Remix and how to push the project from
Remix to GitHub Repository.
I resolved those challenges by watching the tutorial video made by Sahabia and other videos from YouTube, and by the assistance mr. Likem and above all by the use of the Solidity Programming 101 course.



