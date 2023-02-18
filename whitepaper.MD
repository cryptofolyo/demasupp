
NIP-58
======

Matching demand with supply
---------

`draft` `optional` `author:cryptofolyo`

Algorithms can increase the utilisation of existing assets, inventories, service providers etc by increasing the discovery mechanisms to meet demand with supply. If hyper local demand can be met with hyperlocal supply lot of unnecessary fossil fuel consumption can be reduced and we can move towards a greener earth. We can define a protocol named NIP-58 or demasupp protocol which will work on specialised NOSTR client apps adhering to this protocol which can be used by centralised like amazon or by decentralised platforms like NOSTR clients to post and search for the nearby demand of products and services offered and match them with the nearby supply of the same . This will allow hyper local connection between previously undiscovered buyers connecting them to the sellers nearby. For products like content, videos etc the demand can be met globally by the highest quality content in the relevant domain whereas for items like fresh milk, and wheat etc the demand can be met with supply nearby hyperlocally.
The protocol should also be capable of rating the buyers ,sellers, transporters and dealmakers and allow users of the protocol to see the volumes handled by the buyer, seller, transporter etc. It will also enable smooth payments and refunds to be transacted easily between the buyer and seller as previously agreed upon before the deal is accepted by the buyer,seller,transporter. Specialised NOSTR Clients with specialised UI can be used to enter these demands and the properties or attributes and the entry is broadcasted to the relevant relays to reach out to the network of users. NOSTR clients complying with NIP-58 or demasupp protocol will have functions to search and display the nearest BUYERS and SELLERS. The commerce and profits happening in real world should also incentivise the DEALMAKERS to help the SELLERS setup their accounts and train them in how to sell using the protocol and also increase awareness among public on how to buy cheaper and faster locally as well as globally by having access to previously unknown nearby SELLERS. DEALMAKERS may also bear the cost of setting up NOSTR relays exclusive for a city etc as needed to maintain the network. DEALMAKERS will be incentivised to do the marketing and increase the awareness and adoption of the protocol across the world. 

Please note that as the author is not a programmer and this is the first NIP posted by the author there may be limitations in the formats etc.

# DEFINITIONS

### 1. ORIGIN ACCOUNT 
The origin account can be a multisig account controlled by a DAO with the original participants in developing and building the protocol and the first client app implementing the protocol. ( The DAO Model can be adopted from bisq.network with a similar colored coin implementation to fund the DAO )
### 2. BUYER 
The buyer can be a person or organisation wanting to buy a product like fresh milk or wheat or wanting to avail a service like fixing a leak in the wash basin or to avail the service of a teacher to teach how to code in HTML
### 3. SELLER
The seller can be a person or organisation wanting to sell a product like fresh milk or wheat or a service provider having resource to fix a leak in the wash basin or a service provider like someone or a Educational institute who can teach how to code in HTML 
### 4. RATING
The BUYER, the SELLER, the TRANSPORTER, the DEALMAKER etc will be rated 1 out of 5 after each transaction on the platform. There will be overall rating for the BUYER and SELLER and also individual rating for the individual product or services offered by the SELLER rated by the BUYER. There can be a rating given for time keeping for each deals. 
### 5. VOLUME
Volume is the total amount transacted during the lifetime by the BUYER or the SELLER. There will be a track of the total lifetime volume of individual products and services offered by the SELLER
### 6. TRANSPORTER 
A transporter can be a person with a bike or car or truck as required by the seller to transport the product or service provider to the BUYERs GPS location. In a not so distant future the TRANSPORTER can be a self recharging drone connected to the demasap network taking orders automated way.
### 7, DEAL 
Each transaction between the BUYER, SELLER and TRANSPORTER is a DEAL - For a transaction to happen the BUYER, SELLER and the TRANSPORTER have to accept the proposed DEAL
### 8. CURRENCY
SATOSHI with lightning network implementation can be a currency of choice. Alternatively for SELLERs who are not comfortable with the volatility of SATOSHI alternatives like AMPLEFORTH SPOT can be explored as inflation resistant stable currency. 
### 9. DEALMAKER
A DEAL can be automatically proposed by an algorithm matching relevant BUYER , SELLER and nearby TRANSPORTER or by an automated algorithm. It can also be proposed manually by a DEALMAKER who scrolls through different feeds of demands and supplies broadcasted in compliance with the DEMASUPP protocol. The DEALMAKER can then propose a deal matching BUYER & SELLER and connecting them with a TRANSPORTER if home delivery is required. DEAL MAKER also handle the ESCROW between the BUYER and SELLER to enable a smooth transaction. The DEALMAKER is also engaged in adding new SELLERS and training them, raising awareness amongst the buyers etc. 
A DEALMAKER can be added only by another DEALMAKER as a Child Account. The first few dealmakers will be added by the ORIGIN ACCOUNt. All DEALMAKERS are invited into the system by other DEALMAKERS. As ESCROWING is a major responsibility the rating of the PARENT DEALMAKER can go down if the CHILD DEALMAKER rating goes down below critical levels.

