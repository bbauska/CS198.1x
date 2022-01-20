oin and Cryptocurrencies  
\## BerkeleyX - CS198.1x

\<p align="center" width="100%">  
 \<img width="50%" src="https://github.com/bbauska/CS198.1x-Bitcoin-and-Cryptocurrencies/blob/main/images/cs198.1x-berkeley-logo.png?raw=true"  
   alt="BerkeleyX Bitcoin logo"\</>  
\</p>

\<!------------------------------------------------------------------------------------------------>  
\<!----------------------------- readme.md of CS198.1x.bauska.site -------------------------------->  
\<!------------------------------------------------------------------------------------------------>

\## Course Syllabus

This course is a comprehensive and in-depth overview of the fundamental  
concepts of the crypto space, with a particular emphasis on Bitcoin. By  
building intuition first from the context of cryptocurrencies, the first  
application of blockchain, we understand the key strengths and  
distinguishing factors of blockchain versus traditional database  
systems. We then leverage these core features of blockchain to solve new  
problems.

The course is divided into 6 modules: Bitcoin High-Level Overview,  
Blockchain History, Bitcoin Mechanics Technical Overview, Bitcoin in  
Real Life, Game Theory & Network Attacks, and Ethereum & Smart  
Contracts. 

1\.  \*\*Bitcoin Protocol & Consensus: A High-Level Overview\*\*

