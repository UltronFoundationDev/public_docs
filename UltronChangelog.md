# Ultron Foundation changelog and updates

**In this file Ultron team lists rollout and development updates for each week for all Ultron Foundation main products.** 

## Ultron Foundation updates from 08.01 - 12.01.2024

**NFT Staking HUB**
* Subgraph development for balance monitoring improvements - in progress;
* Reward bridging mechanism from BSC to Ultron - in progress, the architecture has been approved;
* Import PaymentNFT - Updated the graph and contract in the testnet;
* Processing migration - in progress;
* Business logic tests -  tests under update for newly added functionality;
* Deployment of AM for bridge service - completed;

**Blockscout**
* Blockscout Redesign + Local Deployment - in progress;

**UltronSwap**
* BUSD delisting - in progress;

**L1**
* Testnet update - in progress.
* Validators issue solving - in progress;


## Ultron Foundation updates from 01.01 - 06.01.2024

**NFT Staking HUB**

* Revenue feature - in progress;
* Revenue uusd withdrawal feature - in progress;
* Development of a subgraph for wallets monitoring - in progess;

**Blockscout**
* Redesign Blockscout + Local Deployment - in progress; 

**Bridge**
* Farming Rewards update - completed; 

**L1**
Testnet update - in progress;

## Ultron Foundation updates from 25.12 - 29.12.2023

**NFT Staking Hub**
* Deployment of revenue UI - in progress;
* Burned gaming NFT issue solving - in progress;
* Deployment of revenue subgraph to mainet - completed;
* Backend withdrawal uusdt - completed;
* Reward distribution service (Backend) - completed;
* Development of an endpoint to balance check from custodial wallets - completed;
* Add domain to testnet subgraph - completed;
* Deployment of revshare contract on mainnet - completed;

**Blockscout**
* Redesign Blockscout - in progress;
* Local Deploy - in progress;

**ULXscan**
* StakerInfo issue solving - completed;
* Dynamical adding addresses to workers, optimization of AM work - in progress;
* Deployment of AM for revshare in production - completed;

## Ultron Foundation updates from 18.12 - 22.12.2023

**NFT Staking Hub**
* Revenue share feature - testing user flow in progress;
* Revenue share - withdrawal uusdt feature - modification for withdrawing uusdt from custodial wallets in progress;
* Backend part for uusdt withdrawal - uploaded to the testnet;
* Subgraph development for getting uUSDT and wUlX balance from custodial wallets - in progress;
* Historical data issue clarification for burned nft - in progress;
* Backend import PaymentNFT - backend part completed;
* Transfer of Processing to new server base - completed;

**UltronSwap**
* Check wallet connect in DEX services - in progress;

**Bridge**
* Add events logic for status transactions - completed;

## Ultron Foundation updates from 11.12 - 15.12.2023

**NFT Staking HUB**
* Revenue share system development - in progress;
* Testing of revenue share functionality - in progress;
* Development of a reward distribution service (Backend) with a test version deployment - in progress;
* Revenue UI (frontend) testing - in progress;
* Integration of the revenue share contract into the DAO - in progress;
* Burned NFT historical data issue solving - in progress;
* Backend development for importing PaymentNFT - in progress;
* ITANFT technical specification - in progress;
* Deployment of revenue UI on the testnet along with CI implementation - completed;

**Bridges**
* Refactoring of bridge scanning and DB query interactions with the frontend - completed;

**Address Manager**
* Writing additional tests for address manager - in progress;

**Blockscout**
* Redesigning and local deployment of Blockscout - in progress.

**Ultron Bridge**
* Adding alerts for cancelled and expired items - completed;
* Writing test for deposit and bridge scanning - completed;

## Ultron Foundation updates from 04.12 - 08.12.2023

**NFT Staking hub**

* Revenue share functionality impelementation - in progress;
* Reward distribution service - in progress;
* Revenue UI (frontend) - in progress;
* adding bridge monitoring - Ultron team added monitoring for bridges from BSC to Ultron;
* Update of gaming contract - completed
* Check of the burned nfts - Ultron team updated the contract;
* Revenue share subgraph development - uploaded for testing;
* CI/CD and deployments refactoring - in progress;


**Address Manager**
* Functionality tests - in progress;

**Blockscout**
* Testnet deployed locally in a new design for testing modules;

**UltronSwap**
* UltronSwap regression tests - completed
* Farming Rewards update - completed;


## Ultron Foundation updates from 27.11 - 01.12.2023

**NFT Staking Hub**
* Revenue share smart contract testing - test preparation in progress.
* Reward distribution service (Backend) - calculating rewards service preparation in progress.
* Burned NFT issue fix - fixing small issue, detected during NFT burning process;
* Revenue share - final preparation check;
* Update of gaming contract - contract uploading in progress;
* Models refactoring - completed;

**Address Manager**
* Adding of queued status and logic completed - added the status “in queue”;

**Blockexplorer**
* ULXScan regress tests - in progress;
* Redis API issue - completed;

**UltronSwap**
* Swap regress tests - in progress;

## Ultron Foundation updates from 20.11 - 24.11.2023

**NFT Stakint Hub report**
* Revenue share - tests conduction and brand improvements - in progress;
* Update of gaming contract - under review for further improvements;
* Integration gaming nft claim into Staking HUB (Backend) - in progress;

**Address Manager**
* Integration of AM into Reward service - in progress, uploaded for testing;

**Ulxscan**
* Fixes for pre-production stage - completed (NFT metadata, nested txs, font refactoring, adoptives minor fixes);
* GoRutines stop fix - completed;
* Reddis API issue - in progress;
* Fixes after regression tests - complrted (adoptive menu, profile fix)


## Ultron Foundation updates from 13.11 - 17.11.2023


**NFT Stakint Hub report**
* Revenue share update - in progress;
* Gaming contract update - in progress;
* Update of NFT HUB subgraph - completed
* Transfer of a test server - completed;

**Address Manager**
* Integration of AM into Reward service - on test;

**Ultronscan**
* Pre-production deployment - completed. Deployed on the mainnet to do final tests;
* Minor issues fixes - in progress. Including return of the gas tracker, nested transactions, and minor UI improvements to the validators page;
* GoRutines stop fix - in progress;

