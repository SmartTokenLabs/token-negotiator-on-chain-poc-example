# token-negotiator-on-chain-poc-example
A proof of concept to demonstrate the use of on chain tokens in various scenarios

See:
https://tokenscript.github.io/token-negotiator-on-chain-poc-example/

### List of offers:

- Offer A: Tickets to Studio54 offered to BAYC Derivative Holders
- Offer B: Free T-shirt for Expansion Punk Holders
- Offer C: Exclusive Subscription to Vogue for BAYC Derivative + Woman tribe
- Offer D: Car Hire Discount for Riot Racers
- Offer E: Car Hire Demo for Riot Racers
- Offer F: 20% Off for your next VIP experienceto BAYC Derivative Holders
- Offer G: Free T-shirt for Zed Holders

### Activating the offers

From the Token overlay connect to the issuers then select the desired tokens. Once selecting the NFT/s the page will update with the available offers.

### Deploy to github pages

merge code to main branch

### Run locally (npm pacakge install required http-server) 

http-server 

### development

To extend the example with new offers, see:

- `offers: {}` which contains the offers and notification copy. 
- `negotiator.on("tokens-selected", (tokens) => { ... }` which triggers the offer validation when tokens are added / removed.






