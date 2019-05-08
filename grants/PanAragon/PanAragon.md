# PanAragon Nest Proposal

## Abstract

Our team is committed to the improvement of Aragon Core by focusing on two major goals: gradual scalability towards a futuredelivery of the Arachain via R&D efforts based on Polkadot and Substrate, and network monetization strategies and  theimplementation of such. 

Our proposal, in a nutshell:
* Aragon Core technology development in collaboration with existing contributors/ flock teams where required; building tech tools for the Aragon ecosystem with a focus on scalability.
* Aragon Product Lab: Product-Market-Fit and Monetisation research 



## Nest Deliverables (3 months)

**Deliverable**: PoC of a Substrate-based Layer-2 scalability solution for AragonOS, on Ethereum.

**Motivation**: An organisation, incorporated or informal, has to make a multitude of decisions. AragonOS is a technically complex product and it consumes a large amount of gas, 150,000+ units of gas based on our analysis of Aragon smart contracts. In this regard, the cost of on-chain governance which is at the heart of Aragon becomes an obstacleto the growth of Aragon-based organisations. 

Therefore, to address the costs of on-chain governance as an impeding factor of growth of the overall network, we propose to create a layer-2 solution adapted for on-chain voting, similar to Plasma. To provide an additional layer of security, we propose to implement it on Substrate. Subsequently, we aim to deliver a working “parachain” with Aragon contracts on Ethereum, featuring the parachain’s native smart contract API accepting signed transactions for voting messages. 

The additional layer of security enabled by the parachain’s consensus prevents vote manipulation and attacks to the voting system.When the voting periods end (the voting rules will be described in the Substrate contracts), the results will be synchronized with the Ethereum network.

## The Future - Flock (6 months) 

After completing the aforementioned work, we intend to apply for a Flock grant to help the AragonOne team (or any of the existing Aragon contributing teams) ship the Arachain on Substrate, subsequently working on Layer-1 scaling. 

**Deliverable**: working testnet

Given that Aragon hasannounced its research towards the implementation of the protocol on Polkadot, we believe our team is qualified toactively contribute to building the Arachain adapted to the protocol, and fast-track the overall R&D efforts and roadmap. Our team has already created their own chain using Substrate and is acting as a validator for Polkadot testnets. The Polkadot Telemetry details are here: 

* https://telemetry.polkadot.io/#/Akropolis

* https://telemetry.polkadot.io/#/Krumme%20Lanke

* https://telemetry.polkadot.io/#/Alexander

## Product-Market-Fit R&D: Real World Use Cases


