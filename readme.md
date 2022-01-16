## Bitcoin and Cryptocurrencies
### (CS198.1x - BerkeleyX)
 
#### Course Syllabus
This course is a comprehensive and in-depth overview of the fundamental concepts of the crypto space, with a particular emphasis on Bitcoin. By building intuition first from the context of cryptocurrencies, the first application of blockchain, we understand the key strengths and distinguishing factors of blockchain versus traditional database systems. 
We then leverage these core features of blockchain to solve new problems.
The course is divided into 6 modules: 
  01. Bitcoin High-Level Overview, 
  02. Blockchain History, 
  03. Bitcoin Mechanics Technical Overview, 
  04. Bitcoin in Real Life, 
  05. Game Theory & Network Attacks, and 
  06. Ethereum & Smart Contracts.

### Modules
  1. Bitcoin Protocol & Consensus: A High-Level Overview
> We begin with some fundamental concepts such as the basic properties and intent of centralized/decentralized currency. 
> We then build an in-depth understanding of Bitcoin from the ground up, divided into four stages: a. Identity, b. Transactions, c. Record Keeping, and d. Consensus. 
  
  2.	Blockchain History: From the Cypherpunk Movement to JP Morgan Chase
> This module delves into the origins and historical significance of Bitcoin. 
We look into the roots of Bitcoin in the Cypherpunk movement and Libertarian ideals, and examine the revolutionary significance of Bitcoin compared to some of its early predecessors. 
> We then move onto exploring the history of the crypto space as a whole.
  
  3.	Bitcoin Mechanics & Optimizations: A Technical Overview 
> We examine the in-depth mechanics behind Bitcoin, such as the Bitcoin network, cryptography and cryptographic hash functions, Bitcoin Script, privacy, and hash commitment schemes.

  4.	Bitcoin In Real Life: Wallets, Mining, and More 
> We examine the most frequently used real-world aspects of Bitcoin, such as wallets, wallet mechanics, mining, transactions, and Bitcoin governance. 
> We explain the various ways one can interface with the Bitcoin network, depending on the specific software they run.

  5.	Game Theory & Network Attacks: How to Destroy Bitcoin 
> We look into how to destroy Bitcoin, including various network attacks. 
Specifically, we look into vulnerabilities such as pool cannibalization, double spending and forking attacks, network attacks, the Goldfinger attack, malicious mining profit strategies, and 51% attacks.

  6.	Ethereum & Smart Contracts: Enabling a Decentralized Future 
> This module focuses on the properties behind the second largest blockchain platform, Ethereum. We introduce the Ethereum Virtual Machine and the idea of Turing completeness and examine some of the key protocol differences between Bitcoin and Ethereum, such as the UTXO vs. accounts model and functionality.
> We then look into some of the use cases of Ethereum, and conclude with an overview of smart contracts and building decentralized applications.
> While the last modules primarily focus on cryptocurrencies, this module encourages students to think about blockchain use cases outside of cryptocurrency.

#### Resources
  •	Bitcoin and Cryptocurrency Technologies by Arvind Narayanan, Joseph Bonneau, Edward Felten, Andrew Miller, and Steven Goldfeder
  •	Mastering Bitcoin by Andreas Antonopoulos
Also, a good unofficial resource is the Blockchain at Berkeley Public Slack, where we discuss various topics related to blockchain. You can request access to our Slack workspace at the bottom of the Blockchain at Berkeley website under "Join Blockchain at Berkeley on Slack."

#### Course Staff
Rustie Lin, Mengyi (Gloria) Wang, Nadir Akhtar, Jennifer Hu, Janice Ng.

#### Major Contributors
Blockchain Fundamentals started off as the Cryptocurrency DeCal (Democratic Education at Cal, student run) course on UC Berkeley campus in Fall 2016, taking inspiration from existing courses, videos, and textbooks. From the beginning, the vision was to lower the barrier of entry and provide a survey into the blockchain and cryptocurrency space -- to explain concepts from the ground up, as clearly and concisely as possible.
Each semester since then, we have had many student volunteers take time out of their already hectic schedules to help develop and fine-tune content, to make Blockchain Fundamentals what it is today. 
Blockchain Fundamentals is constantly being improved, in terms of new information as well as course design, but its vision has remained constant. Here are some of the major contributors to Blockchain Fundamentals, who have not already been featured on the previous page.
Max Fang, Philip Hayes, Sunny Aggarwal, Aparna Krishnan, Gloria Zhao, Gillian Chu, Brian Ho.

