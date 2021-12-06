# Metamask Approval Hygiene

## With the latest Badger exploit let's talk about Metamask approval hygiene

### 1. Know what you are approving

>#### Check the approved address yourself. <br/> Do not trust the site's UI. Take the address manually from the metamask data and look at the contract on [Etherscan](https://etherscan.io). <br /> If you are on another network you may want to use [Polygonscan](https//polygonscan.com), [BSCscan](https://bscscan.com), [Solscan](https://solscan.io) or the blockexplorer for your network.
>![image](https://user-images.githubusercontent.com/17516174/144847760-ed8e1951-e448-427c-a774-a4976d63a793.png)
>![image](https://user-images.githubusercontent.com/17516174/144847777-a36ea991-009c-4805-9995-533c4d49f444.png)
>#### Things to pay attention to at this point.
>- Is the contract brand new?
>- Who deployed it?
>- Where did the funds come from to the deployer
>- Is it a proxy? 

### 2. Know how much you are approving
>#### Never approved more than you plan to use. <br/> You can always approve more in the future.
>![image](https://user-images.githubusercontent.com/17516174/144848997-d4e1589c-e9f7-4a45-8b87-73d5d030ca01.png)<br/>
>#### Yes, it costs a few $ more, but so is psychological help once you will get rugged.<br/>
>![image](https://user-images.githubusercontent.com/17516174/144849106-31491371-bbbc-48f4-8de0-0495c2b150ef.png)

### 3. Approvals are per token
>#### So if you approved WETH on some shady contract only your WETH is at risk due to that approval, none of your other tokens.

### 4. Be extra tight with your approvals on proxies
>#### You are not only approving the current implementation, you are also approving the next implementation, and the next implementation, and the next implementation... <br/> This means that if the code is changed, your approval will still be valid, you need to be really careful here.

### 5. Periodic review of all your approvals
>#### Go over each approval and verify if it makes sense. If not, revoke it.<br/> If there is a lot of stuff you are unsure about, see what is less of a hassle, revoking all the odd approvals or migrating all tokens to a fresh address. <br/> You can use [Etherscan's](https://etherscan.io/tokenapprovalchecker), [Polygonscan's](https://polygonscan.com/tokenapprovalchecker) or [BSCscan's](https://bscscan.com/tokenapprovalchecker) token approval checker, at the time of writing, there is no equivalent service for Solana. <br/> There is no need to revoke tokens you don't hold anymore and don't plan to use in the future.

### 6. You should have a good reason for doing an infinite approval
>#### *It should not be your default!* <br/><br/> Not sure what an infinite approval looks like? <br/> It looks like this:
>![image](https://user-images.githubusercontent.com/17516174/144851213-e3f9c554-eb3c-42d2-bba8-1d1ec620ef8b.png)

<br/><br/>

## Stay safe out there apes.
#### Created by [0xPUFLER](https://twitter.com/0xPUFLER) (0xAFFE6a78BD3F014Da114C327a48BBEC8CbcFbF3F)
#### Taken from https://twitter.com/CryptoCatVC/status/1466380960648380419?s=20