**Ultronswap**
* Internal migration of web application to other framework - completed;


## Ultron Foundation updates from 06.11-10.11

**NFT Staking Hub**
* Revenue share - the team is engaged in testing. We have finished developing the graph. Updated the spec.
* Transfer test server - in progress;
* Balance monitoring - added addresses to monitoring, then the team will make changes to the dashboard;
* scanner optimization - in progress;
* Perform fallback on public (ankr) - completed;
* Transfer parser - completed;

**Address Manager**
* Test vault Integration - integration of the updated Vault version into the address manager - in progress;
* status endpoint adding - completed;

**Ulxscan**
* Redesign of ulxscan - completed, waiting for release;
* Scanner and api separation, health-check endpoint - completed;
* GoRutines stop fix - in progress;

**BlockScout**
* The deployment version with the new GUI - in progress;

**UltronSwap**
* Farming Rewards upd - done;
* Info Page - done, uploaded to prod;
* New Meta Descriptions - done;

**L1**
* Performance tests of network - in progress, 3 nodes deployed, submitted a proposal on how to reduce the initial time to log into the network.

## Ultron Foundation updates from 23.10-27.10

**NFT Staking HUB**
* Revenue Share contract update preparation - in progress;
* Unit tests preparation - in progress;
* Cron transfer claim to Kubernetes - in progress;
* Spec Updating - completed;
* Custodial version implementation - completed;

**Ultron Scanner**
* Ulxscan redesign - in progress;
* Validator’s delegation extension - completed;
* Claim exchange rate field in NFT metadata Implementation - completed;

## Ultron Foundation updates from 16.10-20.10

**NFT Staking HUB**
* Ticket vouchers preparation - completed;
* Revenue share functionality - in progress.
* Rates displayment improvements on staking contract (airdrop dollar cap/ claim dollar cap) - completed;
* Change commission rates - completed;
* Claims Data Export - completed;
* Change attribute for claim nft- completed;
* Start of claim reward on testnet - completed;
Address Manager
* Add waiter receipt tx worker - completed;
* Update of spec and preliminary preparation of specs for Vault - in progress;

**Blockexplorer**
* Redesign ulxscan - performing tests, fixing issues, getting ready to submit for final testing;

**L1**
* Performance tests of network - in progress, finished with the infrastructure, launching tests;
Ultron Foundation
* Minor SSL issues investigation - in progress; 

## Ultron Foundation updates from 09.10-13.10

 
**NFT Staking HUB**
* Ticket vouchers - completed:
* Smart contracts and subgraph on deployment and testing;
* Celery branch update;

**Address Manager**
* Admin panel preparation - completed; 
* User model creation - completed; 
* Sqladmin integration - completed; 

**Blockexplorer**
* Redesign of ulxscan - all pages + gas tracker have been improved;

**L1**
* Performance tests of network - in progress, environment reconfiguration completed;

**Ultron Foundation website**
* Website Indexing - completed.


## Ultron Foundation updates from 02.10-06.10

**Staking Hub NFT Report**

* Ultron team commenced the import process and added new functionality to the contract.
* Ticket Vouchers: Currently, team preparing contracts and tests for ticket vouchers.
* Start Claim Reward on Testnet: The team is in the process of initiating the rewards claim on the testnet.
* Auto-refund in optimism network - in progress;
* Address Manager: Ultron team has been testing and debugging the address manager. Certain identified cases and issues were resolved.

**Blockexplorer**
* Redesign of ulxscan: Main page adaptivity and main page staging are done. Validators’ page preparation - in progress; 
* Validators APR count: Completed.

**UltronSwap**
* TX issue during withdrawal of WETH LP tokens - in progress;
* Wallet Connect “quota exceeded” issue: In progress.
* Farming Rewards Update: Completed.

**Ecosystem**
* Network Performance Tests: In progress. After review, environment setup will be revised (elimination of downtime, renaming adjustments).

## Ultron Foundation updates from 25.09-29.09

**NFT Staking HUB**
* Movement of  NFT transferability to the celery branch - In Progress;
* Creation of a task diagram based on Revenue share specs; initial version is currently under team review - In Progress;
* Recover of a lost monitoring address list - Completed;
* Update of the testnet subgraph - Completed;
* Export of bonus hub for buyback information - Completed;
* Team completed business logic tests;

**Infrastructure**
* Adding workers for AM operations optimization - In Progress;
* Introducing waiter receipt transaction worker - In Progress;
* Testing workers and addressing fixes while debugging the address manager - In Progress;
* Ultron team is updating Vesting contract UI;
* Ultron team has completed documentation on working with the Vesting contract;
* Ultron team finished preparation of documentation regarding Vesting smart contract functionality;
* Conducting performance tests of the network: Environment setup and issue resolutions are In Progress;

**Blockexplorer**
* Gas Tracker has been implemented on the backend and is now deployed to staging;
* Redesign of ulxscan: Desktop version has been deployed to staging (validator staking excluded);
* Validators APR counting is currently In Progress; the team has updated the frontend reward calculation formula;

**Bridges**
* Address of “502 in RPC logs” - Completed;

**Ultron Swap**
* “Quota exceeded” issue is In Progress and is scheduled for the beginning of the next sprint;

**Ultron Website**
* Partnership Form integration - Completed.

## Ultron Foundation updates from 18.09-22.09

**NFT Staking HUB**

* NFT transferability testing - in progress;
* Business logic tests - the developers team is adding tests for new functionality;
* Exchange rate subgraph implementation - in progress;
* API for Block the claim on the bonus NFT updating - in progress;

**Ecosystem**
* The address manager Upgrade spec preparation - on progress;
* Performance test on validator - completed;
* Vesting contract testing - in progress;

**Blockexplorer**
* Ulxscan redesign layout for desktop - completed;
* Vue3 migration - completed.
* Wallet connect upgrade - completed.
* Gas Tracker initial investigation - completed, implementation starts next sprint.

**Bridges**
* Certificate issue on BSC side - resolved.
* Manual transaction review ongoing for stuck transactions.

