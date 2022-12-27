# Ultron Foundation changelog and updates

**In this file Ultron team lists rollout and development updates for each week for all Ultron Foundation main products.** 

## Ultron Foundation updates from 19.12-23.12.2022


**NFT Staking HUB**
* Buyback system internal improvements and changes - finished and deployed.   
* Multiple tasks and on queues handling optimization in processing; 
* Comission payments issues fixed and improvements deployed; 

**UltronSwap**
* Refactoring of ultron decentralized exchange finished; 

**Website**
* Refactoring carried out;
* Rewards calculator updated

**Infrastructure**
* Witnet oracle launched pricefeed and randomness on Ultron testnet;


## Ultron Foundation updates from 12.12-16.12.2022


**Bridge**
* Monitoring system improved, new features deployed; 
* Bridge issues solving, improving bridge ecosystem; 


**Infrastructure**


* Preparing Ultron Smart - contracts for audit; 
* Refactroring of queues and fixing previously appeared issues; 
* Node upgrades + starting new nodes implementation;  


**Website**
 * Minor UI improvements;



## Ultron Foundation updates from 05.12-09.12.2022


**Bridge**
* More precise validation has been added to the forms;
* Fixed a minor issue with incorrect balance display;
* Monitoring system improvements;
* Network and Node updated;


**Ultron Website**
* Added a blog, made minor changes to the page UI; 


**Ultron NFT Staking HUB**
* Finished issues with remaining small amount of NFTs; 
* Rechecking legacy NFTs;
* Conducted a comparison of buybacks, still in progress;
* Load balancer work successfully finished; 
* Finished implementing the k8s;
* Made a fix for sending a webhook when paying for an order;


**Infrastructure improvements** 

* Updating nodes and network due to the update on Fantom;



## Ultron Foundation updates from 28.11-02.12.2022


**UltronSwap** 
* Solving problems with Binance nodes;
* Commissions have been adjusted for small values;
* Avalanche network restored and available on the bridge; 
* Bridge monitoring system management improved; 


**Ultron Scanner**
* Finishing updating rates with Coingecko;


**Ultron NFT Staking HUB**
* Solving minor issues with NFT’s ;
* Testing the rewriting of queues on the new framework;
* Checking the tasks accumulated in the queue;
* Checking buybacks; 
* Nodes improvement and upgrades;



## Ultron Foundation updates from 21.11-25.11.2022



**Ultron NFT Staking HUB**
* NFT Metadata contract updated;


**Infrastructure improvements** 
* Saving price rates from Coingecko, fixing problems with nginx configurations;
* Scaling the graphnodes for better preformance;
* Backend documentation improvements, configuration services integration, deployment services and manifest setting; 
* Spec for global monitoring;
* Preparation of smart-contract audits; 



## Ultron Foundation updates from 14.11-18.11.2022



**Ultron NFT Staking HUB**
* Dealing with problems after deploying the subgraph;
* Fixing user ids, checking potential duplicate NFTs, fixing empty order ids in NFT;
* Fixing Legacy and user id connections, conducted tests with buybacks;


**Infrastructure improvements** 
* Solving errors after the deployment of the subgraph;
* Creating the roadmap for migrating applications to the k8s;
* Migrating to the k8s started; 
* Implementing monitoring system alerts; 
* Transfer of validators to one continent; 
* Working with queues, rewriting and improving queues:



## Ultron Foundation updates from 07.11-11.11.2022:


**UltronSwap** 
* Minor issue fixes (problem with displaying liquidity in ULX-wETH pairs);
* Checking and testing the pool uUSD - wETH;
* Testing the second part of staking;
* Implementation of parallel autotests;
* Correction of positions in the block "ULX token on other networks";
* Staking task on Ultron DEX;
 
 
**Bridge**
* Bridge task (completed) for saving Network; 
* Fixing a issue with unknown network appearing;
* Collected a list of token balances on handlers;
* Minor issues fixing and completion of transactions on the bridge;
* In the process of setting up a local bridge to manage errors with tx on FTM;