Module/Week 1:
Course/Bitcoin Protocol & Consensus: A High Level Overview/Intro
Welcome to the first module in Cryptocurrencies: Bitcoin and the Crypto Space, the first course in the Blockchain Fundamentals program.
Whether you’re an enthusiast, trader, aspiring blockchain developer, or just a curious individual looking to learn where and how blockchain can be used, you’ve come to the right place.
Blockchain technology is poised to affect so much of the world today, -- in the financial, energy, identity, and IoT industries just to name a few.
But blockchain use cases weren’t always this pervasive.
Throughout its infancy, blockchain found its primary use in cryptocurrencies -- and Bitcoin was its original inspiration.
To understand the wider crypto and blockchain space, we must first seek to understand Bitcoin, the oldest and most widely understood blockchain application.
Throughout this module, you’ll first learn what Bitcoin is and what its primary motivations are.
Then, we’ll dive into four-part buildup of Bitcoin consensus and explain why Bitcoin is built the way it is.
Bitcoin Protocol & Consensus: A High-Level Overview
Intro: What is Bitcoin?
In this section, you will learn about the origins and motivations of Bitcoin, and the key distinctions between cryptocurrencies and normal currencies.
We’ll clear up some common misconception about Bitcoin and Blockchain, and also explain briefly Bitcoin’s origins in the Cypherpunk movement.
We’ll then draw a comparison between Bitcoin and Banks and analyze each of the features and services they provide.
And this all sets the stage for the next section, in which we’ll build Bitcoin from the ground up, incorporating each of these features and services and seeing how they fit together.
What is Bitcoin?
Most people struggle to answer the question, “What is Bitcoin?,” because there are so many different ways to respond.
First, Bitcoin is considered the first and the most widely used cryptocurrency.
A cryptocurrency is a completely digital, decentralized currency that is built using principles of computer science, cryptography, and economics.
The term “Bitcoin” refers to the protocol governing this currency.
Second, bitcoin lowercase refers to the actual units of currency.
A Bitcoin user will say they have a certain amount of bitcoins, similar to how we say we have a certain amount of dollars when referring to the US Dollar.
Third, Bitcoin is the inspiration for the blockchain, which is the underlying data structure of this cryptocurrency.
A data structure is a virtual format for organizing, retrieving, and storing information.
The Bitcoin blockchain in particular stores a permanent history of all transactions to ever occur in the history of Bitcoin.
It is an append-only ledger, meaning that any information added to the ledger cannot be deleted.
But most importantly, Bitcoin is a cultural revolution.
Rooted in ideals from Cypherpunks and libertarians, Bitcoin represents a shift towards privacy and decentralization.
This cryptocurrency is not backed by any central organization, government, or company.
Instead, Bitcoin is built by the users, for the users.
As we said, Bitcoin was inspired by the Cypherpunk Movement of the late 80s.
Cypherpunks advocate for the protection of privacy using cryptography.
They don’t trust governments, corporations, or large organizations to respect privacy.
These points of centralization accumulate a great deal of power over society by collecting unimaginable amounts of information from millions of users.
And the Cypherpunks were some of the first to be concerned about central entities stripping away the freedom of the general public.
One massive point of centralization in modern day society is the financial system, where:
banks govern the economies of entire countries.
Several different companies and researchers attempted to make a decentralized or anonymous currency, but all of them failed.
Bitcoin was the first technology to succeed as a cryptocurrency.
The Bitcoin whitepaper, or research paper, was published in October 2008 by Satoshi Nakamoto.
The whitepaper was a 9-page, concise proposal for the structure and function of a peer-to-peer electronic currency.
Satoshi Nakamoto is a pseudonym, or a false identity, of an individual or a group of individuals.
No one knows their real identity. However, what's important is that this whitepaper envisioned a currency where users do not rely on financial intermediaries or trust anyone in order to make transactions with each other.
In Bitcoin, users do not need to use their real world identities; instead, they are represented by addresses, strings of random letters and numbers.
Bitcoin takes control out of the hands of third parties and gives users the freedom to transact while protecting their privacy.
So how does Bitcoin do it? On a high level, the Bitcoin network validates transactions and stores the entire transaction history.
The Bitcoin network is a group of users communicating with each other as part of the Bitcoin protocol.
This network serves as the substitute for the central bank and must have certain properties to function correctly.
Bitcoin is trying to create an open, accessible cryptocurrency not subject to censorship or centralization.
But what are the problems?
Keep in mind the problems of trying to create an open, accessible cryptocurrency not subject to censorship or centralization:
There are no central parties to ask for information about user accounts, and there are no central parties to kick out or censor malicious users.
Decentralized networks generally suffer from these problems, leading to inconsistencies between parties and malicious messages infecting the network.
The most popular attack is known as the double spending attack, an attack where some value is used for more than it i’s worth.
In real life, it’s easy to prevent double spending: since dollar bills can’t be copied and pasted.
However, in digital currencies, there needs to be assurance that the virtual tokens have not been promised to more than one person.
Bitcoin as a technology is trying to solve a very specific problem in the realm of distributed systems: when any “node,” or computer within the network, can come and leave as it pleases and behave however it likes.
There are enormous possibilities for failures given the complete removal of centralization, which is why there were so so many Bitcoin’s predecessors to Bitcoin which failed.
So how does bitcoin solve these problems?
Bitcoin solves these problems through two things:
First, the blockchain, and the Proof-of-Work consensus protocol, both of which are Satoshi Nakamoto’s most popular and influential innovations.
Because of these two things, anyone with access to internet and a computer can join the Bitcoin Network.
There are no banks or any equivalent of the Federal Reserve on the Bitcoin Network.
Instead, everyone can verify and audit the transaction history on their own.
And even the creation of money is decided not by a central authority, but through the process of mining, or Proof-of-Work.

