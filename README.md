# Tip ETH to anyone

How would we tip anyone in ETH, simply by sending to their digital identity? This unlocks the ability to interact and transact with anyone, without needing to know the recipient's web3 wallet address. Nor do you need to wait, or rely on, social platforms to build a wallet function as a user or a dev, making it simple to bypass integration complexities.

**An experiment**:

This forms the basis of an extremely lightweight way to interact AND transact with anyone on the web2 and web3 internet, across any internet identifier [1], across any platform, in a web3 way. 

How it works: 
* You connect your ethereum wallet
* You send a tip offer to @TwitterID
* The smart contract locks/holds the ETH in escrow
* You send a tweet or DM to @TwitterID to let them know they have received a tip
* If they are the genuine @TwitterID, then only they can log-in (and attest) they are the owner of the handle to claim the ETH
* The Attestation certificate serves as the right to claim the ETH tip from the contract, without revealing their authentication credentials or further information (such as wallet address) to any other party

Key properties: 
* not require access to a centralised authority or platform's verification system, eg Twitter Blue Tick.
* use cases where pseudonymous internet identifiers can satisfy the interaction, without compromising the txn.
* specifically, avoid sovereign identity to verify as KYC information is vulnerable PII
* a systematic way to interact with web3, so you "plug-in" only once to interface across all web2 social platforms!
* this version is peer to peer (meaning, entity to entity, individual to entity and vice versa).

Will build with: 
* EVM Smart Contracts for Ethereum Testnet
  So this is onchain and open for anyone to query and verify that interaction. 
* Attestations, a TokenScript component.
  This generates the Attestation certificate, using zk, for any 3rd party who needs proof to verify.
* Attestation.id.

ID Expansion pack:   
  We start with a Twitter handle, but any public web2 internet identifier will work.
  
  This can be: 
* a Discord account
* a Reddit account
* a PGP key
* an 0x wallet address or ENS Name
* a peice of content or object on IPFS
* any decentralised, or centralised, social network
* any other services or platforms being built by devs

Some considerations during the build:
* tradeoffs
* improvements
* implementation conditions
* differences in onboarding

This forms the project submission to ETHGlobal Online Hackathon.

### References: 
[1] RFC5322 Internet Identifier Message Format: https://datatracker.ietf.org/doc/html/rfc5322#section-3.4.1
