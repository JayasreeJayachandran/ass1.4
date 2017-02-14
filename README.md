# ass1.4
1.CHARACTERISTICS OF BIG DATA
VOLUME:
It the size of the data which is collected which is huge and unimaginable.
VELOCITY:
the speed at which data is generated and accumulated in the database.
VARIETY:
the data stored will be in various form like image,PDF etc.which will not be alike the 
management of those irrelevant data refers to variety.
VERACITY:
Big Data Veracity refers to the biases, noise and abnormality in data. Is the data that is being stored
veracity in data analysis is the biggest challenge. 
VALUE: 
 We uncover the meaningful relationships and patterns from the raw datas we collect from not only logs/text but also media
 and cctv footages
 2.SCALING UP AND SCALING OUT:
 SCALE UP :   
- it consumes more money and time as well the reliabilty will be low.   
- Scaling up is taking what you’ve got, and replacing it with something more powerful.  
From a networking perspective, this could be taking a 1GbE switch, and replacing it   
with a 10GbE switch. Same number of switchports, but the bandwidth has been scaled    
up via bigger pipes. The 1GbE bottleneck has been relieved by the 10GbE replacement.     
SCALE OUT :    
- rather than scale up this will be contrast where co ordianation is better since 
machines were shared with work as well machine failure will be handled.    
- Scaling out takes the infrastructure you’ve got, and replicates it to work in parallel.  
This has the effect of increasing infrastructure capacity roughly linearly. 
Data centers often scale out using pods. Build a compute pod, spin up applications to use it, then scale  
out by building another pod to add capacity. Actual application performance may not be linear,  
as application architectures must be written to work effectively in a scale-out environment. 
3.SOLUTION TO HANDLE BIG DATA:
Solution to the exploding data can only be increasing the capababilities of the system that collects/manages it.
For this we use,

Scale up: where this is not a recommended one which the data storage exceeds the limit the storage 
 	device capacity can be added up.as well it a costly,time consuming and a complex process.
 	> Increase the configuration of a single system, like disk capacity, RAM, data transfer
 	speed, etc.
 	> Complex, costly, and a time consuming process
 	 
Scale out: where here economical machines can be added up instead of adding the data storage through devices.
 	many number of computers can be added together to share the data's.and this is the better method than scale 
 	up.which is economical as well work is distributed among different machines.
 	> Use multiple commodity (economical) machines and distribute the load of
 	storage/processing among them
 	> Economical and quick to implement as it focuses on distribution of load
 	> Instead of having a single system with 10 TB of storage and 80 GB of RAM, use 40
 	machines with 256 GB of storage and 2 GB of RAM
