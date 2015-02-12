# CrowdFundrr
A decentralized, fully transparent, open-source crowd funding DApp build on Ethereum.

<img src="/img/screen0.jpg" />

### Front-End
http://crowdfundrr.github.io/

### When Deployed
- You can create, donate to, discover and track new campaigns
- Link to campaigns via http://www.crowdfundrr.github.io/?id=CAMPAIGN_ID
- Embed a link, upload an image on your website to be used on Discover interface
- Get payed out when campaign is finished

### Components
- jQuery v2.1.1
- Bootstrap v3.3.2 
- bignumber.js v2.0.0
- ethereum.js
- bootstrap-datepicker.js

### Requirements
- cpp-ethereum node by Gavin Wood or
- go-ethereum browser by Jeffrey Wilcke

### Installing
Crowdfundrr is presently undeployed on POC 8 Testnet but is tested on Mist/AlethZero
- Git clone the Crowdfundrr/Crowdfundrr repo
- Transact Crowdfundrr.sol hex to your local chain or testnet
- Change var contractAddr value to your new contract address in JS/Crowdfundrr.js
- Then start creating campaigns and using Crowdfundrr
- Note** you can use arrow keys to get local addr's when inputing beneficiary address

### Contract/DApp Functionality
All core features should be exposed through the UI and access the companion contract:
- Landing Page
- Link to a campaign via the URL
- Create a campaign
- Contribute to a campaign (donate)
- If sufficient funding received, payout to campaign recipient
- If expired, refund to contributors
- Display progress report of a campaign
- Find new campaigns to donate to (Discover)

### Solidity
- Original contract based on Chriseth's Crowd Funding example
- Modifications and additions are done me SC

### TODO
- Deploy on POC 8 Testnet
- Flavicon
- Form Clean Up (value trimming)
- Better Comments
- Fix Date Picker Bug
- Share Link on Tracker Page
- Cleaner JS/HTML
- Reorganize Folder Layout

<!--
### COMPLETED
- Mist Testing
- AlethZero Testing
- Clear campaign data when Campaign Complete or Expired
- If sufficient funding received, payout to campaign recipient
- Address Scroller (for easily selecting addresses)
- Payout/Goal Reach Front-End Complete
- Most Recent Campaigns
- Cleaned Up JS
- Display progress report of a campaign
- Date Picker Added
- Campaign/Discover Page Categorization
- URL/EMBED Code Generation (post Campaign Creation)
- JS Compaign Tracker Days, Convert to ETH denominations
- Discover Page
- New Campaign ID, url and meta tag return
- Display progress report of a campaign
- Contribute to a campaign (donate)
- Landing Page
- Link to a campaign via the URL
- Added User numCampaigns and campaigns data
- Search Campaign
- Create New Campaign JS->Solidity
- Connect HTML/JS front-end to BC
- Develop contract to fit contract functionality in Solidity
- Build bootstrap front-end
- Branding/Name Logo-->

### FUTURE TODO
- iframe portal for each campaign
- better badge for EMBED
- Clean up UI for tracker/New Campaign
- Hookup to a Central Name Registry Contract
