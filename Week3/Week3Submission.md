

@mitzsuyi @sniperJ @Munzy3.0 @garosan @codewiz42, @alienrobot
enyG1V, VBOgrD, VTn1eM, KXUj9S, 9bEn8R, Ym4XLm


- ERC20 Contract (TokenizedVote) Contract Address = 0x7d621492566230a2272c8ab2422484193a9110aa - https://sepolia.etherscan.io/address/0x7d621492566230a2272c8ab2422484193a9110aa

- TokenizedBallot Contract Address  = 0x49afef6d55453b2460a88efa53e47ac4a40c1df1 - https://sepolia.etherscan.io/address/0x49afef6d55453b2460a88efa53e47ac4a40c1df1

### Short Summary

Developed scripts to interact with the blockchain. First we deployed the ERC20 Contract where the team were all given tokens. Then we deployed the TokenizedBallot contract where we passed the following parameters: 
- proposal names
- contractAddressOnSepolia
- voter wallet address

Then we gave team member voting writes by minting tokens, checked for voting power then voted for multiple proposals. 

### Project Purpose

Learn to interact with ERC20Votes, ERC20 Permit, AccessControl contacts by importing them into our own ERC20 Contract (TokenizedVote) and then passing the contract address as necessary parameter to another contract to TokenizedBallot. 