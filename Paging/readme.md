# Paging
*Memory mangement technique*
So in the paging we divide the process into equally sized pages and then putting that into the  main memory that is divide into the memory frames. that equally sized pages into the main memory frames.this is what's mean by paging.
here we generally have the 1.Process size 2.Page Size 
And this we have the formula as we know that is 
```number of pages will be=Process Size/Page Size ```
Process size=shows that how many bytes does the process have.if the process size=4 byte then the total number of  the bytes does the process have is.and binary bytes start fro zero.

### Main Memory
Memory is byte addresable
in the main memory there also will be the 1.Memory size 2.Frame size 
and to know how many frame is going to have in the main memory
 ```memory=memory size/frame size ```
 **One more important thing to know that page size and the frame size needs to be same,because the pages needs to be fit inside of the frame of the main memory.that's why they need to be equal.**
 So after this whole thing done the pages get inside of the main memory and inside of that frames.

#### What will happened if CPU asked for the bytes on the specific place .why does it asked it's because it require for the data that is store on the specific byte.
so when the CPU asked it can't directly get the byte because the bytes is randomly store in the frame they are not store in the one by one.because there will be case that the main memory can be filled .like F1 is filled then f2 is empty here you can save but then the F3 is filled and you have to store ther page you just store that in the next F4.that's why you really can just take the byte from the Main memory frames.

**Absoulte Address:a very important concept the absoulte address basically mean the actual bytes that is required by the cpu is store that is present inside of the main memory**

# Mapping 
mappin is a technique used when the the cpu generate a address and then that address is converted to absoulte address.
**And for convertion we use the MMU(memory Management Unit)**
And the memory management uses **Page Table.**

