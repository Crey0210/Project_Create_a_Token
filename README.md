# Project_Create_a_Token
This project is for the completion of the Solidity Beginner in Metacrafter. 
It has a coded that intended to be used as a kind of practice in making my own token. Although it might not have anything special in particular.
It includes an external mint and burn function that takes two parameters: address and value. 
It was made to be external to limit the access only to other contracts and also to have a cheaper gas usage as public will consume more gas.
The mint function meant to perform increase in the amount of total supply and the balances of the sender of token.
The burn function meant to perform deduction in the amount of total supply and the balances of the sender will then be deducted from that amount.
It has condition that the burn function will only perform if the balances of address of sender is greater than or equal to the amount supposed to be burned.
It will not perform as long as the balances of the sender is less than to avoid getting all balances burned.
