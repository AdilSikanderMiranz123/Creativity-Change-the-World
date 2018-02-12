# Creativity-Change-the-World
Creativity creates innovations, Innovation Change the Behavior of World.

World want to change ! Change occure, when behaviour changes. Due to this Fact, A new technlogy come into the world known as BlockChain.
Any One Knows about it ? 
oops No. now i m going to tell you something about it that are very intersting. Block Chain is the combination of Blocks. so the question is what is block ?
Block is a combination of Data, Hash of current, Hash of Previous Block. Its very Simillar with Double Linked List.

Why BlockChain ? 
Only one reason it does not allow to temper the data. and as well as no one can do something wrong now on social media. its a Decentralized Networks where each node serve as a Distributed Server.
Example: BlockChain =Block + Block + …… + n.

BlockChain Categories into three classification: Public , Private , Consortium or Federated. Public Blockchain scope all over the public anyone can visit and look at the transactions becuase of Decentralized Newtwork.
Where as the Private BlocChain is only the Specific person can See the Transactions, where we specified some layer of organization, only specific layer person can look at the Transaction.
where as Consortium means when 50% people agree to allow the request to see the result, then request be granted.otherwise not.
We Use Some Important Terms in BlockChain. Like ICO and IPO, ICO refers to the concept where we do some Initial Coin Offering. means we are going to introduce some new digital coin in the era. but we have no fund to start it so we do ICO that help us to collect funds from investors , investor holds the Coin when its value incresing then we give them some rewards in the form of Digital Coin.
BlockChain has some Challenges, Like how we can communicate to others securely!, if some middle man get our Shared Secret :O, then it will leads to our investment into destruction.
to Overcome this Challenge another Concept comes in the world that is Symetric and Asymetric. 
In Symetric, We have one Shared secret that both the parties holds and communicate with each other Securly! and it is possible when we are follwing Deffi helmin Algorithm.
on Another Hand we have ASymeteric Concept where we have one Public Key, One Private Key. One key For Encryption and then Second Key is for Decryption.


![center](./blockchain-bitcoin-33-638.jpg)

White Paper of Bitocoin Discription:
Satoshi introduces an electronic payment system based on cryptography. This will allow two parties to interact with each other without a 3rd party getting in the way. Since these cryptographic transactions will be computationally impossible to reverse, users will be protected from fraud.

## Transactions:
The definition of a Bitcoin is a “chain of digital signatures” that can be passed from one person to another using an electronic signature (hash). During this process, the sender passing the Bitcoin onwards, electronically signs the pervious transactions of the Bitcoin and the public key of the recipient they are sending the Bicoin to. 
An analogy to this is signing for a package that you have received and then writing a forwarding address on the package before sending it onwards

## Timestamp server:
The timestamp server is a simple piece of software that is used to digitally timestamp data. The server takes a small section of the transaction data (a hash) and timestamps it. This time stamped hash is then made publicly available for everyone to see. The existence of this time stamped hash therefore proves that the transaction exists and is therefore valid.  

## Proof-of-work & Proof-of-stakes
Bitcoin and Proof of Work. Bitcoin is based on a POW (Proof of Work) system where the probability of mining a block is dependent on how much work is done by the miner. A proof-of-stake (POS) systems varies in that a person can “mine” depending on how many coins they hold

 ## Networking
 
New transactions are “publicly announce” to all nodes >> each node puts all new transactions into a block >> each node works on solving the proof-of-work (earlier described) for its own block >> when a lucky node solves the puzzle for its block, it informs all other nodes >> nodes accept the solved block if ALL transactions are valid and there are no issues of double spending >> nodes move onto next block in chain >> This process then repeats in a loop.

## Incentive:
Transaction fees also act as incentives, which are additional charges added to each transaction. Once the maximum amount of coins (21 Million) have entered the Bitcoin system, the incentive to keep mining Bitcoins solely comes in the form of transaction fees, which are inflation free.  

## Reclaiming Disk Space:
Old transactions can be discarded after a set amount of time to save disk space, the root (a trace) of the discarded transaction will remain so the Blockchain remains intact. 
The development of computer hardware (Moore’s law) will outpace the size of the Blockchain and as such, storing the chain on hardware shouldn’t be a problem.   

