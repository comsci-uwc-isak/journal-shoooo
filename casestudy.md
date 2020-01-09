1. Who/what changes bitcoin difficulty
2. How many miners are needed to run the 51% attack?
3. What are some possible attacks on a blockchain?
4. Are there majore bitcoin servers?
5. Distribution of bitcoin owners?
  30% owners own 98.3%
  1% of world population owns 45%
6. What is a Merkle tree?

Define: nonrepudiation

Nonrepudiation is the assurance that someone cannot deny something. Typically, nonrepudiation refers to the ability to ensure that a party to a contract or a communication cannot deny the authenticity of their signature on a document or the sending of a message that they originated. 

To put simply, nonrepudiation means that in legal terms, one party cannot reject the validity of a certain action or claim of other parties. 

Nonrepudiation ensures the integrity of data all across the internet. In blockchain, digital signature, decentralized database, public and private cryptography help establish nonrepudiation, allowing users to make transactions safely.


Example:
Once Alice creates her digital signature, she then sends it to her recipient, Bob, alongside the data. When Bob receives the data, he can verify its authenticity, check whether it retains its integrity and see whether it is non-repudiable, all by using Alice’s public key.

Alice will most likely have shared her public key with Bob ahead of time, otherwise Bob will be able to find it on a key server (this is a server where many people host their public keys, so that others can find them and contact them in a secure manner).

Bob takes the digital signature and Alice’s public key and computes them together using the reverse of the algorithm that Alice used.

Due to the unique mathematical properties of this calculation, the result will be the same as the hash of Alice’s data from before she digitally signed it with her private key.

Bob then runs the message that he received through the same hash function that Alice used. If this message has not been altered since Alice signed it, then the hash function will give Bob the same result that he got from the computation he performed with Alice’s public key.
https://www.comparitech.com/crypto/cryptography-blockchain/
https://toughnickel.com/personal-finance/Cryptography-Digital-Signatures




Collision
Determinism
Double-spending
Entropy
