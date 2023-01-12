# voting-system-blockchain
Blockchain idea for voting systems

The voting process would begin by creating a decentralized ledger on a blockchain network to record all votes in real-time. This ledger would be maintained by a network of nodes that would work together to ensure the integrity and security of the voting process.

To ensure that only eligible citizens can vote, states would issue tokens to U.S. citizens using their social security number (SSN) as the token. These tokens would be called SSTs (Social Security Tokens) and would be linked to the voter's identification documents such as driver licenses, state IDs, or voting cards. This would ensure that only citizens who are registered to vote are able to access the voting process.

After citizens are registered, they would then receive a Voter Enabled Token (VET) that would allow them to vote. This token would be unique to each voter and would be linked to their SST. The VET would be used to confirm the voter's identity and eligibility to vote.

VETs could be deregistered for various reasons, such as death, giving up citizenship, or a felony conviction. These deregistered tokens would be called DEREG-VETs and would no longer be valid for voting.

SSTs could also be deregistered for death or giving up citizenship and would be placed into cold storage for historical tracking and census data. This would ensure that the voting process is up-to-date and that only eligible citizens are able to vote.

All states, counties, and districts would validate their Current Vote Eligible Persons (CVEP) by comparing the number of citizens to census data and the number of eligible voters (aged 18-120 and not having a felony or other disqualifying factors). This would ensure that only eligible citizens are able to vote and prevent any kind of voter fraud.

This system would ensure that the voting process is secure, transparent, and accurate. It would also ensure that only eligible citizens are able to vote and prevent voter fraud. 




---Anonymous Process---

To ensure anonymity and protect personal ID, the Voter Enabled Token (VET) could be combined with Scrambled Prime Key Encryption (SPKE) to create an Anonymous Activated Voter Enabled Token (AAVET).

The AAVET would be unique for each voter and would be created by scrambling the voter's prime key (a unique identifier) with a randomly generated encryption key. This would make it difficult for anyone to trace a vote back to an individual voter.

The AAVET could be used to cast a vote on the blockchain-based voting system, and the vote would be recorded as a transaction on the blockchain.

The use of AAVETs and SPKE would add an additional layer of security and anonymity to the voting process, but it would also require additional resources and complexity to the system.


## How the process would unfold

1. Citizens register to vote.
2. Citizens visit voting centers.
3. Vote center clerks validate voter registration.
4. Citizens place their ID on an RFID Voting Process Unit (RFID-VPU) for processing.
5. The RFID-VPU detects the Voter Enabled Token (VET) and activates the Blank Reusable Voting Card (BRVC).
6. The RFID-VPU places the Anonymous Activated Voter Enabled Token (AAVET) on the BRVC.
7. The Voting Blockchain updates with a successful voting slot and waits for AAVET confirmation.
8. The voter is handed the BRVC.
9. The voter walks into a booth and places the BRVC on the voting machine.
10. The voting machine establishes an encrypted connection to the Voting Blockchain.
11. The voter selects their desired vote(s).
12. The voting machine registers the vote(s) and asks for confirmation.
13. The voter reviews the vote(s) and confirms.
14. The voting machine updates the Voting Blockchain ledger and removes the AAVET from the BRVC.
```
When the voting blockchain updates with a successful voting slot, this means that the blockchain is recording that a vote has been cast and is waiting for confirmation that the Anonymous Activated Voter Enabled Token (AAVET) is valid.

To ensure security, the voting blockchain can employ various techniques such as time-to-live (TTL) limits, multi-signature validation, and smart contract-based validation to confirm the AAVET is valid.

- Time-to-live (TTL) limits: This is a mechanism that prevents the AAVET from being used again after a certain period of time. For example, once the voter casts their vote, the AAVET is only valid for a certain number of minutes or hours, after which it becomes invalid.
- Multi-signature validation: This is a mechanism that requires multiple parties to sign off on a transaction before it is recorded on the blockchain. This can be used to confirm that the voter's identity has been verified and that the vote is valid.
- Smart contract-based validation: Smart contracts are self-executing contracts with the terms of the agreement written into code. The use of smart contracts in the voting process could be used to confirm the voter is eligible to vote, the voter's identity, and that the vote is valid.
```
15. The AAVET is locked into the Voting Blockchain slot and cannot be changed. The Blockchain slot is closed.
16. The Voting Blockchain ledger is updated.
17. The voter is provided confirmation and can see their vote listed within the Voting Blockchain.
18. The voting machine has the option to print a paper ballot for the voter to turn in to the voting clerk for confirmation, audits, etc.
19. The AAVET is now useless for additional voting since it is no longer valid.
20. The voter removes the BRVC and leaves the booth.
21. The voter returns the BRVC for reissue to the next voter.
22. The vote clerk places the BRVC on the RFID Wipe Clean Verify System (RFID-WCVS)
23. The BRVC is issued to the next voter and the process repeats.
24. Voting statistics are displayed publicly for all to see.


