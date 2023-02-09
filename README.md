This is a README file documenting my experiments with simpy event simulation.  
(Also reviving some of my python programming knowledge.) 

- DONE use case 1: customer arrives and gets seated and goes away  
- DONE use case 2: multiple customers arrive and get seated and go away.  Restaurant capacity is not checked.  
- DONE use case 3: restaurant has capacity and capacity is checked.  If there is no seat available, customer will wait until someone goes away.  Introduce restaurant revenue which is a constant per customer.  
- DONE use case 4: restaurant has capacity and capacity is checked.  If here is no seat available, the customer goes away without eating.  
- DONE use case 5: customer has a patience threshold and will wait until patience is exhausted then go away.  But if turnover is happening, they will wait.  
- Use case 6:  A single customer is really a party with a random size between 1 and 6.  A party that exceeds the base capacity of the restaurant will get turned away at the door.   (so a party of 6 will never be waiting for 4 seats).   But a party all gets seated at the same time, and uses up that many resources.  Print out available seats.  
- Use case 7: A restaurant has tables of different sizes and each table size is a resource of its own for which people can be queued.  A  party of 2 will be tested for the 2-top queue first then 4-top then 6-top.  (This wants to be unit tested with a list of customers aka parties of predetermined sizes, which brings us to unit testing. and possibly to getting this out of a notebook and into a normal editing environment?)  
