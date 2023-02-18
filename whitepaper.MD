# DEMASUPP
A global protocol to match and connect demand with supply
======

cryptofolyo@gmail.com dated 18th February 2022
-------------------------


### Abstract: 
A protocol which can be used by centralised like amazon or by decentralised platforms like NOSTR clients to post and search for the nearby demand of products and services offered and match them with the nearby supply of the same . This protocol will allow hyper local connection between previously undiscovered buyers connecting them to the sellers nearby. For products like content, videos etc the demand can be met globally whereas for items like fresh milk, and wheat etc the demand can be met with supply nearby. The protocol should also be capable of rating the buyers and sellers and allow users of the protocol to see the volumes handled by the buyer and seller. The protocol will also enable smooth payments and refunds to be transacted easily between the buyer and seller as previously agreed upon before the transaction. Protocol layer like NOSTR can be used to broadcast the demand and supply to the network of users. NOSTR clients complying with DEMASUPP protocol will have functions to search and display the nearest BUYERS and SELLERS. The commerce and profits happening in real world should also incentivise the DEALMAKERS to help the SELLERS setup their accounts and train them in how to sell using the protocol and also increase awareness among public on how to buy cheaper and faster by having access to previously unknown nearby SELLERS. DEALMAKERS may also bear the cost of setting up NOSTR relays exclusive for a city etc

# DEFINITIONS

### 1. ORIGIN ACCOUNT 
The origin account can be a multisig account controlled by a DAO with the original participants in developing and building the protocol and the first client app implementing the protocol. ( The DAO Model can be adopted from bisq.network with a similar colored coin implementation to fund the DAO )
### 2. BUYER 
The buyer can be a person or organisation wanting to buy a product like fresh milk or wheat or wanting to avail a service like fixing a leak in the wash basin or to avail the service of a teacher to teach how to code in HTML
### 3. SELLER
The seller can be a person or organisation wanting to sell a product like fresh milk or wheat or a service provider having resource to fix a leak in the wash basin or a service provider like someone or a Educational institute who can teach how to code in HTML 
### 4. RATING
The BUYER, the SELLER, the TRANSPORTER, the DEALMAKER etc will be rated 1 out of 5 after each transaction on the platform. There will be overall rating for the BUYER and SELLER and also individual rating for the individual product or services offered by the SELLER rated by the BUYER.
### 5. VOLUME
Volume is the total amount transacted during the lifetime by the BUYER or the SELLER. There will be a track of the total lifetime volume of individual products and services offered by the SELLER
### 6. TRANSPORTER 
A transporter can be a person with a bike or car or truck as required by the seller to transport the product or service provider to the BUYERs GPS location
### 7, DEAL 
Each transaction between the BUYER, SELLER and TRANSPORTER is a DEAL - For a transaction to happen the BUYER, SELLER and the TRANSPORTER have to accept the proposed DEAL
### 8. CURRENCY
SATOSHI with lightning network implementation can be a currency of choice. Alternatively for SELLERs who are not comfortable with the volatility of SATOSHI alternatives like AMPLEFORTH SPOT can be explored as inflation resistant stable currency.
### 9. DEALMAKER
A DEAL can be automatically proposed by an algorithm matching relevant BUYER , SELLER and nearby TRANSPORTER or by an automated algorithm. It can also be proposed manually by a DEALMAKER who scrolls through different feeds of demands and supplies broadcasted in compliance with the DEMASUPP protocol. The DEALMAKER can then propose a deal matching BUYER & SELLER and connecting them with a TRANSPORTER if home delivery is required. DEAL MAKER also handle the ESCROW between the BUYER and SELLER to enable a smooth transaction. The DEALMAKER is also engaged in adding new SELLERS and training them, raising awareness amongst the buyers etc. 


### Introduction

In todays world people living in apartment complexes may need to buy fresh milk but are forced to buy packed milk. What if a person living in an apartment complex can post his need to buy fresh milk and a person living nearby having a cow can supply him with it. And a transporter with a bicycle can carry the milk to the apartment. 
The top 1% of the society may have access to internet, youtube, and contents whereas the person having the cow may be having a smartphone and can be trained on how to sell by broadcasting to networks like NOSTR using demasupp protocol. In case of non availability of smartphone a bitcoin paper wallet may be used by the SELLER as trained by the DEALMAKER. The DEALMAKER can help the SELLER convert the proceeds from the Sales to FIAT as and when demanded by the SELLER.

High quality online content, study materials etc can be sold by SELLERS across the world without any barriers whereas local produce. Organic vegetables, freshmilk etc can be sold hyperlocally by the SELLERs to the nearby BUYERS

The demasupp protocol will enable the discovery of all the hyperlocal demand and match it with the hyperlocal supply.

### How the deals will happen ?

The BUYER using the NOSTR client app ( Built adhering to NOSTR and DEMASUPP protocols ) will make a post on the client app


        For Example the BUYER post will carry the data as JSON or some suitable format


        Item needed                     = Fresh Milk
        QTY                             = 500
        Unit                            = ml
        Need expires within             = 60 minutes
        My GEO Location                 = 48.856613 LATITUDE 2.352222 LONGITUDE
        Description                     = Fresh milk ( Cow ) 500 ml needed. 
        Transport Required              = Yes
        Return policy                   = Product can be returned within 24 hours for a refund. No refund for transportation