## What about security and transparency?!?!

Additional things that could be considered when it comes to education, policy, technology, security and transparency in a blockchain-based voting system:

- Voter education: Providing voter education resources and training for election officials can ensure that voters understand how to use the voting system, including how to register to vote, how to verify their identity, and how to cast their ballots.

- Voter registration: This could be done online or in person, and it should be a secure and efficient process, that allows the voter to register only once and be able to vote in any location.

- Voter turnout: Designed to increase voter turnout by making it easier for people to vote, such as providing more convenient voting locations and allowing for early voting or vote-by-mail options.

- Voter confidence: Designed to increase voter confidence in the voting process by providing a clear and transparent view of the voting process, and by making it more difficult for any one person or group to tamper with the voting results.

- Technical support: A reliable technical support system should be in place to help voters and election officials with any technical issues that may arise.

- Cost: Considering the cost of implementing and maintaining the blockchain-based voting system and weigh it against the benefits it would bring in order to make a decision about whether or not to implement it.

- Interoperability: Designed to be interoperable with other systems, such as voter registration systems, to ensure a smooth and efficient process.

- Compliance with regulations: Researching and complying with all relevant laws and regulations at the federal, state, and local level is necessary.

- Auditing: A way for independent auditors to verify the accuracy of the voting results. This could be done by allowing auditors to access the voting data on the blockchain, or by providing a way for them to conduct a parallel vote count.

- Voter-verified paper audit trail (VVPAT): Providing a paper trail of the vote casted, by printing a physical copy of the vote that the voter can review before submitting, provides a way for voters to confirm that their vote was cast as intended, and for auditors to verify the accuracy of the voting results.

- Accessibility: Making the voting process accessible to all eligible voters, including those with disabilities, can be achieved by providing accessible voting machines or allowing remote voting options.

- Decentralization: Utilizing blockchain technology's decentralization feature, which means that the data is stored across multiple nodes, can make it more difficult for any one person or group to tamper with the voting results.

- Smart Contracts: Smart contracts can be used to automate some of the voting process and ensure that it is transparent and secure. For example, smart contracts can be used to validate voter eligibility, ensure that each voter can only vote once, and automatically count and report the vote results.

- Anonymity: Techniques such as zero-knowledge proofs or homomorphic encryption can be used to verify the voter's identity without revealing their personal information.

- Security: Designed with robust security measures in place to protect against hacking and other forms of cyber attacks, such as multi-signature validation, using secure communication protocols, and regular security audits and penetration testing.

- Transparency: Provide a clear view of the voting process for the public, this could be done by allowing public access to the voting data on the blockchain, providing real-time vote counting, and publishing the final results on a public website.

## I would rank the priorities this way:

1. Voter confidence
2. Security
3. Transparency
4. Compliance with regulations
5. Voter turnout
6. Voter education
7. Voter registration
8. Auditing
9. Voter-verified paper audit trail (VVPAT)
10. Accessibility
11. Decentralization
12. Smart Contracts
13. Anonymity
14. Interoperability
15. Technical support
16. Cost effectiveness


## High-level and very basic representation of the blockchain network:

- The network would consist of multiple nodes that would work together to maintain the blockchain ledger.
- Each node would have a copy of the blockchain ledger, which would be updated in real-time as votes are cast.
- A consensus algorithm such as Proof of Stake (PoS) to ensure that the nodes reach consensus on the state of the blockchain ledger.
- Have an API that would allow for the integration of different voting machines, RFID-VPUs, and other voting-related systems.
- Smart contracts that would be used to validate voter eligibility, ensure that each voter can only vote once, and automatically count and report the vote results.
- Scrambled Prime Key Encryption (SPKE) to encrypt the voter's prime key to create the AAVET.
- Built-in time-to-live (TTL) mechanism that would prevent the AAVET from being used again after a certain period of time.
- Voter-verified paper audit trail (VVPAT) that would provide a physical copy of the vote that the voter can review before submitting.
- Public access to the voting data on the blockchain, providing real-time vote counting, and publishing the final results on a public website.


## Laws that need to be drafted and voted on:

1. Voter identification laws: To ensure that only eligible citizens are able to vote, a system for voter identification would need to be established through laws that require citizens to have a government-issued ID, such as a driver's license or passport, in order to vote.

2. Election integrity laws: To ensure the integrity of the voting process, laws would need to be passed that establish penalties for voter fraud, a process for auditing the voting results, and a process for resolving disputes over the voting results.

3. Cybersecurity laws: To ensure the security of the voting process, laws would need to be passed that establish standards for the security of voting systems, penalties for hacking or other forms of cyber attacks on voting systems, and a process for responding to cyber security incidents.

4. Privacy laws: To protect the privacy of voters, laws would need to be passed that establish standards for the protection of personal information, penalties for the unauthorized disclosure of personal information, and a process for resolving disputes related to the privacy of voters.

5. Blockchain laws: To govern the use of blockchain technology in the voting process, laws would need to be passed that establish standards for the security and integrity of blockchain-based systems, a process for resolving disputes related to the use of blockchain technology, and a process for regulating the use of blockchain technology.


## How do we start and test out this idea... Mr. ZeroBandwidth?

Testing the blockchain-based voting system on a smaller scale, such as voting for city council members or town mayors, would display its real benefits in several ways:

- Feasibility: A smaller scale test can help identify and find solutions for technical issues such as scalability.

- Security: Security vulnerabilities such as hacking attempts can be identified and solutions found on smaller scale deployment tests.

- Transparency: Transparency issues, such as providing a clear view of the voting process for the public, can be identified and solutions found through testing the system on a smaller scale.

- Voter acceptance: User acceptance issues, such as accessibility, can be identified and solutions found if used in smaller voting election events. 

- Legal compliance: Identifying any compliance issues that may arise and finding solutions for them can be achieved.

- Cost effectiveness: Quick identification of any cost-related issues that may arise and to find solutions for them.

Testing the blockchain-based voting system on a smaller scale would also provide an opportunity to gather feedback from voters, election officials, and other stakeholders. This feedback would be valuable in identifying any issues or concerns that may arise during the implementation of the system, and to make any necessary adjustments to the system before it is rolled out on a larger scale.

Additionally, testing the overall system and practices on a smaller scale would also provide an opportunity to demonstrate the transparency and security benefits of the system to the public. By providing a clear view of the voting process, and making it more difficult for any one person or group to tamper with the voting results, it would increase public trust in the voting process, and therefore increase voter participation.

Testing the system on a smaller scale would also provide an opportunity to demonstrate the benefits of smart contracts, which could automate some of the voting process and ensure that it is transparent and secure.


## Acronyms I made up:

AAVET: Anonymous Activated Voter Enabled Token, it's a unique token that enables a voter to vote anonymously.
BRVC: Blank Reusable Voting Card, it's a card that is activated by RFID-VPU, and carries the AAVET on it.
CC: Citizen Count, it's the number of citizens in a certain area.
CD: Census Data, it's the data collected by the census bureau.
CVEP: Current Vote Eligible Persons, it's the number of citizens who are eligible to vote.
DEREG-VET: De-registered Voter Enabled Token, it's a token that has been de-registered and is no longer valid.
RFID-VPU: RFID Voting Process Unit, it's a device that is used to activate the BRVC and place the AAVET on it.
RFID-WCVS: RFID Wipe Clean Verify System, it's a system that is used to wipe and clean the BRVC before it's issued to the next voter.
SST: Social Security Token, it's a token that is issued to U.S. citizens using their social security number (SSN) as the token.
SPKE: Scrambled Prime Key Encryption, it's a way to encrypt the voter's prime key (a unique identifier) with a randomly generated encryption key to create AAVET.
VEP: Vote Eligible Persons, it's the number of citizens who are eligible to vote.
VET: Voter Enabled Token, it's a token that is issued to registered voters and allows them to vote.


## Final thoughts....

This idea for a blockchain-based voting system is a design taking place in a perfect world. Where the technology is fully developed, tested, and implemented to its full potential. This system would provide a secure, transparent, and accurate way to vote that would increase voter turnout and public trust in the voting process. It would also provide a way to automate some of the voting process and ensure that it is transparent and secure, using smart contracts.

It's important to remember that this idea is just that, an idea, and while it has the potential to solve some of the problems with the current voting system, it would require extensive research, development, testing, and compliance with relevant laws and regulations before it could be implemented.

As the person who came up with this idea, it's important to remember that not every idea will be fully implemented, but it's a good to come up with ideas and try to find solutions for problems instead of just complaining about them. 

Even small contributions can make a big difference and that it's essential to keep pushing for progress.

;)