### Bitcoin vs. Banks
Bitcoin aims to get rid of the central entity, the bank.
In order to understand how it does that, we first need to understand what purpose a bank serves and what features it provides to users, then understand the parallels in Bitcoin.
The first thing that banks do for us is manage accounts.
Banks verify that we are the legitimate owner of the bank account and only we can spend the money or the funds. How does a bank do that? Banks will ask us to provide identification before any activity can take place.
Every transaction we conduct can be traced back to our identity.
On top of that, banks transfer and redeem money on your behalf.
We send money to each other through banks.
We rely on banks to honestly record our account balances.
This way, we don’t need to send money through envelopes to relatives -- we let these central institutions move money in safe and, established ways on our behalf.
To keep track of all this information, we rely on banks to keep track of our account balances.
Banks update our account balances whenever we make a new transaction.
They also let us see statements so that you’re aware of your past history of activity.
But most importantly, banks provide trust: banks are run by educated professionals from top-tier universities and under the constant regulation of the U.S. Government.
If you trust the quality of education and standards of the U.S. government, then you can trust the bank.
But if you don’t, then you start looking for alternatives.
And this is where Bitcoin comes in.
So, let's take a look at how Bitcoin can fulfill a bank's functions.
In Bitcoin, identity and account management are completely autonomous.
Each user of Bitcoin creates their own identity instead of asking a bank to create one.
Anyone can generate a Bitcoin identity on their own.
This identity is disconnected from their real world identity, providing a high degree of privacy.
On top of that, transactions are also peer-to-peer: instead of talking to a bank which will talk to another bank which will eventually talk to the recipient of some money, we can make transactions directly can be made between with our peers and be confident that they are confirmed by the rest of the network.
Therefore, in Bitcoin, users can send funds to each other directly knowing that their transactions will be validated by the entire network without the presence of a trusted third party.
To store all this information, each Bitcoin user gets to possess their individual copy of the ledger.
This decentralized approach of record keeping ensures the integrity of data despite the presence of faulty nodes who might record the information dishonestly.
The decentralized nature of bitcoin also prevents the risk of single point of failure.
In the event that a particular node is hacked in bitcoin, because everyone is a record keeper, the rest of the network can still ensure the integrity of the transaction record and keeps running. 
But finally, there is still a need for trust in Bitcoin: instead of trusting people in suits, we trust math and logic.
We trust that the Bitcoin protocol is correct, allowing us not to trust the users and still have certainty that transactions are being validated correctly.
We trust in the incentive alignment and publicly verifiable, tamper evident ledger instead of our fellow users.
All of these pieces together make Bitcoin the technological revolution that kicked off the Cryptocurrency Movement.

