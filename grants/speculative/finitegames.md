# Finite Games

## Project Description
Finite Games is focused on the development of the tools and conceptual demonstrations to support hypercasual e-sport experiences. These experiences will emphasize the extension of the capabilities of blockchain gaming beyond player ownership to the design of mechanisms where in-game decisions have an explicit impact on all other players through a finite world. Essentially, we are creating a persistent global environment where resources are not just finite but consumed during gameplay. Through the use of blockchain digital assets, we can support the development of interoperability. 

To support this foundational concept, we believe that the use of finite digital assets can democratize the esports experience across various aspects of the industry’s verticals. To achieve this democratization, we plan to create NFTs that have a separate permission assigned to the source of its visualization components. This can be used to create an advertisement marketplace where sponsors can directly purchase the ability to rebrand/reskin a player's items based on negotiated conditions. The various functionality will provide a foundation for scaling the esports experience and increasing engagement through the gameplay mechanics. 

The establishment of an independent non-fungible token (NFT) marketplace focused on the adtech market has the potential to create a novel use to create lucrative B2B2B (Business to Business to Consumer) opportunities. This could play an important part in establishment the technology stack to support interoperable gaming and individual participation in the advertisement and sponsorship space. We will integrate this project initially as a parachain. However, this will require some development on the substrate framework to provide the components for execution. 

Our team is interested in this project because we wanted to create gaming experiences that have longevity and could make the onboarding of our friends into the cryptocurrency space easier. We are also interested in seeing the economics of our system implemented. We beleive we can create a more accessible means of esports. Also, this infrastructure can be the foundation for even more innovative use cases.