### Sample scenarios

### Scenario 1 - How we can reach out to people without smartphones where most of the commerce happens

In todays world people living in apartment complexes may need to buy fresh milk but are forced to buy packed milk. What if a person living in an apartment complex can post his need to buy fresh milk, organic vegetables etc and a person living nearby having a cow can supply him with it, another person having a small organic farm nearby. And there is a transporter with a bicycle can carry the milk to the apartment. Suppose both the farmers and the cyclist does not have even a smartphone.
The top 1% of the society may have access to internet, youtube, and contents and be aware about platforms like NOSTR whereas the person having the cow may not even have a smartphone but he can be eventually trained on how to sell by broadcasting to networks like NOSTR using demasupp protocol by incentivising the training by DEALMAKERS. In case of non availability of smartphone a bitcoin paper wallet may be used by the SELLER as trained by the DEALMAKER. The DEALMAKER can help the SELLER convert the paper wallet proceeds from the Sales to FIAT any time as demanded by the SELLER. FIAT conversion also can be listed as a service provided on this platform. This means that with the help of the DEALMAKERS almost anyone can participate in the ecosystem. This will also lead to widespread adoption of bitcoin.

### Scenario 2 - Content monetisation

Highest quality online content about a particular domain from the highest quality teacher who can teach with excellence, can be sold by SELLERS across the world without any barriers. For example a DEALMAKER in AFRICA may want to learn how to set up his own NOSTR client and relays for his city. An expert in NOSTR can create an online video and become a SELLER on the network. People need not waste their time on less than average quality content and spend their time in a better way and learning collectively as humanity in a faster way.
The demasupp protocol will enable the discovery of all the local demand and match it with the hyperlocal as well as the global supply. For online contents videos etc the rating and popularity and volume can be far higher for the best quality content. it can be served across the world without barriers of payment. A competing content in the similar topic may be gaining fast popularity and volumes. These can be easily captured from the demasupp apps by searching with the related keywords like "Build NOSTR Client" etc

### How the deals will happen on demasupp network?

The BUYER using the demasupp specialised NOSTR client app will make a post on the client app with the specialised User interface to enter data in a granular way. 


        For Example the BUYER post will carry the data as JSON or some suitable format.


        Item needed                     = Fresh Milk
        QTY                             = 500
        Unit                            = ml
        Need expires within             = 60 minutes
        My GEO Location                 = 48.856613 LATITUDE 2.352222 LONGITUDE
        Description                     = Fresh milk ( Cow ) 500 ml needed. 
        Transport Required              = Yes
        Return policy                   = Product can be returned within 24 hours for a refund. No refund for transportation
        Online Product                  = NO


