# Create a blockchain-using-a-python

Blockchain is a shared, immutable digital technique that stores transactions over a decentralized network of computers.

# Screen-shots

![how-blockchain-work](https://user-images.githubusercontent.com/86722467/180414371-a23649f7-8e30-4962-b2a5-73c104210969.png)
![blockchain_screenshot](https://user-images.githubusercontent.com/86722467/180414813-6cc55bad-11e9-4d9e-80de-578ebe6e1b68.png)

# Usage/Examples

Module to generate encrypted messges:
```
import hashlib
```

Create object of class Blockchain:

myblockchain=Blockchain()

Store transactions in the form of strings:

t1='Vansh sends Rs. 5 to Shaurya'
t2='Shaurya sends Rs. 20  to Tushar'
t3='Tushar sends Rs. 40 to Rohit'
t4='Rohit sends Rs. 11 to Ritik'

Now create a Blockchain:

myblockchain.create_block_from_transactions([t1, t2])
myblockchain.create_block_from_transactions([t3,t4])

Print the Blockchain:

myblockchain.display_chain()
