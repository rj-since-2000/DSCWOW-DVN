# DSCWOW-DVN
Decentralised Voting application using Ethereum Network
### Abstract
Building a secure electronic voting system that offers the fairness and privacy of current voting schemes, while providing the transparency and flexibility offered by electronic systems has been a challenge for a long time. In this work-in-progress project, we evaluate an application of blockchain as a service to implement distributed electronic voting systems. The paper proposes a novel electronic voting system based on blockchain that addresses some of the limitations in existing systems and evaluates some of the popular blockchain frameworks for the purpose of constructing a blockchain-based e-voting system. In particular, we evaluate the potential of distributed ledger technologies through the description of a case study; namely, the process of an election, and the implementation of a blockchain-based application, which improves the security and decreases the cost of hosting a nationwide election.
<img width="1440" src="https://assets.devfolio.co/hackathons/4851e74537ac440d864f5a760f6b8167/projects/ee13125ddb81465098ea0bd1506045e8/picun1tfhzbc.png">
### Dir Structure 

```bash
 
    +---.github
    |          stale.yml
    |
    +---build/contracts
    |                  Election.json
    |                  Migrations.json
    |
    +---contracts
    |            Election.sol
    |            Migrations.sol
    |
    +---migrations
    |             1_initial_migration.js
    |             2_deploy_contracts.js
    |
    +---src
    |      +---css
    |      |      bootstrap.min.css
    |      |      bootstrap.min.css.map
    |      |
    |      +---images
    |      |
    |      +---js
    |      |     app.jss
    |      |     bootstrap.min.jss
    |      |     truffle_contract.jss
    |      |     web3.min.jss
    |      |
    |      +---index.html
    |
    +---test
    |       .gitkeep
    |       election.js
    |
    +---.gitattributes
    |
    +---.gitignore
    |
    +---bs-config.json
    |
    +---LICENCE
    |
    +---package-lock.json
    |
    +---package.json
    |
    +---README.md
    |
    +---truffle-config.json
    

```
## Setup
### Dependencies
<ul>
  <li>NPM: https://nodejs.org</li>
  <li>Truffle: https://github.com/trufflesuite/truffle</li>
  <li>Ganache: http://truffleframework.com/ganache/</li>
  <li>Metamask: https://metamask.io/</li>
</ul>  

Follow the steps below to download, install, and run this project.

### Step 1. Clone the project
`git clone https://github.com/rj-since-2000/DSCWOW-DVN`

### Step 2. Install dependencies
```
$ cd DSCWOW-DVN
$ npm install
```
### Step 3. Start Ganache
Open the Ganache GUI client. This will start your local blockchain instance.


### Step 4. Compile & Deploy Election Smart Contract
`$ truffle migrate --reset`
You must migrate the election smart contract each time your restart ganache.

### Step 5. Configure Metamask
- Unlock Metamask
- Connect metamask to your local Etherum blockchain provided by Ganache.
- Import an account provided by ganache.

### Step 6. Run the Front End Application
`$ npm run dev`
Visit this URL in your browser: http://localhost:3000

If you get stuck, want to collaborate or found a bug, please raise an issue.
