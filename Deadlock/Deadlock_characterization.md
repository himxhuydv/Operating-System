# Deadlock Characterization
deadlock basically happened when one process is requesting of the resource but it's currently acquired by another process.so the first process which is requesting have to wait.so this result in deadlock state.
For the deadlock there are some nesscersary condition have to accept 
**Mutual Exclusion**  
**Hold and wait**    
**No preemption**  
**Circular wait**   
### Mutual Exclusion
In this the Resource must have been in the non shareable mode and that resource is assinged to a process and another process which is requesting must have to wait untill the first process which is using the resource execute and released it then have to use it.
### Hold and Wait
In this the every process held resources but they are requesting for additional resources and that is also currently hold by another resources.that thing is called hold and wait.
### No preemption
in this if there is no priority is set then there is a drawbrack then every process will say that give me the resource first result in the waiting because everyprocess is in the race of getting of the resource.
### Circular wait 
in this there are n-1 process and the n-1 resource each is held by the next process and the n-1 required the resource of next process to fully execute.mean there are p1,p2,p3 and there is resource like r1,r2,r3,r4,r5 and p1 required the r2 resource and the r2 is currently held by the p2 and p2 required r3 that is currentrly accuired by the p3 and p3 required r1 that is currenetly accuried by the p1 (so these are in the circular waiting so that there next process execute then they finally get the released resource)