## Team members
 * Jomari Peterson is the team lead. He is serial entrepreneur with a focus on the design of innovative systems and business models. His past work can be found on Linkedin: (https://www.linkedin.com/in/jomari/) and Github (https://gist.github.com/jomarip). Some of his successes include delivering a 10x return as a co-founder of the Quantum Resistant Ledger. He was able to facilitate its growth to $100M valuation. He has also designed novel approaches to proof of stake and microlending solutions. In addition to attending Carnegie Mellon University for his PhD in Engineering & Public Policy, he graduated from Howard University with a focus on a Masters in Business Administration. He also also traveled as an international speaker on Economic Systems, Incentives and Mechanisms. 

 * Whitney Griffith is the developer who initiated the smart contracts that lead to winning at the SF Blockchain Week Gaming Hackathon. Her pastwork can be found on Linkedin (https://www.linkedin.com/in/whitneygriffith/) and on github (https://gist.github.com/whitneygriffith). Some of her past successes includes being a serial blockchain hackathon winner and Startup Bus winner with Small Street. She is also the Director fo Developer Relations with the Carribean Coding Academy and Microsoft Commercial Software Engineeer. She graduated from Howard University's computer science program. 

## Team Website	
* https://finite.games

## Legal Structure 
Hajj Media, LLC

## Team's experience
Jomari Peterson  If the project involves development work, then we'd appreciated if you can single out a few interesting code commits made by team members on their past projects.  We'll glance at whole repositories too, but not if they contain many vendored dependencies, which often makes commits easier. 
https://github.com/whitneygriffith/LoggingIoTHighFrequencyDataOffChain/commit/473e745425790a6e0b54e643e7873589cdf63f56
https://github.com/jcarolinares/gmail_massive_email_sender-/commit/5f8b38ea2efb1250976dcabcd22d40d7beb2d4f5
https://github.com/theQRL/QRL/commit/5d86a3bdaf348dce07d17fce915711455ebf0004

## Team Code Repos
* https://github.com/jomarip/roshambo-contracts/tree/master
* https://github.com/jomarip/roshambo-backend
* https://github.com/jomarip/roshambo-players
* https://github.com/jomarip/roshambo

## Team LinkedIn Profiles
* https://www.linkedin.com/in/jomari/
* https://www.linkedin.com/in/whitneygriffith/

## Development Roadmap
### Milestone 1 - Gaming and IPFS NFT Standard

**Time estimate:** 4 weeks

**Budget:** $5,500 (65% in USD or stable coins, 35% in DOTs)

**Deliverable:** installation packages for Substrate IDE (Mac OS).

**Specifications:**
Outside of the use of collectibles,  NFTs can be multifaceted tools. We want to implement a methodology for creating additional permissions and functionality around NFTs. Specifically, a modifier to NFTs that allow users to maintain ownership of the collectible but auction off the pointer that represents the NFTs visualization. This type of functionality is important for laying the foundation of consistent interoperability between different mediums. 
We at Finite Games have a long term interest in the use of Generative Adversarial Networks (GANs) to modify assets in one game to be normalized and properly adapted for utilization in other games. To achieve this, it is necessary to be able to build out NFTs with modifiable parameters and permissions relative to how they are processed under various conditions. These would leverage the creation/leveraging of a potential pallet for whitelist creation associated with the NFTs that provides certain permissions. These are executed with a multisig and must be confirmed by the owner of the asset. 
Minimum Expected Pallet Functionality: NFT, Multisig, WhiteList

Build Gaming Focused IPFS NFT Implementation with the following functionality:

 - NFTs are Parameterized
    - Modifiable Attributes (durability, size, location, etc)
    - Pointer (Digital Asset Visualization)
    - Version control
    - Layers
    - Permissions
  - IPFS Storage and Verification Protocol
    - Verify file parameters meet NFT speficiations
    - Update/Modify Files based on NFT permissions
    - Return a proof/verification to parachain/parathread
  - Documentation for each component and parameter

**Notice** Milestone 1 is only an alpha-stage release and not intended for production use without verification following build out in application settings.

### Milestone 2 - RoShamBo Proof of Concept of Hypercasual Esports Gaming Functionality as a Progressive Web App

**Time estimate:** 4 weeks

**Budget:** $8500 (65% in USD or stable coins, 35% in DOTs)

**Deliverable:** Progressive Web App of RoShamBo for Tutorial and Demonstration Purposes

**Specifications:**

Our first demonstration of these core concepts are with RoShamBo: Rock Paper Scissors Elite. This will be implemented asa Progressive Web3 Application (PW3A) for Chrome and Brave Browser. This will not only provide a demonstration platform, but a reproducible means of creating PW3As. Within the minimum viable demonstration of the NFT milestone 1, in each generation, only X digital collectible cards will be created for rocks, papers and scissors. Card durability is consumed during matches, and an overall counter is provided to keep track of the dwindling supply. A leaderboard is provided for the number of stars players have accumulated. Stars are also tradeable between users after playing sufficient matches. Tournaments can be created ad hoc, but they are a subset of the existing resources. With the completion of milestone 3, the in-game assets will be reskinnable/brandable assets that the users can set up for auction with sponsors. Sponsors will be able to filter by player records and games played per day and other relevant statistics of players to determine impact metrics. This piece of work would leverage a number of pallets to complete the ecosystem of functionality. This will share a parathread/parachain with the marketplace from Milestone3.

- Create/Register/Login Users
  - Login with email
  - Login w/ Private Key
  - Generate and Encrypt keypair to localstorage
- Account Management
  - Send or Receive 
  - View account balance
  - View account transaction history
  - Transfer Assets
  - Purchase Assets from Smart Contract
  - Sign transactions
- Gameplay
  - Matchmaking
  - Initiate Game
  - Join Game
  - Render NFTs based on wallet and IPFS related parameters
  - Select NFTs 
  - Save NFT Formation
  - Use NFTs in Game
  - Update in-game statistics
  - Update NFTs based on gameplay
- Documentation for each component and parameter

**Notice** Milestone 2 is potentially only an alpha-stage release and not intended for production use without verification following build out of the marketplace as an application settings.

### Milestone 3 - Marketplace for Customizable in-Game Assets
**Time estimate:** 4 weeks

**Budget:** $8500 (20% in USD or stable coins, 80% in DOTs)

**Deliverable:** Marketplace for Customizable NFTs

**Specifications:**
It is well known that a major trend in gaming is to provide players in-game skins for their characters and other in-game items to set their characters apart. These skins are often coveted and part of the branding for players. With the ability to separate ownership and digital visualization, we can create a marketplace where players can be directly sponsored through their in-game assets. In addition, we would create a separate tool to support the modification of those in-game assets would be needed. This means whether it is the reskinning of their characters or other assets they have, it would be a means for amateur esports players to also participate in the market. Another beneficiary market of this foundational technology would be digital art. The type of art and manipulation possible could substantially change with the ability to further augment and brand existing pieces. Overall, this type of platform would increase accessibility and support the transition of amateurs to pro status. Implementing this may necessitate the creation/utilization of an Orderbook pallet that interacts with the NFTs. Upon fulfillment of orders, the purchaser will be added to the whitelist of the NFT for the ability to modify the assets. 

- Owners of NFTs
  - Add NFTs to Orderbook
  - Remove NFTs from Market
  - Set Price and Conditions
  - Event listener for notification of purchases
- Sponsors/Buyers
  - Submit Bid/Fee and Agreement to Terms/Conditions 
  - Submit NFT Pointer for Approval
  - Verify Image/File Meets Parameters (IPFS)
  - Event Listener for Notification of Approval Signatures
- Orderbook/History
  - Get List and Info of Items
  - Get time assets were listed
  - Get list and info for sold items
 - Documentation for each component and utilization


**Notice** Milestone 3 is potentially only an alpha-stage release and intended for testing with Milestone #2


### Long term plan
The establishment of these frameworks and implementations create the groundwork for the development and extension of novel NFT based digital assets into mobile and web gaming. Following this, Finite Games will extend the capabilities into a commercial ready product and market place. A focus will be on onboarding people to use the MVP of RoShamBo and smaller potential sponsors to determine the best ways to scale the foundational technologies. Finite Games will also begin to support gaming studios in leveraging the existing assets to build new games across web platforms and as native applications. The goal will be a robust digital art and in-game asset marketplace. 

## Future Plans
Use General Adversarial Networks (GANs) or some other machine learning framework to create multi-attribute digital assets that can be easily moved from one game ecosystem to another and be normalized

## Additional Information
Finite Games is a growing team and we tap into a number of resources to execute and audit our work. We were winners in the SF Blockchain Week Gaming Hackathon and had some of the initial frontend work already funded. We have not applied for any other grants and have not seen any similar projects. The closest may be async art which launched recently and uses a layer approach to NFTs.
