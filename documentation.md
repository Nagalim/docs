<div class="welcome-card">
  <div class="title">Welcome to</div>
  <img src="img/welcome.svg" width="458">
  <div class="call-to-action">Feel free to navigate throught any section of interest, or start by clicking in our most visited sections bellow.</div>

  <div class="call-to-action-links">
    <a href="#" class="link">What is Peercoin?</a>
    <a href="#" class="link">PoS vs PoW</a>
    <a href="#" class="link">Minting vs Mining</a>
  </div>
</div>

----

# Introduction to Peercoin

Hello, and welcome to the Peercoin Documentation website. We hope to help you understand more about this coin, its philosopy and technologies that runs behind it. Before getting too technical, we invite you to dive a little bit into the history of Peercoin, leraning why it was created, and the purposes behind it.

## Peercoin Genesis: 2012

Since the creation of Bitcoin (Nakamoto 2008), proof-of-work has been the predominant design of peer-to-peer crypto currency. The concept of proof-of-work has been the backbone of minting and security model of Nakamoto’s design.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec a tellus pellentesque, varius risus at, mattis erat. Duis tincidunt nulla quis odio dapibus tempor. Nunc egestas dictum orci vitae fringilla. Ut dictum ac sapien vel iaculis. Duis varius libero vitae fringilla vulputate. Donec posuere vel risus nec cursus. Integer in lectus ut tellus vehicula ultricies vel vel elit. Morbi mattis eleifend tellus eget tempus. Duis tristique et justo ut gravida. Vivamus maximus commodo consequat. Donec faucibus erat a scelerisque eleifend. Vestibulum pretium nunc vel consequat sollicitudin. Cras tortor nulla, semper a sapien ut, aliquam congue nisi. Nullam id suscipit urna, a maximus velit.

Etiam egestas a mi a maximus. Phasellus sed dictum tortor, in sodales nulla. Vestibulum ut nisi volutpat, dictum orci vitae, rutrum augue. Praesent convallis urna dui. Vestibulum auctor leo eget dui semper hendrerit. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. In sed sapien varius ante volutpat mattis.

Sed nisi neque, porta varius tristique eget, viverra sed magna. Donec venenatis nulla augue, quis dignissim neque hendrerit vel. Aliquam vitae mi nisl. Donec ut varius lectus. Curabitur euismod, metus ut vulputate sollicitudin, velit leo elementum est, eget accumsan ligula metus quis justo. Nullam et gravida sapien. Ut nec arcu id lorem sagittis eleifend. Phasellus est sapien, finibus nec viverra id, elementum quis augue. Vivamus sapien magna, iaculis id sem eu, porttitor sodales nulla.

Fusce nec facilisis quam, sit amet venenatis erat. Donec dapibus nulla quis mi ultrices, nec gravida ipsum hendrerit. Curabitur vel tincidunt augue. Nullam nec sagittis tellus, et commodo erat. Aliquam quis vulputate ante, eget viverra mi. Cras nec tortor scelerisque, facilisis eros eget, mollis libero. Sed at risus a orci aliquam gravida. Pellentesque scelerisque scelerisque cursus. Nam egestas lacus pulvinar ex ultricies mattis non in lacus. Interdum et malesuada fames ac ante ipsum primis in faucibus. Quisque leo dolor, scelerisque id faucibus pellentesque, tempor vel dolor. Quisque laoreet hendrerit turpis, ut interdum quam varius non. Phasellus consectetur turpis at suscipit semper. Maecenas ante dui, sollicitudin et auctor et, rutrum quis eros. Maecenas mattis, risus non imperdiet euismod, odio sem cursus magna, nec feugiat metus erat eget nisi.

# Comparison with other blockchain networks

Peercoin is best compared with it's sibling - Bitcoin; however in the following table we'll show how it bodes against something vastly different like Ethereum. Peercoin was invented as response to increasing doubts on Bitcoin's PoW consensus model with regards to it's increasing centralization and conflict of interests between miners. Peercoin can be understood as Proof-of-Stake clone of the Bitcoin but that is an oversimplification as Peercoin differs vastly - especially when it comes to economics and incentives of the system.
Major differences between the two are the fee market, ie. the absence of it in Peercoin and Peercoin's dedication to continual token distribution via PoW block rewards while the Bitcoin's distribution rate (also PoW block rewards) is reduced geometrically every four years until it becomes zero.


### Consensus algorithm

### Distribution


### Fee market