We begin with some fundamental concepts such as the basic properties and  
intent of centralized/decentralized currency. We then build an in-depth  
understanding of Bitcoin from the ground up, divided into  
\*\*\[four\*\* \*\*stages\*\*: a. \*\*\_Identity\_\*\*, b. \*\*\_Transactions\_\*\*, c.  
\*\*\_Record Keeping,\_\*\* and d. \*\*\_Consensus\*\*\_.

2\.  \*\*Blockchain History: From the Cypherpunk Movement to JP Morgan  
   Chase\*\*

This module delves into the origins and historical significance of  
Bitcoin. We look into the roots of Bitcoin in the Cypherpunk movement  
and Libertarian ideals, and examine the revolutionary significance of  
Bitcoin compared to some of its early predecessors. We then move onto  
exploring the history of the crypto space as a whole.

3\.  \*\*Bitcoin Mechanics & Optimizations: A Technical Overview\*\*

We examine the in-depth mechanics behind Bitcoin, such as the Bitcoin  
network, cryptography and cryptographic hash functions, Bitcoin Script,  
privacy, and hash commitment schemes.

4\.  \*\*Bitcoin In Real Life: Wallets, Mining, and More\*\*

We examine the most frequently used real-world aspects of Bitcoin, such  
as wallets, wallet mechanics, mining, transactions, and Bitcoin  
governance. We explain the various ways one can interface with the  
Bitcoin network, depending on the specific software they run. 

5\.  \*\*Game Theory & Network Attacks: How to Destroy Bitcoin\*\*

We look into how to destroy Bitcoin, including various network attacks.  
Specifically, we look into vulnerabilities such as pool cannibalization,  
double spending and forking attacks, network attacks, the Goldfinger  
attack, malicious mining profit strategies, and 51% attacks.

6\.  \*\*Ethereum & Smart Contracts: Enabling a Decentralized Future\*\*

This module focuses on the properties behind the second largest  
blockchain platform, Ethereum. We introduce the Ethereum Virtual Machine  
and the idea of Turing completeness and examine some of the key protocol  
differences between Bitcoin and Ethereum, such as the UTXO vs. accounts  
model and functionality. We then look into some of the use cases of  
Ethereum, and conclude with an overview of smart contracts and building  
decentralized applications. While the last modules primarily focus on  
cryptocurrencies, this module encourages students to think about  
blockchain use cases outside of cryptocurrency.

\### Resources

\-   \[Bitcoin and Cryptocurrency  
   Technologies \](https://d28rh4a8wq0iu5.cloudfront.net/bitcointech/readings/princeton_bitcoin_book.pdf)by  
   Arvind Narayanan, Joseph Bonneau, Edward Felten, Andrew Miller, and  
   Steven Goldfeder

\-   \[Mastering  
   Bitcoin \](https://github.com/bitcoinbook/bitcoinbook/blob/develop/book.asciidoc)by  
   Andreas Antonopoulos

\<p align="center" width="100%">  
 \<img width="50%" src="https://github.com/bbauska/CS198.1x-Bitcoin-and-Cryptocurrencies/blob/main/images/expectations.png?raw=true"  
   alt="Expectations"\</>  
\</p>

Also, a good unofficial resource is the Blockchain at Berkeley Public  
Slack, where we discuss various topics related to blockchain. You can  
request access to our Slack workspace at the bottom of the \[Blockchain  
at Berkeley website \](https://blockchain.berkeley.edu/)under \\"Join  
Blockchain at Berkeley on Slack.\\"

\### \*\*Course Staff\*\*

Rustie Lin, Mengyi (Gloria) Wang, Nadir Akhtar, Jennifer Hu, Janice Ng.

\### Major Contributors

Blockchain Fundamentals started off as the \[Cryptocurrency  
DeCal \](https://blockchain.berkeley.edu/decal/fa16/)(Democratic  
Education at Cal, student run) course on UC Berkeley campus in Fall  
2016, taking inspiration from existing courses, videos, and textbooks.  
From the beginning, the vision was to lower the barrier of entry and  
provide a survey into the blockchain and cryptocurrency space \\-- to  
explain concepts from the ground up, as clearly and concisely as  
possible.

Each semester since then, we have had many student volunteers take time  
out of their already hectic schedules to help develop and fine-tune  
content, to make Blockchain Fundamentals what it is today. 

Blockchain Fundamentals is constantly being improved, in terms of new  
information as well as course design, but its vision has remained  
constant. Here are some of the major contributors to Blockchain  
Fundamentals, who have not already been featured on the previous page.

Max Fang, Philip Hayes, Sunny Aggarwal, Aparna Krishnan, Gloria Zhao,  
Gillian Chu, Brian Ho.

\### Module 1: Course/Bitcoin Protocol & Consensus: A High Level Overview/Intro

Welcome to the first module in Cryptocurrencies: Bitcoin and the Crypto  
Space, the first course in the Blockchain Fundamentals program.

Whether you're an \*enthusiast, trader, aspiring blockchain developer\*,  
or just a \*curious individual\* looking to learn where and how blockchain  
can be used, you've come to the right place.

Blockchain technology is poised to affect so much of the world today,  
\\-- in the financial, energy, identity, and IoT industries just to name  
a few.

But blockchain use cases weren't always this pervasive.

Throughout its infancy, blockchain found its primary use in  
cryptocurrencies \\-- and Bitcoin was its original inspiration.

To understand the wider crypto and blockchain space, we must first seek  
to understand Bitcoin, the oldest and most widely understood blockchain  
application.

Throughout this module, you'll first learn what Bitcoin is and what its  
primary motivations are.

Then, we'll dive into four-part buildup of Bitcoin consensus and explain  
why Bitcoin is built the way it is.

\#### Bitcoin Protocol & Consensus: A High-Level Overview

\### Intro: What is Bitcoin?

\#### \[Click Here for What? \](\<https://youtu.be/Gc2en3nHxA4\>), 1 min; 37 sec

In this section, you will learn about the origins and motivations of  
Bitcoin, and the key distinctions between cryptocurrencies and normal  
currencies.

We'll clear up some common misconception about Bitcoin and Blockchain,  
and also explain briefly Bitcoin's origins in the Cypherpunk movement.

We'll then draw a comparison between Bitcoin and Banks and analyze each  
of the features and services they provide.

And this all sets the stage for the next section, in which we'll build  
Bitcoin from the ground up, incorporating each of these features and  
services and seeing how they fit together.

\### What is Bitcoin?

\<p align="center" width="100%">  
 \<img width="50%" src="https://github.com/bbauska/CS198.1x-Bitcoin-and-Cryptocurrencies/blob/main/images/what%20is%20bitcoin-bitcoin%20genesis.png?raw=true"  
   alt="What is Bitcoin?"\</>  
\</p>

Most people struggle to answer the question, "What is Bitcoin?," because  
there are so many different ways to respond.

\*\*First\*\*, Bitcoin is considered the first and the most widely used  
cryptocurrency.

A cryptocurrency is a completely digital, decentralized currency that is  
built using principles of computer science, cryptography, and economics.

The term "Bitcoin" refers to the protocol governing this currency.

\*\*Second\*\*, bitcoin lowercase refers to the actual units of currency.

A Bitcoin user will say they have a certain amount of bitcoins, similar  
to how we say we have a certain amount of dollars when referring to the  
US Dollar.

\*\*Third\*\*, Bitcoin is the inspiration for the blockchain, which is the  
underlying data structure of this cryptocurrency.

A data structure is a virtual format for organizing, retrieving, and  
storing information.

The Bitcoin blockchain in particular stores a permanent history of all  
transactions to ever occur in the history of Bitcoin.

It is an append-only ledger, meaning that any information added to the  
ledger cannot be deleted.

But most importantly, Bitcoin is a cultural revolution.

Rooted in ideals from Cypherpunks and libertarians, Bitcoin represents a  
shift towards privacy and decentralization.

This cryptocurrency is not backed by any central organization,  
government, or company.

Instead, Bitcoin is built by the users, for the users.

As we said, Bitcoin was inspired by the Cypherpunk Movement of the late  
80s.

Cypherpunks advocate for the protection of privacy using cryptography.

They don't trust governments, corporations, or large organizations to  
respect privacy.

These points of centralization accumulate a great deal of power over  
society by collecting unimaginable amounts of information from millions  
of users.

And the Cypherpunks were some of the first to be concerned about central  
entities stripping away the freedom of the general public.

One massive point of centralization in modern day society is the  
financial system, where:

banks govern the economies of entire countries.

Several different companies and researchers attempted to make a  
decentralized or anonymous currency, but all of them failed.

Bitcoin was the first technology to succeed as a cryptocurrency.

The Bitcoin whitepaper, or research paper, was published in October 2008  
by Satoshi Nakamoto.

The whitepaper was a 9-page, concise proposal for the structure and  
function of a peer-to-peer electronic currency.

Satoshi Nakamoto is a pseudonym, or a false identity, of an individual  
or a group of individuals.

No one knows their real identity. However, what\\'s important is that  
this whitepaper envisioned a currency where users do not rely on  
financial intermediaries or trust anyone in order to make transactions  
with each other.

In Bitcoin, users do not need to use their real world identities;  
instead, they are represented by addresses, strings of random letters  
and numbers.

Bitcoin takes control out of the hands of third parties and gives users  
the freedom to transact while protecting their privacy.

So how does Bitcoin do it? On a high level, the Bitcoin network  
validates transactions and stores the entire transaction history.

The Bitcoin network is a group of users communicating with each other as  
part of the Bitcoin protocol.

This network serves as the substitute for the central bank and must have  
certain properties to function correctly.

Bitcoin is trying to create an open, accessible cryptocurrency not  
subject to censorship or centralization.

But what are the problems?

Keep in mind the problems of trying to create an open, accessible  
cryptocurrency not subject to censorship or centralization:

There are no central parties to ask for information about user accounts,  
and there are no central parties to kick out or censor malicious users.

Decentralized networks generally suffer from these problems, leading to  
inconsistencies between parties and malicious messages infecting the  
network.

The most popular attack is known as the double spending attack, an  
attack where some value is used for more than it i's worth.

In real life, it's easy to prevent double spending: since dollar bills  
can't be copied and pasted.

However, in digital currencies, there needs to be assurance that the  
virtual tokens have not been promised to more than one person.

Bitcoin as a technology is trying to solve a very specific problem in  
the realm of distributed systems: when any "node," or computer within  
the network, can come and leave as it pleases and behave however it  
likes.

There are enormous possibilities for failures given the complete removal  
of centralization, which is why there were so so many Bitcoin's  
predecessors to Bitcoin which failed.

So how does bitcoin solve these problems?

Bitcoin solves these problems through two things:

First, the blockchain, and the Proof-of-Work consensus protocol, both of  
which are Satoshi Nakamoto's most popular and influential innovations.

Because of these two things, anyone with access to internet and a  
computer can join the Bitcoin Network.

There are no banks or any equivalent of the Federal Reserve on the  
Bitcoin Network.

Instead, everyone can verify and audit the transaction history on their  
own.

And even the creation of money is decided not by a central authority,  
but through the process of mining, or Proof-of-Work.

\<p align="center" width="100%">  
 \<img width="50%" src="https://github.com/bbauska/CS198.1x-Bitcoin-and-Cryptocurrencies/blob/main/images/image002-bitcoin-vs-banks.png?raw=true"  
   alt="Bitcoin vs Banks"\</>  
\</p>

\### Bitcoin vs. Banks