The Buyer once he broadcast his demand he can see all the nearby available SELLERS who meet the specific demand and he can also see if there is any transport available. BUYER can check in physically to the SELLER if transport is not available. The client app will have fields to enter all these details and the app will post to NOSTR as a structured JSON or some suitable format so that other apps following DEMASUPP protocol will be able to list out the nearby demands to a SELLER or a DEALMAKER


The BUYER can choose the SELLER and TRANSPORTER and make the payment in Satoshi or AMPL Spot etc and complete the deal. The DEAL amount goes to the Account of DEALMAKER (preferably multisig by the BUYER and the DEALMAKER) and is held as escrow similar to localbitcoin model or the Bisq.network model. Once the deal is completed and the milk is delivered by the TRANSPORTER to the BUYER the BUYER has to accept the item or return the item to the TRANSPORTER. If accepted by the BUYER and on clicking accept the transaction is settled to the SELLER and the TRANSPORTER from the ESCROW account. 


        The TRANSPORTER having a bike can use the app to mark his availability in the following way

        Vehicle                 = Bicycle
        Average Speed           = 5 mph
        My Geo Location         = 48.856625 LATITUDE 2.352234 LONGITUDE
        Available now           = Yes
        Availability expires    = 360 minutes
        Maximum distance        = 3 miles
        Maxumum weight          = 20 kg
        Rate                    = 500 SATOSHI per mile per kilo
        
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


The DEALMAKERs or the SELLERs themselves can use the app to explore the nearby recent demands matching the items or services provided by the SELLER using the app.

For example in the app an alert will come to all the SELLERS of FRESH MILK nearby when a demand is broadcasted to the network. 

Similarly the platform can also be used to find out service providers like plumber if there is a leak in the wash basin and you want the plumbers service at your home. The timeslot can be defined earlier and the rating may go down if the time is not kept. The average delay in keeping the time may be published for the service providers. This may even be used for locum jobs etc.


### What happens in bad deals, product return etc 

        The SELLER as per the initial DEAL agreement has to refund the transaction in case of returns. If there is a difference of opinion between the BUYER and the SELLER the DEALMAKER can mediate the DEAL and based on Mutual agreement arrive at a settlement. 
If there is a mediation then the mediation is rated by both the BUYER and SELLER. The DEALMAKER rating will be transparent to both BUYERS and SELLERs. 


### DEALMAKER incentivisation

The DEALMAKER is the most important part of the entire ecosystem that will be built upon implementing the DEMASUPP Protocol. A DEAL can be automatically proposed by an algorithm matching relevant BUYER , SELLER and nearby TRANSPORTER or by an automated algorithm. It can also be proposed manually by a DEALMAKER who scrolls through different feeds of demands and supplies broadcasted in compliance with the DEMASUPP protocol. The DEALMAKER can then propose a deal matching BUYER & SELLER and connecting them with a TRANSPORTER if home delivery is required. Each transaction between the buyer and seller goes into an DEALMAKERS ESCROW account to be released from the ESCROW account to the SELLER account once the BUYER accept the product or service delivered similar to the localbitcoins or BISQ model.

Anybody who is the early mover into the protocol and understands the importance of the protocol can decide to become an DEALMAKER for the local region. The DEALMAKERS will help the local shopkeepers or sellers to setup the SELLER accounts and teach them how to sell by broadcasting to the platform. Via the sellers stores and online forums awareness generation can be done amongst the buyers as well.

The DEALMAKERS also may suffer loss in settling the differences if a deal goes bad between the buyer and the seller in such a way that the buyer and seller is happy and the DEAL is not rated down. This is the risk the DEALMAKERS are taking. The BUYER as well as SELLER will be rating the DEALMAKER after each DEAL. The DEALMAKER account will be disabled if the rating goes below a critical Level. The rating of the parent DEALMAKER also will be taking a HIT in case if a Child DEALMAKER account goes below the critical rating.

The DEALMAKERS can set a percentage for each of the transactions routed via the DEALMAKER with a minimum of 0.1% of each transaction happening via the SELLERS added by the DEALMAKER. A healthy competition between DEALMAKERS will help the percentage stay nearby the minimum levels. Each SELLER account needs to be connected to at least 1 DEALMAKER account to start Selling. The first DEALMAKER account is to be connected to an ORIGIN Account. And the subsequent DEALMAKER accounts can be generated only by an existing DEALMAKER account. Each Parent DEALMAKER account will be eligible for 5% of the total incentives flowing into any other Child DEALMAKER accounts connected to the Parent DEALMAKER account. This will help the creation of an invite only DEALMAKER network and awareness generation. And the incentives start coming to the DEALMAKERs only when commerce start happening via the SELLERS and BUYERS


This document is Version 1.0 - Inviting comments to improve upon the idea - Inviting interested programmers, app designers etc to collaborate and build the first client and be part of stakeholders of the ORIGIN account.
