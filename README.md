#### what is virtual memory?
- indirection

- virtual memory is using the address the program uses and *maps* it the real address in memory
- page tables and traslation
	- how the mapping works essentially 
	- storing & doing mappings


---

## problems with virtual memory
- ### crash if we try to access more memory in a program then ram is installed


- ### Memory fragmentation:
	- ![alt text](https://i.imgur.com/PLSrPpo.png)
	- we have `4gb of ram` in this example
	- and we `moved program 1 & 2 into Virtual Memory` (ram)
	- and we `quit program 1`
	- even though we want to put `program 3` into virtual memory which holds 2gb we still cannot move it into memory
	- *due to the fact* that `program 2 is seperating the locations in memory` where we still have available data
	- `there is 2 spaces of 1gb`; we'd need 1 space of 2gb or more to move program 3 into virtual memory, this is memory fragmentation

![alt text](https://i.imgur.com/fCxxw7c.png)

--- 


## What really is virtual memory
- without virtual memory PROGRAM addresses ``=`` RAM addresses
- with virtual memory PROGRAM addresses `map to` RAM addresses
![alt text](https://i.imgur.com/BIV9mgB.png)

- virtual memory **solves the problem of not enough memory**


![alt text](https://i.imgur.com/ahT6SeL.png)

- solves the issue of **holes in address spaces**

![alt text](https://i.imgur.com/GPPuhDb.png)

- **keeps the program secure**

