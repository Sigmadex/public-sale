<img src="https://user-images.githubusercontent.com/33762147/155625647-55c69f06-e0ea-44a8-a425-7aa086c329c5.png" style="border-radius:50%;width:72px;">

# Fair Launch & Community Sale (Price Discovery Event)

## Summary
<em>Sigmadex is proposing a community driven token sale event for accurate price discovery. This concept utilizes Sigma Curves for price determination, liquidity and vesting while giving an opportunity for the public to obtain the same valuation tiers as all earlier investors. This is all accomplished through game theory economics.</em>

## Motivation

Many projects use the same mundane public sale models which involve arbitrary parameters resulting in erroneous price discovery and economic imbalance.

|Outcome|Interpretation|
|-------|--------------|
|The auction doesn't sell out | Price is overvalued |
|**The auction successfully sells out** | Price is accurate or undervalued |

By using a Sigma Curve, we add the most liquidity at the highest price, making it intentionally harder to fill the public auction. This ensures the price discovery is accurate relative to demand as we already know there will be demand at the earlier rounds. If the end price is set too high and not within reason, it will struggle to reach its target for a complete sell-out and be apparent that the pricing parameters are out of balance. Negative pressure on launch can be expected if the sale does not fill-out completely.

Choosing the proper initial variables should be decided systematically and is critical for a healthy launch. We propose using the community for feedback on determining the best parameters for the sale as being greedy and setting a high end value will cause 2 risks:

* Risk of not selling out the allocation
* Cause an immediate stunt in price appreciation post launch

### Variables 
<div align="center"> 
  
<div class="row">
    
|axis|desc|
|---|----|
|*x*|liquidity|
|*y*|price|
 
  </div>
</div>
 
### Proposed Parameters
<div align="center"> 
  
|var|value|
|---|-----|
|x-min|500,000|
|x-max|10,000,000|
|y-min|0.0135|
|y-max|0.125|
  
</div>
