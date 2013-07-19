From: John H. 
To: Ramesh J. 
Re: Thoughts on Markets-Mechanisms-as-Experimental Units 
Introduction 
Very little is know about differing matching market mechanisms. There is some empirical work comparing auction formats, but as far as I know, no true experiments comparing, say a decentralized spot market to a deferred-acceptance matching market. This is presumably the result of the empirical difficulty of experimenting at the market level---not a lack of interest in the questions mechanism comparisons raise.
Broad-Scope Research Questions
Who gets paired with whom under different mechanisms? Are matches assortative? Do spot market leads to outcomes that look like matched markets?  
What is the quality of resultant matches? 
Work quality
Completion rates 
How do wages compare across mechanisms (assuming buyers/sellers form preferences with knowledge of binding, offered wages)? One critique of centralized markets is that they suppress wages. 
Can we experimentally create unraveling? When does it happen and why? 
Does lack of strategy-proofness matter in the small?
When do spot markets not clear and why?  

Basic Experimental Infrastructure
We  would need to build a basic site with browsable profiles of buyers and sellers. Buyers and sellers would only be able to “see” profiles in their experimental unit (recall that the market will be the experimental unit). There would some way for buyers/sellers to (a) make offers (in the decentralized case) and (b) express rank-ordered preferences in the centralized cases. 
Subjects 
We would recruit participants to be buyers or sellers, who in turn would log into our site with their oDesk accounts. This would generate a small oDesk-based profile. 
Tasks 
Buyers and sellers would be pairing up to complete some task. The task would, ideally, be something that was (a) a real task in the marketplace (b) has a more-or-less objective measure of quality. It should also be monitorable in terms of time spent. Some kind of writing or data entry task would seemingly be ideal. The buyer should also perhaps have some role to play, so that seller preferences over buyers are meaningful (though perhaps buyers would post prices). 
Incentives 
We would give buyers an endowment to spend in the marketplace on sellers. The buyer would be the residual claimant i.e., they can keep whatever they do not spend on wages. We would also need to make their pay-off dependent on the quality of the work produced--otherwise they have an incentive to just find the cheapest contractor. 
Basic Experimental Design 

Decentralized: Buyers view seller profiles and can make offers; if an offer is accepted by seller, a match is formed. Buyers and sellers can only be matched to one sellers are at a time. Buyers have T time to make a match. At time T, matches are announced and work commences. We would have to decide how matches can be dissolved (if at all) before T.   
Centralized: Buyers and sellers browse profiles and build a rank-ordered list of the other side. At time T, DA is run and matches are announced. 

Software Development 
This project would have a very large infrastructural component---we are basically building from scratch an e-commerce platform. That being said, we could potentially re-use much of what id developed in follow-on projects. 

Task Performance Interface 
I think something like a Etherpad interface with extensive logging might be ideal. We could also insist that work be done with the oDesk team room tracker to get clicks and screen-shots for ex post analysis. The key is going to be excellent instrumentation. 
oDesk API integration 
This will simplify payments and give us real-world observable characteristics to readily incorporate into profiles 
Profile and Offer Interface 
This should be relatively straightforward, as it is primarily a crud interface. 
Proposed Software Development Plan  

I think we should try to plan to build a series of more-or-less throw-away prototypes of the market interface and run some pilots. I think there will likely be many issues that will arise when our plans hit reality and it would be good to work on the kinks before we scale anything up.  