**Ultron Foundation website**
* Partnership Form design completed, implementation expected soon;

**L1**
* Network performance tests - ongoing.

## Ultron Foundation updates from 11.09-15.09

**NFT Staking HUB**

* Subgraph implementation - in progress;
* Metrics services updating - in progress;
* Change the parser for the second version of the staking contract in connection with the release of version 2 of staking - in progress;
* Smart - contracts improvement - completed, on review;
* Graph update and backend changes - completed, on review;
* Transfer of locks finished. Ultron team currently monitoring the situation and it’s work;
* Block the claim on the bonus NFT updated. The changes have been uploaded to the test;
* Rewards calculation moved to separate server;
* Performance tests for the current version of Staking contract - completed;

**Tokenomic**

* Developers are working on deploying gnosis services for the chainsafe service spec;
* Test contract Vesting deployment to the Ultron mainnet - finished;

**Blockexplorer**

* Redesign of ulxscan - assets pages are completed, non-adaptive transactions are ready;

**UltronSwap**

* Staking failed transactions bug - resolving in progress;
* Support Request issue - resolved;
* Swap Confirmation Bug - testing;

## Ultron Foundation updates from 04.08-01.09

**NFT Staking HUB**

* NFT transferability logic update - in progress;
* Ultron team completed the transfer of locks;
* Commission payouts in uUSDT on ultron network - on tests;
* Response issue with requests from utronswap-exchange - in progress
* Exchange rate subgraph update - in progress;
* Smart - contract update + adding exchange rate to obtain the value of the terminals - in progress;
* Ultron team updated claim mechanism on the bonus NFT in the api. The changes have been uploaded to the test. 


**Address Manager**
* Conducting performance tests on validator - in progress;

**Ecosystem**
* Ultron team is in  process of connecting Gnosis Safe contracts to the wallet application + deployment of gnosis services and changes to suit our needs;

**Blockexplorer**
* Redesign of ulxscan - in progress; 

**UltronSwap**
* Farming rewards update - updated farming data;
* Bug Fixes - bugs were fixed (connecting a wallet, removing rewards);


## Ultron Foundation updates from 28.08-01.09

**NFT Staking HUB**

* Update of NFT transferability logic, as well as endpoint updates and openapi preparation - in progress;
* Implementation of an address manager as a queue to solve the issue with nonce for ability to make multiple workers - in progress;
* Transfer of locks - in progress;
* Commission payouts in uUSDT on Ultron network - in progress;
* Purchase of NFT on Ultron network (uUSDT) functional - in progress;
* NFT staking v2 optimization - in progress;
* Bonus NFT claiming functional updates - in progress;

**Ecosystem**
* The Ultron team is writing a script for deploying chainsafe service to Ultron Network;
* Script preparation for Safe Wallet deployment on Ultron - in progress;

**Blockscout**
* Node deployment functionality - issues solving is finished, currently functional is planned to be implemented to the testnet;

**UltronSwap**
* UltronSwap updated design deployment - in progress;
* Creation of new CI for UltronSwap - completed;
* Front-end bugs and improvemts - minor issues fixed, modal resized, minor screen improvements - in progress

## Ultron Foundation updates from 21.08-25.08

**NFT Staking HUB**

* Ultron developers continue to work on the logic of transferability, endpoint updates and preparation of API updates;

* Conversion of locks to a new smart contract in the mainnet - in progress;

* Code refactoring update - in progress;

* Optimization of the NFT staking contract V2 - in progress. Developers are working on solving security issues;

* Spec for transferability update - in progress;

* Blockers optimization completed. Ultron team switched to listening to events from the blockchain;

* Tests for the payout functionality for a staking contract added. All changes uploaded to the mainnet and testnet;

**Tokenomic**

* Creation of the script for deploying wallet update in Ultron network and integrating the ledger and testing - in progress;

**Blockscout**
* Nodes deployment - team is currently working on finding and fixing minor issues;

**UltronSwap**
* UltronSwap redesign - all pages have been deployed to the stage, and work on the bridge update is in progress;

* Minor front-end issues fixed and improvements implemented;

## Ultron Foundation updates from 14.08 - 18.08.2023

**NFT Staking HUB**
* Ultron team improved logic of NFT transferability;
* Conversion of locks - in progress;
* Data transfer to a new smart contract in mainnet - in progress;
* Blocks working logic improved. Ultron team will switch to listening blockchain events (EVM) to reduce records amount in the database and assure smooth work of network;
* Spec on NFT transferability prepared;
* API for claim on the bonus NFT block updated;
* Ultron team switched to using TRON fullnode API;
* Block scanner for Ultron network for buy NFT on ultron network (uUSDT) completed. Currently team performs final checking;
* Interface to run manage commands scripts in k8s for NFT Staking HUB completed.
* General refactoring of the code for updating the cellery branch completed;
* Ultron team rechecked the Unlocks and claims logic to be fully prepared for upcoming payouts.

**UltronSwap**
* Redesign of UltronSwap. Swap pages, ULX wrap, bridges and farm preparation completed for desktop version.
* Staging Deploy. Team uploaded all updated pages for staging.
Ultron main website
* New Whitepaper uploaded.

## Ultron Foundation updates from 07.08 - 11.08.2023

**NFT Staking HUB**
* Redistribution of locks issue solving - in progress;
* Development of a blacklist for nft in v2 staking contract - in progress.
* Execution of the high level tests for staking v1 and performance of detailed tests for staking v2 - in progress.
* Deployment of subgraphs to new production nodes - completed.

**Bridges/infrastructure**
* Transaction cancellation issues fixes completed.

**Blockscout**
* Deployment of blockscout to testnet and fixing minor issues - finished;

**Ultronswap**
* Ultronswap redesign - in progress.

## Ultron Foundation updates from 31.07 - 04.08.2023

**NFT Staking HUB**

* Conversion of locks - in progress;
* Data based on the mainnet data corrected. Formula for the second version of staking and for gaming nft adjusted.
* Changing of the parser for the second version of the staking contract - in progress;