The Buyer once he broadcast his demand he can see all the nearby available SELLERS who have already braodcasted to the network that they are selling that particular item in that geographic area and also the nearby transport available. BUYER can check in physically to the SELLER if transport is not available. The client app will have fields to enter all these details and the app will post to NOSTR as a structured JSON or some suitable format so that other apps following DEMASUPP protocol will be able to list out the nearby demands to a SELLER or a DEALMAKER

The BUYER can choose the SELLER and TRANSPORTER and make the payment in Satoshi or ampleforth Spot or any other crypto to complete the deal. The DEAL amount goes to the Account of DEALMAKER (preferably multisig by the BUYER and the DEALMAKER) and is held as escrow similar to localbitcoin model or the Bisq.network model. Once the deal is completed and the milk is delivered by the TRANSPORTER to the BUYER the BUYER has to accept the item or return the item to the TRANSPORTER. If accepted by the BUYER and on clicking accept the transaction is settled to the SELLER and the TRANSPORTER from the ESCROW account. 


        The TRANSPORTER having a bike can use the app to mark his availability in the following way

        Vehicle                 = Bicycle
        Average Speed           = 5 mph
        My Geo Location         = 48.856625 LATITUDE 2.352234 LONGITUDE
        Available now           = Yes
        Availability expires    = 360 minutes
        Maximum distance        = 3 miles
        Maxumum weight          = 20 kg
        Rate                    = 500 SATOSHI per mile per kilo
        Currency Accepted       = SATOSHI, AMPLEFORTH SPOT
        
This means that TRANSPORTER is having a bicycle and he or she is available for the next 360 minutes to take any DEALS and is willing to transport upto 20 kg to a maximum distance of 3 miles.


        The SELLER post will look something like this
        
        Item available               = Fresh Milk
        QTY                          = 500
        Unit                         = ml
        Rate                         = 2000 SATOSHI
        Stock                        = 15
        Availability till            = Always available
        My GEO Location              = 48.856643 LATITUDE 2.352223 LONGITUDE
        Description                  = Fresh milk ( Cow ) 500 ml - Farmer = John Doe 
        Refund Policy                = Full refund except the transportation cost within 6 hours of delivery.


The DEALMAKERs or the SELLERs themselves can use the app to explore the nearby recent demands matching the items or services provided by the SELLER using the app.

For example in the app an alert will come to all the SELLERS of FRESH MILK nearby when a demand is broadcasted to the network. Similarly if the SELLER or DEALMAKER propose a deal for the buyer the alert will go to the buyer with the deal value and the buyer can know the estimated time and click on accept.

Similarly the platform can also be used to find out service providers like plumber if there is a leak in the wash basin and you want the plumbers service at your home. The timeslot can be defined earlier and the rating may go down if the time is not kept. The average delay in keeping the time may be published for the service providers. This may even be used for locum jobs etc.


### Currency adoption
Satoshi may be the first currency of choice for the demasupp network. 
But for some farmers, merchants common people etc who are not comfortable and have a psychological barrier related to the volatility of Satoshi their adoption may lag behind if Satoshi is the only choice. They may be given other options like USDT, AMPLEFORTH SPOT etc where SPOT can mitgate inflation as well as provide the stability of Dollar. AMPLEFORTH SPOT as of now is trading at 1.14 which is the value of 1 USD in 2019. The inflation mitigation coupled with price stability offered by  SPOT may be a very welcome feature in countries with high inflation running above 2 digits. 

### Ratings
Ratings provided by the seller to the buyer and transporter etc for keeping the commited time and quality of product etc is a crucial component. SELLERS and BUYERS joining early on to the demasupp network will be hugely incentivised. The Transporters will be rated based on delays in delivery etc. The DEALMAKERS will be rated by BUYERS and SELLERS and transporters after each DEAL. BUYERS can set their app to connect only to SELLERS having a minimum rating defined by the BUYER. DEALMAKERS falling below critical rating will be made inactive and the SELLER accounts connected to this DEALMAKER will be moved to the PARENT DEALMAKER accounts. SELLERS can set their filter to deal with only BUYERS having a minimum set rating. This will enable competition amongst newcomers for rating and also provide more business and the business with better ratings can sell on premium. 

