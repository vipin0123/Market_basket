# Market_basket

 Apriori Algorithm
 Apriori algorithm is a classical algorithm in data mining that is used for mining frequent itemsets and association rule mining.Apriori algorithm assumes that any subset of a frequent itemset must be frequent.
 In this we find the four thing on which basis we can make the profit more by selling the things 
      1. Support
      2. Confidence
      3. Lift
      4. Conviction
      
Support : Support of the item x is nothing but the ratio of the number of transactions in which the item x appears to the total number of transactions.
                  Support = number of transection in which the iteam 1 appears/ Total number of transection
               
Confidence : Confidence (x => y) signifies the likelihood of the item y being purchased when the item x is purchased. This method takes into account the popularity of the item x.
              
                Confidence((item1,item2)=>item3) = support(item1,item2,item3)/support(item1,item2)
                
 Lift : Lift (x => y) is nothing but the ‘interestingness’ or the likelihood of the item y being purchased when the item x is sold. Unlike confidence (x => y), this method takes into account the popularity of the item y.
 
              Lift((item1,item2)=>item3)=support(item1,item2,item3)/support(item1)+support(item3)
              
Conviction : 
            conviction(x=>y)=1-support(item3)/1-confidence(item1,item2=>item3)