**Ultron Bridge**
* Implementation of a logging system - in progress;

**Blockscout**
* Ultron team redeployed  node and finished tests . Will be uploaded to the test network;

**UltronScanner**
* Redesign of ulxscan - estimated, started;
UltronSwap:
* The redesign is estimated and UltronSwap website front is preparing for it


## Ultron foundation updates from 24.07 - 28.07.2023

**NFT Staking HUB**
* Data transfer to a new smart contract in mainnet. in progress;
* Fix transaction re-processing - Completed;
* Execution of the high-level tests for staking v1 and detailed tests for staking v2 in progress;
* Checking data for all types of NFT gaming packages (regular task) - in progress;
* Updating the сelery branch - in progress;


**UltronSwap**
* Ultronswap movement from AWS to Cloudflare - Completed;
* Check all subgraphs and fix logic when lagging behind - Completed;
* vULX (liquid staking) - preparing specs in progress;


**UltronBridge**
* Frontend: get data from the backend - Сompleted
* Archiving instances from the bridge to aws - Completed


**Ecosystem**
* Validators update - Completed;
* Balance monitoring dashboard preparation - in progress;
* Vault monitoring preparation - in progress;
* Deployment of Tron API to k8s - in progress;
* Ansible deployment configuration (regular task) in progress;
* Deploy internal mainnet-ultron API - in progress;
* Delete old resources from AWS - Completed;
* SAFE INIT INFRA3 - in progress;

## Ultron foundation updates from 17.07 - 21.07.2023

**NFT Staking HUB**

* Extended migration with support for both static and dynamic USD value;
* Data transferred to a new smart contract in testnet;
* Data transfer to a new smart contract in mainnet - in progress;
* Execution of the high level tests for staking v1 and detailed tests for staking v2 - in progress;
* Celery branch update - in progress.



**Ultron bridge**

* Deployment of chainbridge in k8 finished;
* Control of chainbridge services setup - in progress;
* Team solved the issue of gas underestimation;
* Team created the system of retries for underpaid transactions;
* Archiving instances from the bridge to AWS - in progress;

**DEX**

* Subgraph updated and modified;
* Move Ultronswap zone from AWS to Cloudflare - in progress;
* Subgraph issues checking and solving - in progress;


**Website**
* DNS switched to the new ultron.foundation;

## Ultron foundation updates from 03.07 - 07.07.2023

**NFT Staking Hub**

* Team checked and solved the case with Nft;
* Fixed total stake issue case;
* Dollar cap checked and fixed;
* Speed up block processing on tron blocker fixed;
* Business logic tests for gaming NFT and BatchPayoutQueue added;
* Aggregating business metrics on prometheus completed;
* Checking the balance when withdrawing tokens on the processing - uploaded to production;
* Team changed the parser for the second version of the staking contract;
* Subgraph logic update implemented, team making final check;
* New spec was written and approved;
* Execution of the high-level tests for staking v1 and detailed tests for staking v2 - in progress;
* Updating the claim on the bonus NFT in the smart contract- in progress;
* Fix of transaction re-processing - in progress;
* Rechecking data before migration - in progress;
* (support) manual order confirmation - in progress;
* Migration of rewards to separate server - in progress;

**Blockexplorer**

* Add the function of adding a token to the metamask to Assets - in progress;
* Updating the list of our official tokens + icons - in progress;

**DEX**
* Check scroll page Farm (completed)
* Update the list of our official tokens + icons on DEX (completed)


## Ultron foundation updates from 03.07 - 07.07.2023

**NFT Staking HUB**

* Dollar cap check and fix+ checking if there is an issue with the dollar cap in mainnet - completed;
* Checked and fixed issue with Bonus Hub stake and earnings;
* Parser for the second version of the staking contract Changing - in progress;
* Execution of the high level tests for staking v1 and detailed tests for staking v2 - in progress;
* Data transfer to a new smart contract in testnet for staking v2 - in progress;
* Address manager to improve the transactions delivery (analogue of Firefly) preparation - in progress;

**Infrastructure**
* Transaction re-processing fixing;
* Processing - Deployed and tested on the test environment. Testing of the main functionality of Processing deployed in a cube has been completed.
* Migration of rewards calculation to separate server - in progress;
* Deployment of chainbridge in k8 - in progress;

**UltronSwap**

* Farming rewards update (farm page), July 2023 - completed;


## Ultron foundation updates from 26.06 - 30.06.2023

**NFT Staking Hub**

**Completed**
* Change the owner in the NFT smart contract (all the issues fixed)
* Statistics of the amount of incoming payments per day added (realtime ecosystem metrics);
* Form of auto-returns for gaming nft added;
* Block scanner updated;
* NFT staking v2 - in progress;
* Updating parser - in progress;
* Review of treasuries tokenomics - in progress;
* Fixing issue with the total stake - in progress;
* Balance tracking functionality - in progress;
* Dollar cap issue in mainnet fixed;

**Infrastructure**
* Migration of processing to k8 - in progress;

**Ultron bridges**
* Deployment of chainbridge in k8 – in progress


## Ultron foundation updates from 19.06 - 23.06.2023

**NFT Staking HUB**
* Corrected base stake;
* Fixes of old issues with Stake Ratio status for some hubs between 10 Aug - 13 sept - completed;
* Merged legacy NFTs into bonus NFTs;
* Corrected legacy values;
* Re-set the buybacks;
* Imported Buybacks;
* Added to the parser buybacks import #1,2;
* Business statistics of the token processing module (rea-time ecosystem metrics) uploaded;
* NFT staking v2 - in progress;
* Migration of processing to k8 - in progress;
* Explore using Firefly supernode for our projects - in progress;
* Gaming NFT smart contract currently preparing for the audition;

**Ultron bridge**
* Deployment of chainbridge in k8 - in progress


## Ultron foundation updates from 12.06 - 16.06.2023

**NFT Staking HUB**
* Web3py Updated to v6;
* Transaction re-processing fixed;
* Block scanner updated;
* Fixes of old issues with Stake Ratio status for some hubs between 10 Aug - 13 sept - completed;
* Corrections by Correct base stake uploaded;
* Redeployment of the NFT staking v2 contract to the mainnet with the changes made - in progress;
* Monitoring dashboard with business metrics - in progress;