## Simplified Payment Verification:
The transaction cannot be checked by an individual node, a person must connect to another node which connects them to the Blockchain. This connection will then verify that the person’s version of the Blockchain is up to date, if not, the Blockchain will update the person version of the Blockchain before continuing.  

## Combining & Splitting Value:
You could pay for an item by sending the recipient one dollar at a time $1... $1... $1... $1 and $1 or alternatively you could add up all your dollars and send them $5. It is more efficient to send the recipient $5 in one transaction and as such this is the method used to send Bitcoins.    
## Privacy:
Although transactions are publicly declared, the public keys that identify individuals are anonymous, and hence the identities of the sender and receiver cannot be determined by the public. It is publicly declared that an amount of money is moving from point A to B, however no identifiable information is openly distributed. This model of identification is similar to the “tape” used by stock exchanges when making their trade information public.
(10) Calculations. 
## Uncles
Miners on the Ethereum network are incentivized to include a number of uncles every time a block is mined. This may sound very strange at first, as it allows “orphaned” blocks to still yield a reward for miners. This is another example of how Ethereum is very different from Bitcoin. In Bitcoin mining, an uncle would yield nothing.
## Problems:
•	First of all, it decreases decentralization in Ethereum mining. Like it or not, but cryptocurrency mining is often a very centralized
activity. 
•	One big potential issue with this uncle system is how it can create incentives for miners -or even pools- to mine empty blocks
•	Do keep in mind including uncles also creates a bit more blockchain “bloat,” which is becoming somewhat of a recent issue with 

## Ethereum.
Solutions for blockchain bloat:
•	Increase Blocksize
•	Use sidechain solutions

## What is Public Key Infrastructure?
A two way (asymmetric) encryption system for communication.
Provide authentication and confidentiality.

## Authentication:
Confirms the owner of the keys using Digital Certificate.
## Confidentiality:
Encrypts data transmission.

## How PKI Works:
You                                				CA (Certified Authority)  _		                      Alice
->You   request Alice certificate to the CA.
->The CA sends Alice certificate to you.
->You encrypts your message using Alice’s verifies public key contained with the CA.
->You send the encrypted message to Alice.
->Alice decrypts the message with her private key.
## Public key infrastructure:
PKI is the framework for encryption that associates a public key with a verified person/system.
## Public key:
The part of the key pair that is available and distributed to the public.
## Private Key:
The part of the key pair that is secret and used only by the key owner.
## Certificate Authority:
CAs are responsible for issuing, revoking, and distributing digital certificates.
## Digital Certificate:
A certificate that verifies whom the public key belongs to .
## Registration Authority:
The RA verifies the prospective key owners identify and sends it to the CA to issue a Certificate.
## Certificate Revocation Lists:
Al list hi certificates that are no longer useable. The list is frequently published.
## Recovery Agent.
A person who is authorized to recover lost private Keys.
## Key Escrow.
Keeping secured copies of private keys for law Enforcement purpose.

# Kerberos by MIT
Network Authentication protocol.

->Provide strong authentication for client/server application by using secret key cryptography.

->Free implementation is available in online side.

->Available in many commercial products as well.

->Some site used firewall to solve network security problems.

Kerberos was created by MIT as a solution to these network security problems. The Kerberos protocol uses strong cryptography so that a client can prove its identity to a server across an insecure network connection. After a client and server has used Kerberos to prove their identity, they can also encrypt all of their communications to assure privacy and data integrity as they go about their business.

## Working of Kerberos:
When the user logins to his or her machine. The principal, is sent to KDC server for login, and the KDC server will provide TGT in return (this request to the KDC server can be sent by the login program).

->Kdc server searches the principal name in the database, on finding the principal, a TGT is generated by the KDC, which will be encrypted by the user’s key, and send back to the user.

->When the user gets the TGT, the user decrypts the TGT with help of the users key).An important fact to note here is that, the client machine stores its key on its own machine only and this is never transmitted over wire.

->The TGT received by the client from the KDC server will be stored in the cache for use for the session duration. There will always be an expiration time set on the TGT offered by the KDC server, so that an expired TGT can never be used by an attacker.

->Now the client has got TGT in hand. If suppose the client needs to communicate with some service on that network, the client will ask the KDC server, for a ticket for that specific service with the help of TGT.