**Ultron Scanner**
* Carried out and completed part of the End2End tests of the front (implementation and execution);
* Implementation of the subgraph during the review process
* Contract address update for NFT metadata is still in progress;
* Updated Subgraph deployment;


**Ultron Website** 
* Adding new articles, and performing minor updates.


**Ultron NFT Staking HUB**
* Completing the creation of a separate scanner for collecting NFT data;
* The task of parallelizing rewards is still in progress;
* Implementation of new technical improvements for increasing processing speed; 
* Adding a balance check before burn balance;
* Support cases solving;
* Solving problems with small amounts display in NFTs metadata; 


**Infrastructure improvements** 
* Address manager implementation for several workers;
* Implementing automatic retry policy for files of any queue and working with tx Queues; 
* Finishing the subgraph upgrades;
* K8s cluster setup starting (for backends);
* Creating LB for subgraph, preparing the graphnode to move;
* Preparing the infrastructure - done 
* Adding addresses in our VPN to the whitelist;
* Bridging infrastructure improvements;
* Secrets management implementing and improving;
* Monitoring system reconfiguration;



## Ultron Foundation updates from 31.10-04.11.2022

**UltronSwap** 
* Adding new tests functionality;
* Solving minor pool withdrawal issues;
* Solving issues with liquidity displaying and re-depositing;


**Bridge**
* Improvements for admin functionality; 
* Analysis of support cases;
* Alerting system improvements; 
* Failed transactions pending;


**Ultron Scanner**
* Finishing tests of the main page, Blocks, epochs, and validators;
* Finishing writing the subgraph and connecting it to the total supply;
* Fixing an issue which appeared in asset details;


**Ultron Website** 
* Blog updating; 


**Ultron NFT Staking HUB**
* Finishing commission auto-payment;
* Starting of upgrading queues to use advanced handler;
* Starting the improvements tests with NFTs on mainnet fork + solving rewards payments issues; 
* Updated NFT contract uploaded to the mainnet;
* Preparing updated smart contracts for audit; 



## Ultron Foundation updates from 24.10-28.10.2022:


**UltronSwap** 
* Updated the displaying of the price for the month + making updates in mobile version; 
* Fixed an issue with scrolling on a mobile phone;
* Fixed trouble with connecting to iOS;
* Uploaded the discord icon and diagram display;
* Completed in-depth tests for DEX + added new test cases for DEX. 


**Bridge**
* The relayer was added for the possibility of testing on the bridge;
* A couple of new bridge issues solving; 


**Ultron Scanner**
* Starting new tests for staking;
* Fixed an issue with assets;
* Asset inflation issue display solved; 


**Ultron Website** 
* Minor UI updates; 
* New article added on the website;


**Ultron NFT Staking HUB**
* Queues handling improvements;
* Finishing changes and improvements on the subgraph;
* Making new additions for NFT's;
* Solving the issue of rewards distribution;


**Infrastructure improvements** 
* Alert monitoring system improved;
* Failed transactions monitoring system improved (bridge);



## Ultron Foundation updates from 17.10-21.10.2022


**UltronSwap** 
* Deployment and launching of the infrastructure for the implementation of the tests;
* Completed the implementation of tests of the main user path; 
* Portfolio edit uploaded: now redirects to a specific transaction in the scan; 


**Bridge**
* Polygon network fixing;
* Working on the network monitoring with alerts;


**Ultron Scanner**
* Staking tests implementation;
* Fixed searching on the main page;


**Ultron Website** 
* Discord icon added + new team member info; 
* Connection of the CMS started;


**Ultron NFT Staking HUB**
* Completed the NFT contract for the subgraph and adding tests; 
* NFT support cases solving;
* Auto-payment of commissions functionality improved; 


**Infrastructure improvements** 
* Ultron validators migrated to closer locations;



## Ultron Foundation updates from 03.10 - 07.10.2022


**UltronSwap** 
*  Mobile design updated; 
*  Added a price display for the month to the price charts;
*  Updated API for Coinmarketcap;


**Bridge**
* Recovery after errors and problems with BSC;
* Bridge contract updated; 