**Bridge**
* Deployment of chainbridge in k8 - in progress;

**Dex**
* Minor issue with «Harvest» button fixed;
* Minor UI interface issues fixed;
* New farm pools and bridge pairs added;

**Website**
* Minor UI updates performed;


## Ultron foundation updates from 05.06 - 09.06.2023

**Ultron Swap**

* New farm pools and bridge pairs added (CAKE and DOT);
* MAX function issue fixed;
* UltronSwap UI update preparation - in progress;

**NFT Staking HUB**

* Launching updated version on the tetstnet and moving the production stage (In progress);
* Changes in the subgraph (In progress);
* Updating the celery branch;
* Id mapping in the processing database and in the blockchain correction;
* Rechecking base stake (In progress);
* Balance monitoring (In progress);
* Monitoring dashboard with business metrics - in progress;
* Data transfer to a new smart contract in testnet - in progress;
* Data transfer to a new smart contract in mainnet - in progress;
* Updating the block scanner - in progress;
* Execution of the high level tests for staking v1 and detailed tests for staking v2;

**Infrastructure**

* Proxy for binance nodes deployed on dev, currently preparing to go for production stage;
* Completion Volt - in progress;
* Finalization of the IPFS cluster - in progress;
* Developers are analyzing issues of the PC cluster, finalizing haproxy under rpc (dedicated cluster + certificate);

## Ultron foundation updates from 29.05 - 02.06.2023


**NFT Staking HUB**

* NFT staking v2 - staking contract v2 and the subgraph are deployed in production. Ultron developers switched the processing in the testnet completely to the second version and currently it is under tests;
* Collecting data on a graph for business metrics in monitoring dashboard - in progress;

**Infrastructure**
* Migration of processing to k8 - devops team started updating the celery branch (to add changes for NFT’s).

ULXScan:
* Parsing alerts from sentry (Completed);

**DEX**
* Added FTM and AVAX adding to UltronSwap (In progress);
* Farming rewards updated;
* PEPE token added;
* Issue with displaying LP value staked in Farms solved;
* MAX function issue correction (In progress)

**Website**
* Updating whitepaper file on the ultron foundation website;

## Ultron foundation updates from 22.05 - 26.05.2023

**NFT Staking HUB**

* Adding new Gaming NFT packages - in progress;
* Burn unused gaming nft’s - completed;
* Pre-sale of Gaming NFTs  preparation and deployment - completed;
* NFT staking v2 preparation - in progress;
* Verification of the functions of the old and new contract + transfer all backend functions to the protocol of the new contract - in progress;
* Data transfer to a new smart contract in testnet - completed;
* Redeployment and setup graphs for multiple environments - in progress;

**Infrastructure**
* Set up monitoring for vaults while in operation - in progress;
* Refinement of CI - Based on Solutions - completed;
* K8 support maintenance - in progress;
* Running IPFS in cluster mode in a k8s - in progress;
* Refinement of the system for collecting metrics - in progress;

**Ulxscan**
* Parsing alerts from sentry Ulxscan - in progress;
* Update web3modal v.2 Blockexplorer - in progress;

**UltronSwap**
* Debug DEX with browser trust wallet - in progress;
* Fixing incorrect display of BNB price on Swap - completed;
* Adding new farm pools and bridge pairs - in progress;
* Bug with looking for reserves for swap - in progress;

## Ultron foundation updates from 15.05 - 19.05.2023

**NFT Staking Hub**
* Send payouts from csv or xlsl file - completed;
* NFT staking v2 - work in progress;
* Subgrapgh tests for the subgraph checking and writing - in progress;
* Data transfer tests in the testnet correction check - in progress ;
* Fixing issue with usd value in buybacks + duplication of buybacks - in progress;
* Accrual of missing amounts of rewards for parts 1 and 2 of the buybacks imports - in progress;
* Fixing calculations - in progres;
* Correcting legacy values - in progress;
* Setting correct package id - in progress;
* Merging legacy NFTs into bonus NFTs before the end of the week - in progress;
* Adding transaction status checks for automatic retry implementation - in progress;
* Adding retry for a nonce error - in progress;

**Blockexplorer**
* Parsing alerts from sentry Blockexplorer - in progress;

**Ultron Bridge**
* Fixing incorrect rate in a chart - completed;
* Making a system of retries for underpaid transactions - in progress;
* Solving the issue of underestimating gas - in progress;

**UltronSwap**
* Adding new farm pools and bridge pairs - finished for Matic and BNB;
* Wagmi update, ethers to view migration, fixing issues with added custom tokens - completed;
* Evaluating and debugging dex with browser trust wallet - completed;

**Website**
* Add Sentry Filtering - completed.

## Ultron foundation updates from 08.05 - 12.05.2023

**NFT Staking HUB**
* Fixed issue with wulx and nft transfer from non-main addresses to main address - completed;
* NFT staking v2 preparation  - in progress
* Testing updated smart contract with the transaction and comparing received data by the backend script - in progress;
* The implementation of the subgraph changes finished and deployed locally, soon it will be deployed on testnet;
* Monitoring dashboard with business metrics - in progress;
* Fixing issue with usd value correcting in buybacks and buybacks duplication - in progress;
* Accrual of rewards for parts 1 and 2 of the buybacks imports - in progress;
* Fixing issue with dollar cap calculation - in progress;
* Package id setting - in progress;
* Legacy values correction - in progress;
* Merging legacy NFTs into bonus NFTs - in progress;
* Setting correct package id - in progress;

**ULXScan**
* Updated tests - completed;

**Ultron Bridge**
* Evaluating and debugging DEX with browser-based trust wallet - in progress;
* Solving gas underestimation problem - in progress;
* Redoing the retry system - in progress;
* Chainbridge deployment in k8 - in progress;

**Website**
* Updated tests for Ultron main website - in progress;

## Ultron foundation updates from 01.05 - 05.05.2023

**NFT Staking HUB**

