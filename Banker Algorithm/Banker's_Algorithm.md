# Banker's Algorithm
(Before starting this topic you will need the prior knowledge about the deadlock.if you don't know about that consider my advise and  go checkout my deadlock notes.i am here providing you the acess URl.)[Deadlock](file:///C:/Users/ashay/OneDrive/Desktop/SACRIFICES%20OF%20COMFORT/Operating-System/Deadlock/Deadlock.md)
So,bascially the Banker Algorithm is a deadlock avoidance is a algorithm used in Operating system to ensure that resource are allocated to the process without ever leading a deadlock 
*you can say it's a deadlock prevention technique which is used for safely transfer of the resources without any problem*
*There are two kind of Algo inside of the Banker's Algorithm :-
1.Resource Request Algorithm.
2.Safety Algorithm.

#### So, Let talk deep about these algorithm so we can understand every fundamental of it .
1.**Resource Request Algorithm**:The set of processes is requesting for a resource it's request consider as the need of the resources.So, that they can fully executed.The total resource they are asking are consider as the MAX and the resources that are given by the CPU is called allocated and after this the total still required by the processes will be the need for complete execution and the availabilty terma as the total resource currently  by available.
```Request p=>Max```.
```Request p=>Avaiability  ```
Why? we required these parameter. 
because this state that no processes get over claiming of the resource and ensurs it's declared limits.
*Banker's Algorithm is based on the promise which it's made to the operating system that they will not exceed their maximum decalred claim.*
and for that reason. **If the request=>need then take *action and reject that as an error.***
And that goes same for the Avaiable**if any Request=>avaiable denied that *request asap and process must wait for freeing of the resource in future.So,that it can get fully executed.***
2.**Safety Algorithm**:This is algorithm state as same as the name.A situation where every thing in the safe state or you can say there will be no possibility of getting deadlock situation.
**Safe state**usually happens when the request get fullfill it's required needs and finally get fully executed that can be written in state of the safe sequence is term as the safe state.
<P1,P2,P3,P4....Pn> if this sequence is generated it mean every process get's fully executed without getting in to any Deadlock state.

So,there is so much numerical is being asked in the Gate Exam.
