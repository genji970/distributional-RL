  
worker \- learner

1\) worker asynchronously collect data from environment 

2\) send it to learner(no replay buffer, no sampling) 

3\) n-step update. loss function \-\> (v-trace)  \+ importance sampling \+ clipped function \+ actor policy \* V-differ

4\) contraction mapping is used(fixed theorem  , cauchy theorem)  