* Processing metrics added to the monitoring - completed;
* The implementation of changes was finished in the spec for NFT staking v2- completed;
* The team started working on a subgraph for NFT staking v2 - in progress;
* Data transfer by using a refactored version of the staking contract - completed;

**Ulxscan**
* Adding blockexplorer to the notification system - in progress;
* Implement Sentry logic on prod Blockexplorer - completed;
* Optimization of getting prices - completed;

**Bridge**
* Solve gas underestimation problem - in progress;
* Redo the retry system - in progress;

**UltronSwap**
* Farming rewards update for May 2023 - completed;
* Implement Sentry logic on prod DEX - done;

## Ultron foundation updates from 24.04 - 28.04.2023

**NFT Staking HUB**
* Custom celery service was written, and health checker completed; 
* Refactoring of the current smart contract and uploading to the testnet - completed;
* Changes on the contract for data conversion - completed. 
* Implementation of the backend for storing all information about all NFTs with unlocks - completed; 
* Script to verify the data of the old smart contract and the new one - completed. 

**Infrastructure** 
* Scaling of workers - in progress;
* Celery set up - in progress;

**UlxScan**
* Getting uUSDT price from CoinmarketCap - completed
* Adding a possibility to perform the search in the NFT metadata to find the result by nft id = 0 - completed
* On the NFT metadata page for buyback and legacy packages, the option of showing zero dollar cap was added; 
* CHAIN TO information saved when the page is updated - completed

**Bridges**
* Solving issue with gas estimation - in progress
* Upgrading the retry system - in progress; 
* Ultron is the default chain if the wallet is not connected - completed; 
* Deploying chainbridge in k8 - in progress; 
* Testing and refinement of the UltronSwap issue notification system -  in progress;
* End2end tests updated; 
* API Changed to CoinmarketCap API 2.0 - completed; 
* Pop-up adding for loading transaction - in progress; 
* Making adaptive UI for different devices - in progress;

**Website**
* Updating Roadmap (in progress)
* Adding new partner projects to the Ecosystem tab + to the footer - completed; 
* Adding a new photo to Our team - completed; 
* Correcting Our Team info - completed;

## Ultron foundation updates from 17.04 - 21.04.2023

**NFT Staking HUB**

* Accrual of missing amounts of rewards for parts 1 and 2 of the buybacks imports - completed;
* Issue fixed with old packages appearance;
* Subgraph transferred to a new instance;
* Fixing issue with buybacks data;
* NFT staking v2 - in progress. 
* Refactoring the current smart contract - in progress;
* Data transfer to a new smart contract - in progress;
* Implementation of test design high-level tests for staking v1 and detailed tests of staking v2;
* Monitoring dashboard with business metrics implementation - in progress;
* Adding the required cumulative metrics to the graph - in progress;
* Service-checker of node status and number of transactions on it - in progress;
* Fixing issue with calculation - in progress;
* Fixing issue with autocompound data after the compound status change - in progress;

**Infrastructure**

* Migration of processing to k8 - in progress;
* Business logic tests - completed;
* Admin panel improvements - completed;
* Pools integration into the backend - completed;
* Transaction waiting added to the Tron network; 
* Deployment and testing processing on testnet - in progress; 
* CI GitLab - in progress; 
* Chainbridge deployment on k8s - in progress; 


**UlxScan**
* Minor UI changes made;  
* Assets displaying issue fixed; 
* NFT Metadata search improved;
* Chain info saved when after page updates;
* uUSDT price updates received from CMC - in progress;
* Optimization of getting prices - in progress; 
* NFT id search results improvement - in progress;
* Dollar cap updates on the NFT metadata page for buyback and legacy packages - in progress;

**UltronBridge**
*  Make Ultron default without a wallet connection - in progress;
*  Bridge admin panel improvements;

**UltronSwap**
* Update end2end tests (in progress);
* API Changed on CMC API 2.0 ;
* Liquidity issue solving - completed;
* Solving issue from Sanity - completed;
* Contracts in other networks added to UltronSwap;


**Ultron Website**
* Roadmap Updates - in progress;
* Partner projects added to the Ecosystem tab  - in progress;
* New blog added;
* Partners list updated;

## Ultron foundation updates from 10.04 - 14.04.2023

**NFT Staking HUB**

* Integration of diamond API with a basic implementation of the staking facet - in progress;
* Refactoring of the current smart contract - in progress;
* Data transfer to a new smart contract. Implementing Backend infrastructure to store information about all NFTs with unlocks - in progress;
* Accrual of missing amounts of rewards for parts 1 and 2 of the buybacks imports - in progress;
* NFTs swapping - in progress;

**Infrastructure**

* Migration of processing to k8 - in progress;
* Business logic tests - in progress
* Integration of tests into the process of building an instance - - in progress;
* Integration of pools in the backend to distribute the load during database connection - in progress;
* NFT data management tools implementation - in progress;


**ULXScan**

* Add caching on the proxy - in progress;
* Add sentry - finished;
* Validators mechanism update - finished;

**Ultron Bridge**

* UX improvement (now users are able to add assets to MetaMask immediately) 
* Deployment of bridge relayers in k8 - in progress;
* Fixing Issue with ETH/Ultron - finished;

**UltronSwap**

* DefiLama information update - in progress;
* End2end tests updated;

## Ultron foundation updates from 03.04 - 07.04.2023

**NFT Staking Hub**

* Auto-return form for subscriptions updated; 
* Staking HUB receipts improved; 
* NFT staking v2  - in progress; 
* Tests for diamond architecture implementation - in progress; 
* Refactoring of the current smart contract - in progress;
* Accrual of missing amounts of rewards for parts 1 and 2 of the buybacks imports - in progress;
* Merge legacy NFTs into bonus NFTs - in progress; 
* Calculation issue fixed; 

**Infrastructure**

* Migration of processing to k8 - in progress
* Deployment and testing  processing on testnet - in progress; 
* Deployment of chainbridge in k8 and tests implementation - in progress; 


**Ultron bridge** 

* Issue with ETH/Ultron fixed;
* Issue with Binance network fixed;


**UltronSwap**
* Rewards Updated;

**Ultron website** 

