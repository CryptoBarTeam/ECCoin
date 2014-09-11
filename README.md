
ECCoin - ECC

ECCoin is an energy saving coin generating most of its coins through PoS blocks. It distributes its initial coins through 45 days evenly distributed PoW mining, no halves during the initial distribution phase, thus ensures a fair distribution. After initial distribution, the PoW block payout will be dropped to 1 coin per block. The main coin generation will be done through the PoS generations.

ECCoin also adopts a variable PoS rate with the following annual interest rate formula:
- 3% - (number of years * .1)

this rate cannot go lower than 1%.

Specifications:

- scrypt PoS/PoW
- 4 transaction confirmations
- 50 minted block confirmations

PoS:
- Variable interests
- PoS Starts after 2 hours of minimum holding

PoW: 
- 45 sec block target
- Random 100000 - 300000 coins per block for the first 45 days evenly distribution 
- After 45 days, the PoW block drops to 1 coin / block
- diff retarget each block

ports:
connection:	19118
RPC:			19119