**Ultron Scanner**
* Changes on the front page;
* Fully deployed the updated staking/delegating page;
* Instructions for using staking prepared;
* Node for testing the validator with a lock deployed;


**Ultron NFT Staking HUB**
* Backported the stable release of the graph node to our graph node fork;
* Auto-return scanning parallelized so that several networks are checked at once to increase processing speed;
* Display the beginning and end of the auto-return scan deployed;



## Ultron Foundation updates from 26.09-30.09.2022:


**UltronSwap** 
* Mobile interface updated;
* Trading volume added on UltronSwap with time pop-ups;
* Fixed issue with changing the network, if the connection was for the first time;


**Bridge**
* Setup of Avalanche network finished;


**Ultron Scanner**
* Staking page deployed, all appeared issues were solved; 


**Ultron NFT Staking HUB**
* Deployment of the bonus program (Legacy NFT);
* Fixing NFTs with wrong data; 
* Order interface added; 


**Infrastructure improvements** 
* Started preparation for cluster management panel; 
* Preparing the validator node for testing;
* Solving the connection problem between nodes on the gossip protocol;
* Initial preparation of lending/borrowing platform; 



## Ultron Foundation updates from 19.09-23.09.2022:


**UltronSwap** 
* Deployment of DEX API for CMC/Coingeco; 
* Returned to the prod pop-up in the mobile browser about switching to Metamask;


**Bridge**
* Finding/carrying out failed transactions after the BSC node crash;
* Avalanche removed from the config;


**Ultron Scanner**
* Message added about the problem and bridge blocking;
* Fixing minor issues with animations; 


**Ultron Website** 
* Popup menu issue fixing; 
* Made the display of project documents in a separate section;


**Ultron NFT Staking HUB**
* TVL information added;
* Completed the task of technical debt processing;
* Subgraph for Staking HUB explored; 
* Auto-payment of commissions and refunds - finished;
* Order interface finished;



## Ultron Foundation updates from 12.09-16.09.2022


**UltronSwap** 
* Price chart corrected;
* Minor redesign and UI improvements; 
* Info about staked ULX added to portfolio;
* Issue with xULX displaying fixed;
* Adapter Updated, xULX pool added to DefiLama;


**Bridge**
* Script for searching the transactions completed;
* ETH network updated, ETH currency returned;
* Fixed the issue that appeared during adding tokens in other networks;


**Ultron Scanner**
* XULX added to assets;
* Added animation;
* Display of wULX balance; 


**Ultron Website** 
* xULX added to assets;
* Blog updated - old articles changed, new ones added; 
* Updated information on decimals in assets;
* “About us” block changed; 
* Files in tokenomics, white paper, and light paper updated;
* New information page deployed;


**Ultron NFT Staking HUB**
* Auto-payment of commissions - uploaded on prod; 
* Auto-returns - finished and uploaded; 
* Stabilization of payments - uploaded and deployed; 
* Security in address management improved; 



## Ultron Foundation updates from 05.09-09.09.2022


**UltronSwap** 
* Made changes to the wallet blocking, and uploaded improvements; 
* xULX pool added to the TVL calculation;
* Displaying of 2 lists of tokens added: ULX in other networks; and other tokens in Ultron network;


**Bridge**
* ETH blocked/returned due to the update; 
* There was an incident with the fall of the bridge, worked and fixed it back to normal functionality; 


**Ultron Scanner**
* Validator names were changed;
* Fixed incorrectly displayed price in explorer assets + price for BUSD 


## Ultron Foundation updates 29.08-02.09.2022

**UltronSwap** 
* Fixed issue with wULX, fixed issue with ETH displaying;
* UltronSwap was added to the DefiLama;
* issue fixed in "My tokens" section;


**Bridge**
* Fixed minor issue with the ULX icon displaying on the bridge;
* Bridge deploy of on the testnet;


**Ultron Scanner**
* Validator info completed;
* Price, the market cap is now displayed;
* Assets page and information added;


**Ultron Website**
* Improved navigation;
* "Articles" block added;
* Added new employees to the "About us" page;