* Minor interface updates; 
* Whitepaper updated;

## Ultron foundation updates from 27.03 - 31.03.2023

**NFT Staking Hub**

*  Fixing issue with adding function to the testnet for the graph for autocompound status change;
* Final improvements made after Solidity Finance's DAO smart contract audit; 
* Bytecode built and committed into the repository with instructions; 
* Receipts correction finished for all packages and buybacks and legacies including autocompounds; 
* Improvements to the script that collects balances from temporary addresses were performed; 
* Repository for new version of smart contracts - in the process;
* Issue with invalid dates in autocompound after flag changing fix - in progress;
* Fixing minor calculations issues with rewards accrual for users going off - in progress; 

**Infrastructure**
* Deployment and testing new processing on testnet - in progress; 
* Celery configuration - in progress
* Checking unit tests + setting up CI for tests - in progress; 
* Preparation of dependent services - in progress; 
* Calibration of scaling workers on testnet - in progress; 


**UltronSwap**
* Test cases writing and implementation - in progress; 
* Fix of cron brewulx script - finished; 

**UltronWebsite**
* Whitepaper updated; 
* Domain transfer preparation, DNS records replacing - finished; 

**Ulxscan**
* Setting up and testing of new network explorer (blockscout) - in progress;
* Validators issue checking and fixing - in progress;

## Ultron foundation updates from 20.03 - 24.03.2023

**NFT Staking Hub**

* Fixed the dev environment issue with slow payments confirmation;
* Fixed issue with incorrect data was set during buybacks import;
* Fixed issue: buyback NFTs could be accidentally burned;
* Fixed issue: Did not transfer wulx and nft after transferring nft from non-main addresses to the main address; 
* New connections added to NFT Staking Hub smart contract;
* Accrual optimization finished; 
* Package type validation added to admin panel; 
* "txqueue" recheck script after execution added, recheck all current txqueue element performed; 
* Rewards processing system: migration to separate server - performing; 
* Finished setup of USD value = 0 for buybacks and legacy packages; 
* System improved after Solidity Finance's DAO smart contract audit; 


**Infrastructure**

* Maintenance of processing migration to k8; 
* Processing deployment and testing on testnet - unit tests and CI setup for testing finished; 
* Scaling workers calibration on testnet finished; 
*  Celery configuration finished; 


**Ultron website**

*  Terraform/terragrunt resources created;  
*  New CI/CD development;
*  Domain transfer; 
*  Creation of a new environment with terraform/terragrunt+gitlab for production;

## Ultron Foundation updates from 13.03-17.03.2023

**NFT Staking Hub** 
* Finished enabling autocompound ON/OFF processing;
* Order processing without NFT finished;
* Staking HUB stake update finished; 
* Adaptive Gas Size in Tron network implemented; 
* Receipts for all packages and buybacks and legacies including autocompounds corrected;
* Data issues with importing buybacks fixed;
* Migration of rewards processing to separate server;
* Upgrading system after Solidity Finance's DAO smart contract audit; 


**Infrastructure** 
* Migration of processing to k8;
* Deploy and testing on testnet; 
* Business logic tests implementation;
* Porting the recent logic changes to the celery queue processing code;

## Ultron Foundation updates from 06.03-10.03.2023

**NFT Staking Hub** 

* Buying NFT on Ultron network with uUSDT - final preparation for deployment; 
* Commission payouts in uUSDT on Ultron network - final checking and preparation for deployment;
* Subscription processing - final checking and preparation for deployment;
* Correcting receipts for all packages and buybacks and legacies including autocompounds;
* Removing old packages which are not used;
* Adding "txqueue" recheck script after execution, rechecking  all current txqueue elements;
* Setting correct package id;
* Rechecking all legacy data;
* Adaptive Gas Size in Tron implementation;
* Fixing issue: Did not transfer wulx and nft after transferring nft from non-main addresses to main address;
* Merging legacy NFTs into bonus NFTs;
* Fixing issue with buyback imports;
* Staking Hubs update;
* Web3modal v.2 update in progress


**Infrastructure** 

* Migration of processing to k8s;
* Deploying processing and testing on testnet;
* Business logic tests implementation;
* Merging the current version of the code into the new branch;
* Transferring a subgraph to a new instance;
* Accrual optimization - the load on the database reduced by 15%; 
* Upgrading system after Solidity Finance's DAO smart contract audit. 


## Ultron Foundation updates from 27.02-03.03.2023

**NFT Staking HUB**

* Testnet Review - rechecking the logic of the work and relevance of the backend architecture;
* Automation of checking the rewards calculation and payouts;
* Subscriptions payment processing;
* Buy NFT on Ultron Network (uUSDT) - final improvements and testing; 
* Commission Payouts in uUSDT on Ultron Network - final improvements and testing; 
* Checking and solving the issue with NFT packages displaying;
* Fixing issues with incorrect data setting during Buybacks import;
* Continuing making improvements after Solidity Finance's DAO smart contract audit;
* Making correct receipts for all Packages, buybacks and legacies including autocompounds;
* Automation of the script in the parser which counts receipts in CSV for updating CSV files for new transactions;
* Checking and solving the Issue with turning autocompound on for some accounts;
* Migrating rewards service to Separate Server;
* Making additional connections In Smart Contracts, improving work and stability;

**Infrastructure**
* Continue migration of processing to k8s;

**Ulxscan**
* Displaying uUSDT and uUSDC amount for any address on ulxscan.com;

**Ultronbridge**
* Preparation of new tokens on the bridge for release;

## Ultron Foundation updates from 20.02-24.02.2023

**NFT Staking HUB**
* Implementing and deploying new test infrastructure for NFT Staking Hub;
* Migration of NFT Staking Hub project to cluster database;
* Package ID monitoring system update; 
* Monitoring the accrual of rewards;
* Fixing data issue with importing buybacks;
* Adding processing post-execution results monitoring script (txqueue); 
* Working on withdrawal limits and buybacks extra validation;

**UltronSwap**
* Local activation of the sentry;

**Bridge**
* Preparations for adding new tokens;
* Monitoring and executing the transactions;