Our team has already been focusing on the research of real-world DAO equivalents identified by the team and mostly channeling investigation efforts into [chamas as precursors to DAOs](https://docs.google.com/presentation/d/16P9pAqSryjJpk37R-CtXDEw-0pNtYpuBei2cmfIR2E8/edit#slide=id.g35c0209681_0_0).

Our team sees the Aragon SDK as a toolkit to super-charge traditional co-op/mutual structures and enable them to connect and exchange value regardless of geography and dependence on any banking system, offering a degree of resilience/protection/stabilisation against any forthcoming financial crisis. 

Our research has already confirmed that community-based informal savings organisations, still existing and active across many emerging markets, have been occurring  for the last 6-7 centuries.The most prominent example are in Kenya, South Africa, and diaspora-based informal savings circles have been identified in the US and Europe. Collectively, they capture over US$100 billion in savings and over US$16 billion annually in diaspora remittances. 

Another prominent examples are mutual credit collectives like Sardex, in Sardinia, Italy,  created as a local response to the 2007 credit crisis and having organically grown to over US$45mn turnover through a bank-independent network  in only one region in the country. 

We want to focus on exploring the ways how this real-world DAOs can use Aragon platform and how this could help to monetise the Aragon platform and support the ANT. 

**Our scope is catalysed by Chamas but not restricted to them** - we are committed to building a generalized solution for real-world DAO equivalents regardless of their geographical location or development stage.



## Requirements

* Publish access to aragonpm.eth

* Access to Aragon servers and cloud infrastructure

* Access to Aragon DNS and ENS domains

* Unrestricted use of the Aragon trademark

## Grant Size

We would like to request the standard $150,000 grant allocation paid in DAI to cover the operating costs. 



## Development timeline

**Deliverable**: PoC of  a Substrate-based Layer-2 scalability solution for AragonOS (L2-Voting), on Ethereum.

Please note that this timeline is indicative and we hope to refine it in collaboration with the Aragon Nest decision-makers to ensure optimal fit and timely delivery.

**1st month: Architecture and tech design.**
Development of the tech specification for L2-Voting chain. L2-Voting solution will be based on [OCEAN model](https://medium.com/the-adex-blog/introducing-ocean-alternative-layer-2-scalability-7d24bb22ebe4) (Off-Chain Event AggregatioN) and will use state channels to bridge Aragon tokens to L2-Voting solution. 

Deliverables: 
* Architecture and design documents
* Test environment set up

**2nd month - Development of offchain-voting and decision making - Using state channels and native Substrate smart contracts**

Deliverables: 
* Off-chain voting prototype (results of voting are not transmitted to Ethereum network). 

**3rd month - Development of Oracle development for voting results transferring from L2-Voting solution to Ethereum Aragon DAO.** 

Deliverables: 
* Layer-2 solution PoC
  
[optional, subject to funding] 4th month- Adding the ability to work with any DAO.

At the 1st stage (1-3 months) we take a test list of DAOs, that can work with our solution. 
In the next stage (this one mentioned above, month 4 - we "open" our solution to all DAOs. 



## Team 


### Ana Andria

Ana is an experienced special situations investment professional with a strong interest in decentralization and blockchain. She currently sits on the advisory board for the Web3 Foundation, and she has analyzed and transacted over USD3.5bn and advised on over USD300mn of private equity and debt transactions. Ana is a business-builder, team-builder, technology and data obsessive, with particular strength in forensic analysis, seeing efficiencies and optimising processes. She’s passionate about individual empowerment and helping others fulfill their potential. FCA-regulated fund management professional and a board member of a regulated private equity fund.

**Commitment**: Part Time

**Socials**: [**LinkedIn**](https://www.linkedin.com/in/anastasia-andrianova-79198b4)  | [**Twitter**](https://twitter.com/ana_andrianova/)



### Alex Maz

Blockchain engineer, educator and a co-founder of St.Petersburg Ethereum meetup, Alex graduated with BSc Applied Mathematics and Computing Sciences and is a PhD (cand.) Machine Learning.
He has 16 scientific publications focussing on natural language recognition and 10 commercially implemented applications to his name.
Alex has both shipped product in fintech, banking, and gaming, and is passionate about educating the new generation of blockchain developers.


**Commitment**: Full Time

**Socials**: [**LinkedIn**](https://www.linkedin.com/in/alexander-mazaletskiy/)  | [**Github**](https://github.com/AlexanderMazaletskiy)


### Alex Koz

Software Engineer, Consultant, Game Developer & reverse-engineering enthusiast. OSS enthusiast, active contributor of DDG, Haxe. Had more than fifteen years of development of real-world applications since 2000. Worked for many companies such as SmartGames, Dulton Media, Games.Mail.ru, Leo Burnett, Rambler, Clickberry and other companies with various projects.


**Commitment**: Full Time

**Socials**: [**LinkedIn**](https://www.linkedin.com/in/akozlovskij/)  | [**Github**](https://github.com/fzzr-)


### Dima Serd

Graduated from the Tomsk Polytechnic University in Information Systems and Technologies. Participated in development of 10 commercial projects, including those in blockchain sphere. Actively following all last innovations in front-end and near themes.


**Commitment**: Full Time

**Socials**: [**Github**](https://github.com/in19farkt)


### Ilgiz Gimal

Fintech professional with 10+ years experience. Prior to joining Akropolis overseed all product development for incubator projects at fintech fund. Earlier worked at Digital Business Development Department at VTB Bank, one of the leading universal banks of Russia. Graduated Lomonosov MSU, PhD in computer Science & Mathematics. Launched several startups from 0, also under management VTB bank integrated and launched digital sales.

**Commitment**: Part Time

**Socials**: [**LinkedIn**](https://ru.linkedin.com/in/ilgiz-gimaltdinov-8bbba411) | [**Github**](https://github.com/apeir99n)


### María Paula Fernández

**Commitment**: Part Time

**Socials**: [**Twitter**](https://twitter.com/mptherealmvp)