### DEALMAKER incentivisation

The DEALMAKER is the most important part of the entire ecosystem that will be built upon implementing the DEMASUPP Protocol. A DEAL can be automatically proposed by an algorithm matching relevant BUYER , SELLER and nearby TRANSPORTER or by an automated algorithm. It can also be proposed manually by a DEALMAKER who scrolls through different feeds of demands and supplies broadcasted in compliance with the DEMASUPP protocol. The DEALMAKER can then propose a deal matching BUYER & SELLER and connecting them with a TRANSPORTER if home delivery is required. Each transaction between the BUYER and SELLER goes into an DEALMAKERS ESCROW account to be released from the ESCROW account to the SELLER account once the BUYER accept the product or service delivered ( inspired from the localbitcoins and BISQ model.

Anybody who is the early mover into the protocol and understands the importance of the protocol can decide to become an DEALMAKER for any local region. The DEALMAKERS will help the local shopkeepers or global online sellers to setup the SELLER accounts and teach them how to sell by broadcasting to the platform. Via the sellers stores and online forums awareness generation can be done amongst the buyers as well. DEALMAKERS are the ones who will spend part of their incentives to popularise the system and thereby gaining more incentives.

The DEALMAKERS also may suffer loss in settling the differences if a deal goes bad between the buyer and the seller The dealmaker will have to settle the deal in such a way that the buyer and seller is happy and the DEALMAKER is not rated down. This is the risk the DEALMAKERS are taking. The BUYER as well as SELLER will be rating the DEALMAKER after each DEAL. The DEALMAKER account will be disabled if the rating goes below a critical Level. The rating of the parent DEALMAKER also will be taking a HIT in case if a Child DEALMAKER account goes below the critical rating.

The DEALMAKERS can set a percentage for each of the transactions routed via the DEALMAKER with a minimum of 0.1% of each transaction happening via the SELLERS added by the DEALMAKER. A healthy competition between DEALMAKERS will help the percentage stay nearby the minimum levels. Each SELLER account needs to be connected to at least 1 DEALMAKER account to start Selling. The first DEALMAKER account is to be connected to an ORIGIN Account. And the subsequent DEALMAKER accounts can be generated only by an existing DEALMAKER account. Each Parent DEALMAKER account will be eligible for 5% of the total incentives flowing into any other Child DEALMAKER accounts connected to the Parent DEALMAKER account. This will help the creation of an invite only DEALMAKER network and will make enough funds available for awareness generation. And the incentives start coming to the DEALMAKERs only when commerce start happening via the SELLERS and BUYERS

### What happens in bad deals, product return etc 

The SELLER as per the initial DEAL agreement has to refund the transaction in case of returns. The terms of refund are already laid out in the deal itself and read by the BUYER before accepting the deal. Some deals may not have a refund policy like that of online content delivery. If there is a difference of opinion between the BUYER and the SELLER the DEALMAKER can mediate the DEAL and based on Mutual agreement arrive at a settlement. If there is a mediation then the mediation is rated by both the BUYER and SELLER, The DEALMAKER rating will be transparent to both BUYERS and SELLERs. 


### Reference websites and links
1. Localbitcoins.com - Inspiration for escrow model between buyer and seller
2. bisq.network - Inspiration of the BSQ colored coin based DAO 
3. ampleforth.org - Inspiration for the inflation resistant elastic stable coin that grows in wallet based on demand and defends the cantillon effect.
4. spot.cash - The inflation resistant stable coin which can easily gain user adoption as it is closer to fiat but mitigates inflation
5. bit.ly/ifsatoshi - Article written by me couple of months back

## Notes:
This document is just a rough draft which requires a lot of improvements
Inviting comments to improve upon the idea