**Infrastructure**
* Installing the consul on a test cluster;
* Importing new database structure for work improvement;
* Expansion of space on virtual servers;
* Genesis generation and upgrade check;

## Ultron Foundation updates from 13.02-17.02.2023

**NFT Staking HUB** 

* Adding unit tests for checking packages that are currently inactive and should be removed.
* Logging the current version of the processing;
* Checking and solving the issue with turning autostake off by the users. 
* Fixing the issue with ulx and NFT transferring; 
* Implementing  mechanism of adaptive Gas Size in Tron network; 
* Checking USD value for buybacks and legacy packages; 
* Improving the buybacks importing feature;
* Migration of NFT Staking HUB and related projects backend to the new repository; 

**Infrastructure**
* Move processing production database to a different cluster; 
* Upgrading nodes for the Ultron network; 
* Updating backend and infrastructure in accordance with the results of Solidity Finance's DAO smart contract audit; 

**Ultron Bridge** 
* Minor UI improvements; 
* Preparing the infrastructure for adding new tokens to Ultron bridge;

**Ultron Website** 
* Implementing simplified mechanisms and infrastructure for faster website loading and simplified updates; 
* Minor UI improvements in the Blog segment;


## Ultron Foundation updates from 06.02-10.02.2023

**NFT Staking HUB**
* Payout addresses logic improvement; 
* Updating gas fees in Tron;  
* Making improvements accordingly to Solidity Finance's DAO smart contract audit; 
* Updating the ABI and add the dollar value mapping to the NFT metadata section in the Explorer and in the utility (the nft-info-ui repository)

**Ecosystem** 
* Upgrading nodes for Ultron network; 

**Website**
* Minor UI improvements; 

**UltronSwap**
* Updating web3modal; 

**Ultron Bridge**
* Chainbridge architecture upgrading;

## Ultron Foundation updates from 30.01-03.02.2023

**NFT Staking Hub**

* Checking order status, and completing unfinished orders;
* Checking the user's bonus nft's; 
* Solving internal issues for the backend receiving new changes about autocompound immediately;
* Making edits on the "Manage" smart contract; 
* Optimized processing of the events at the backend;
* Data schema updates on the processing backend;
* Fixing the issue with the order id link;
* Upgrading nodes of the Ultron network, debug tracing data;
* Withdrawal limits improvement;
* Automation of checking the rewards calculation and payouts;
* Adding script with metrics;
* Metrics monitoring improvement;
* Rechecking all legacy data;
* Adding extra script that changes payout addresses if necessary; 
* Switching queues to celery and deployment in k8s;
* Integration of logs processing;

**Ultron Bridge**
* Chainbridge - improving the metrics and tasks for the backend, prepare the deployment to the k8s cluster;

**Ulxscan**
* Switching the site to a new static generation process;

**Ultron Swap**
* Web3 modal update;
* Parsing alerts from the sentry;

**Website**
* Switching the site to a new static generation of html pages;
* Development of schemes for pages, content

## Ultron Foundation updates from 23.01-27.01.2023


**Scanner**
* Minor issue on staking front page improved;
* Migration to vue 3 performed;

**Website**
 * Google analytics metrics and data collection improved; 
 * Improvements on website data management tools;
 * Search with fuse js added;;
 * Minor edits (imposition has gone);

**Bridge**
* Continued implementation of alerts and backend;

**NFT Staking HUB**

* Adding signatures saving;
* Merging dev and main branches;
* Readonly_fields for all fk/m2m added;
* Replacing all jsonfield with textfield, transferring values with a separate management command, checking handlers;
* Set a delay of 12 blocks in all blockers;
* Parallelization of rewards;

## Ultron Foundation updates from 16.01-20.01.2023

**NFT Staking Hub**

*  Fixed issue: the balance in webhook could be zero, because of this some of the orders were not processed;
*  Import of updated buyback mechanism;
*  Withdraw usdt from the wallets of old orders and send to treasury; 
*  Correcting links in the "staking" smart contract for bybacks and imported NFTs; 
*  Correction of automatic commission payments from the backoffice (bsc usdt); 
*  Set a delay of 12 blocks to avoid reorgs; 
*  Implement calculation change for airdrop with disabled autocompound on the current version of staking (Rewards airdrop calculation update);
*  Price getter deployed to production; 


**Website**
*  Transfer to statically generated deployment;
*  Changed the current year to 2023 everywhere (explorer/dex/bridge);
*  Refreshed partner logos;


**UltronSwap**
*  Fixed functionality availability in other networks;
*  The loader is shown now during loading of the balances;

## Ultron Foundation updates from 09.01-13.01.2023

**NFT Staking Hub**
* Wrong package id fixed;
* Buybacks id fixed;
* Import of the delayed buybacks through the market implemented;
* A delay of 12 blocks in BSC blockchain was applied to avoid possible chain reorg; 


**Infrastructure**
* Calculation change for airdrop when autocompound=off on current version of staking (Rewards airdrop calculation update) - completed, now testing; 
* Upgrading nodes for the Ultron network, setting up private nodes for BSC and Tron; 
* Queues on celery are refactored;

**Website**
* Website migration is almost complete;
* Static generation of all pages is configured;
* Minor changes in data (added a blog and new employees information)

## Ultron Foundation updates from 02.01-06.01.2023


**NFT Staking Hub**
* NFT Staking Hub price update;
* Fix issue with commission payments;
* Update and fix the rewards service (improved monitoring);

**Ecosystem**
* Updating smart contracts after audit, preparing new contracts;
* Update token processing stability and scalability;
* Airdrop service update (withdrawals);
* Nodes improvement - version upgrade, updated genesis preparation;


## Ultron Foundation updates from 26.12-30.12.2022

**NFT Staking HUB**
* Updating autocompound feature; 
* Updating buyback and withdrawal mechanism; 
* Solving issues with withdrawals; 


**Infrastructure**
* Server issues solving;
* Setting up custom nodes for private API of other blockchain networks;
* Continue moving to cluster setup;

**Website**
* Refactroring;
* Data moving for statistical overview; 
* Solving minor interface issues;


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
