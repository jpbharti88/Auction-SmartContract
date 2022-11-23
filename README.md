# Auction-SmartContract

This contract is for Selection of auction winner.

Step1: Contract manager deploy the contract.

Step2: manager adds Items for Auction using addItem Button. 
        input data: string _Itemname, uint price

Step3: Bidders can view Items for Sale using GetItem Button.
        (item details with item Number will be seen.)
        
step3: Bidders quote for the items they wish using doBid button.
        input data: (string _itemNumber ,uint quoteVal)

step4: Once expecter number of bidding is done. Manager executes AuctionFinalize button to run allocation logic.
    
step5: Item allocation can be viewed by using getAuctionresult button.
        input data :(string memory _itemNumber)     
