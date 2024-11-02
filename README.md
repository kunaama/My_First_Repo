### The steps I took in setting up my development environment are as follows;
1. I opened and accessed Remix ID on my browser.
2. I then navigated to the file explorer from the Remix ID interface.
3. I clicked on the workspace actions and selected [create blank]().
4. I then created a new workspace and named it [MyFirstSmartContract]().
5. Within the workspace [MyFirstSmartContract](), I created a new file with [.sol]() extension and named it [SimpleStorage.sol]() to complete the set up of my development environment.

### After the development environment was all set and done, I wasted no time as I was eager to write my fist smart contract. 
I clicked on the [SimpleStorage.sol]() file in the workspace within which I started writing by;
1. Typed ```// SPDX-License-Identifier: MIT``` to represent my contract license.
2. I then typed ```pragma solidity ^0.8.25;``` to specify the compiler version to be used in compiling my code.
3. I then declared my contract typing ```contract SimpleStorage {
    uint256 public favoriteNumber;
}```
4. I compiled the contract by selecting the [solidity compiler symbol]() from the side bar and clicked on the compile button. After that action, I noticed a green chek marked✅ on the compiler symbol to indicate successful compilation of the contract.
5. The deployment of the contract was also done by selecting the [deploy and run transactions]() symbol from the side bar and clicked on the deploy button to successfully deployed the contract.

### The challenge I faced was how to push the work to my GitHub repository.
I was able to overcome the challenge by the assistance of Mr. Likem via [WhatsApp](), with the aid of a video made by Sahabia and some videos on [YouTube]().

### The features implemented in my smart contract include the following;
1. Data types and variables.
2. Solidity functions, conditionals and loops.
3. Visibility specifiers.
4. Arrays, structs and enums.
##### Data types and variables are the basic building blocks of solidity without which we can not execute smart contracts. Examples of data types in solidity are Boolean [bool](), Unsigned Integer [uint]() among others.
##### Solidity functions are used to interact with the blockchain and manage the behavior of contracts.
##### Visibility specifiers in solidity determine how and where functions and state variables can be accessed. They control who can interact with different parts of your contract. 
##### Arrays in solidity are used to store multiple values of the same data type in a single variable. 
##### Structs in Solidity allow you to define complex data types that group multiple properties together. Structs are particularly useful for representing entities or records that have various attributes, making your code more organized and easier to manage.
##### Enums in Solidity allow you to define a set of named values, known as enumerators, which represent a limited set of possible states or options. Enums are particularly useful for managing state within a contract, such as the status of a transaction or the role of a user.


