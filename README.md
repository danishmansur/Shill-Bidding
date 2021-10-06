# Shill-Bidding

Shill bidding in auctions is the practice of placing bids on behalf of the seller with a motive to drive up 
the price of the auctioned item. In auctions of luxury items like art and antiques where the bidders’ 
valuations differ, and the payoffs sellers’ get from fraud; Shill bidding is said to have occurred. We 
though our project wants to check the features and the extent to which they contribute to Shill Bidding. 
This project aims to help companies like eBay to predict which Bidders are taking part in this fraud called
Shill Bidding.

Data Description:
We have the following attributes in our dataset:
1. Record ID: This is a unique identifier for records in the dataset.
2. Auction ID: This is a unique identifier of auctions.
3. Bidder ID: This is a unique identifier of bidders.
4. Bidder Tendency: A shill bidder participates exclusively in auctions of few sellers rather than a 
diversified lot. This is a collusive act involving the fraudulent seller and an accomplice.
5. Bidding Ratio: A shill bidder participates more frequently to raise the auction price and attract 
higher bids from legitimate participants.
6. Successive Outbidding: A shill bidder successively outbids himself even though he is the 
current winner to increase the price gradually with small consecutive increments.
7. Last Bidding: A shill bidder becomes inactive at the last stage of the auction (more than 90\% 
of the auction duration) to avoid winning the auction.
8. Auction Bids: Auctions with SB activities tend to have a much higher number of bids than the 
average of bids in concurrent auctions.
9. Auction Starting Price: a shill bidder usually offers a small starting price to attract legitimate 
bidders into the auction.
10. Early Bidding: A shill bidder tends to bid pretty early in the auction (less than 25\% of the 
auction duration) to get the attention of auction users.
11. Winning Ratio: A shill bidder competes in many auctions but hardly wins any auctions.
12. Auction Duration: How long an auction lasted
13. Class: 0 for normal behavior bidding; 1 for otherwise. This is our Target Attribute.
