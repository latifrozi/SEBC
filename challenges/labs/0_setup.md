##VM Specification and OS version
I am running 5 nodes of Azure VM GS1 with these specs :
* 2 core CPU
* 28GB memory
* 56GB SSD
* OS CentOS 6.8

##Volume Space Available on Each Node 

####Node1
![Node1](https://github.com/latifrozi/SEBC/blob/master/challenges/png/0_setup/2.%20Show%20volume%20space/%5B01%5D%20node%201.png)

####Node2
![Node2](https://github.com/latifrozi/SEBC/blob/master/challenges/png/0_setup/2.%20Show%20volume%20space/%5B02%5D%20node%202.PNG)

####Node3
![Node3](https://github.com/latifrozi/SEBC/blob/master/challenges/png/0_setup/2.%20Show%20volume%20space/%5B03%5D%20node%203.PNG)

####Node4
![Node4](https://github.com/latifrozi/SEBC/blob/master/challenges/png/0_setup/2.%20Show%20volume%20space/%5B04%5D%20node%204.PNG)

####Node5
![Node5](https://github.com/latifrozi/SEBC/blob/master/challenges/png/0_setup/2.%20Show%20volume%20space/%5B05%5D%20node%205.PNG)


##Repo List
####Node1
![Node1](https://github.com/latifrozi/SEBC/blob/master/challenges/png/0_setup/3.%20yum%20repolist%20enabled/%5B01%5D%20node%201.PNG)

####Node2
![Node2](https://github.com/latifrozi/SEBC/blob/master/challenges/png/0_setup/3.%20yum%20repolist%20enabled/%5B02%5D%20node%202.PNG)

####Node3
![Node3](https://github.com/latifrozi/SEBC/blob/master/challenges/png/0_setup/3.%20yum%20repolist%20enabled/%5B03%5D%20node%203.PNG)

####Node4
![Node4](https://github.com/latifrozi/SEBC/blob/master/challenges/png/0_setup/3.%20yum%20repolist%20enabled/%5B04%5D%20node%204.PNG)

####Node5
![Node5](https://github.com/latifrozi/SEBC/blob/master/challenges/png/0_setup/3.%20yum%20repolist%20enabled/%5B05%5D%20node%205.PNG)


##Users and Groups

###User : raffles
``` raffles:x:2000:2000::/home/raffles:/bin/bash ```

###User : fullerton
``` fullerton:x:3000:3000::/home/fullerton:/bin/bash ```


###Group : hotels 
``` hotels:x:2803:fullerton ```

###Group : shops 
``` shops:x:2802:raffles ```