### Intro: Bitcoin from the Ground Up
We saw in the section on Bitcoin versus Banks that we need to enable account and identity management, money transfer as a service, record management, and trust.
In this section: titled Bitcoin from the Ground Up, we’ll take each of these four concepts and see how they fit into Bitcoin’s architecture.
By the end, you should have a high level understanding of how Bitcoin works, and why things are the way they are in Bitcoin.
Intro: Identity (Stage 1)
We’ll start off by taking a look at one of the most fundamental ideas in Bitcoin:
Identity.
We saw earlier that banks need to keep track of the accounts and identities of their customers.
But how do we do this in Bitcoin, without a bank or central entity to keep track of who’s who and who owns what?
 
### Identity (Stage 1)
To understand why we need identity in Bitcoin in the first place, let’s understand first why we need identity at all in the context of currencies.
In currencies, we need to ensure that all users can authenticate themselves through some identification method, and that all identification methods have integrity.
Authentication is required to ensure that no one else acts on your behalf.
Claiming, receiving, and spending money on your behalf are things that only you should be able to do.
Like a bank, by associating yourself with your funds through authentication, you are able to receive money from others and spend your own money.
Only you have access to your own money, since others are not authenticated to handle your money.
Without an authentication process, anyone could spend my money, which is obviously undesirable.
Additionally, authentication can also be used to enforce blaming.
If someone tries to do something incorrect within the network, such as spend someone else’s funds, you want to be able to call them out with proof.
For example, if someone tries to withdraw your funds from a bank, you would want a record of this, including the identity of who was trying to take your funds, to get rid of malicious activity in the future by banning or refusing to interact with those people.
Integrity, the other half of identity, means that all our authentication methods cannot be replicated by anyone else.
We can understand integrity by the process of signing a check: once you sign a check or transaction, no one should be able to intercept and/or manipulate it.
The check has been signed by you, and since no one can replicate your signature, it should be tamper evident.
Integrity ensures that no one but you, the signer, can use your signature.
Imagine the following scenario in Bitcoin: 
If I wanted to send Alice 10 bitcoins, she shouldn’t be able to add another zero and make me send her 100 bitcoins.
She also shouldn’t be able to copy or replicate my signature elsewhere.
Only by preventing all these things can we trust the integrity of Bitcoin identities.
Identity is a simple concept appearing everywhere in daily life.
For example, houses have both addresses and mailbox keys.
When you ask people to send you mail, you give away your address, so they know where to send the package to.
Meanwhile, you alone control the mailbox key.
Similarly, emails have aliases and passwords.
People who want to send you email have access to your email address or alias, while you alone have access to the password to your email account, so only you can read these emails.
Bitcoin, following this pattern, has both public keys and private keys.
The items in orange on the left hand side -- mailbox addresses, email aliases, and public keys -- represent one’s public identity.
They are what you give out to the public so that they know how to communicate with you, so that they know how to recognize and identify you.
Meanwhile, the items on the right hand side in red -- mailbox keys, email passwords, and private keys -- are secret keys that you alone should own.
With these personal keys, you access the orange items on the left.
It gives you control and ownership.
It gives you your identity.
If anyone else gets their hands on your email password, for example, they can pretend to be you, receiving and sending emails on your behalf.