Fee market provides a mechanism to decide which transaction has priority over the others. Transaction fee is claimed by the block miner in both Bitcoin and Ethereum economic systems so the miners have incentive to include the transaction in the block they mine. If Alice wants her transaction to be included in the next block, she should set transaction fee higher and pay more then other network users, ie. outbid them. It is presumed that miners, as rational subjects, will first include transactions which carry the most Bitcoin value. If Alice pays transaction with fee which is under the average fee at the time she might wait for several blocks (or hundreds of blocks) to see her transaction included and confirmed. So, it is obvious that fee market serves as the incentive for miners to process and include the transactions in the mined block as well.
With Bitcoin block size limit is set to 1MB to keep the upward pressure on the price of the transaction fees and incentivize miners to validate the transactions. This is especially important as Bitcoin economy is expected to run on transaction fees alone when the block subsidies eventually stop.

Peercoin fees are fixed at 0.01 PPC per kb and are burned, which is equivalent to paying the transaction fee to each Peercoin holder in proportion to their Peercoin holdings as fee is deducted from the total supply of Peercoins. This property eliminates the need for fee market on Peercoin network and allows every transaction to get included in the very next block. Peercoin retains the 1MB block size limit as it is based on the Bitcoin code, but it has no intricate need to keep it. Block size limit will definitely be increased as Peercoin network grows in usage. Peercoin developers have already hinted that Peercoin will feature dynamic block size in near future.
Due to this economic properties of Peercoin a question arises: why do Peercoin miners even bother processing the transactions?

For spectator looking at this from Bitcoin perspective answer is that Peercoin block miners want to process transactions so they allow Peercoins to be burned - thus making their own stake in the network more valuable.
However when intricacies of PoS are learned it is understood that with Peercoin minters (PoS miners) include transactions because it doesn't cost much to include them, while producing empty blocks reduces the value of the blockchain, and therefore of their stake. The burned fees are not really an argument as the effect on their holdings is negligible.
Bitcoin miners always start off mining an empty block, otherwise they lose the time it takes to validate the transactions and signatures, as time is money on the Bitcoin network. Only after they validated the txns to include and computed the merkle root, they start mining blocks with txns.
while for PoS, the time advantage is negligible. as you can still use the stake hash of a few seconds ago. (hrobeers, 30.08.2017)


### Block size limit and block time spacing

Bitcoin features the 1MB block size limits which serves to place the upward pressure on the transaction fee price, Peercoin copies this parameter from the Bitcoin but it's economic model does not depend on scarcity of the block space.
Bitcoin and Peercoin generate a block every 10 minutes while Ethereum generates a block every 12 seconds. Considering this and the block size limit of 1MB, Bitcoin and Peercoin have a transaction per second (TPS) of about seven tps and Ethereum of about 25 tps.

<table>
<thead>
<tr>
<th>Features</th>
<th>Bitcoin</th>
<th>Peercoin</th>
<th>Ethereum</th>
</tr>
</thead>
<tbody>
<tr>
<td>Main use-case:</td>
<td>p2p financial transactions / store of value</td>
<td>p2p financial transactions / store of value</td>
<td>Turing complete smart contracts</td>
</tr>
<tr>
<td>Consensus algorithm:</td>
<td>PoW</td>
<td>PoS</td>
<td>PoW</td>
</tr>
<tr>
<td>Active since:</td>
<td>2009</td>
<td>2012</td>
<td>2015</td>
</tr>
</tr>
<tr>
<td>Distribution method:</td>
<td>PoW block reward</td>
<td>PoW block reward / PoS block reward</td>
<td>Initial Coin Offering / PoW block reward</td>
</tr>
<tr>
<td>Distribution:</td>
<td>Limited, until 21M tokens exist in the system.</td>
<td>Unlimited.</td>
<td>Unlimited.</td>
</tr>
</tr>
<tr>
<td>Transaction fee:</td>
<td>Fee market (~390 satoshis/byte)</td>
<td>Static 0.01 PPC/kb (~0.2 Btc satoshis/byte)</td>
<td>Fee market (~23 Gwei/byte)</td>
</tr>
<tr>
<td>Estimated transaction bandwidth:</td>
<td>7 tx/sec</td>
<td>7 tx/sec</td>
<td>25 tx/sec</td>
</tr>
<tr>
<td>Block time:</td>
<td>10 minutes</td>
<td>10 minutes</td>
<td>12 seconds</td>
</tr>
<tr>
<td>Block size:</td>
<td>1MB</td>
<td>1MB</td>
<td>Dynamic</td>
</tr>
<tr>
<td>Extra transaction data size limit:</td>
<td>80 Byte<br />(OP_RETURN)</td>
<td>80 Byte<br />(OP_RETURN)</td>
<td>Dynamic<br />(5 gas / byte)</td>
</tr>
<tr>
<td>Topology:</td>
<td>Public blockchain</td>
<td>Public blockchain</td>
<td>Public blockchain</td>
</tr>
</tbody>
</table>
Table 1. Comparison of Crypto currency attributes
(prices of transactions at the time of writing)
