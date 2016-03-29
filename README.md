# LamportPriorityDME

It is assumed that in Lamport’s Distributed Algorithm that all sites have equal priority and
therefore each site broadcasts its request to access critical section to all other sites. In this
question you have to improvise Lamport’s Distributed Mutual Exclusion Algorithm by prioritizing
the sites. Each site is assigned a unique integer number ‘n’ (>=1 and <=K where K is the
number of sites in the system) which duly represents the priority as well as the ID of the
process. The priority of site decreases with the increase in the value of ‘n’ [i.e. priority value ‘1’
means highest, ‘2’ means second highest and so on]. The algorithm designed by you should
fulfill the following requirements:   

a. When there are simultaneous requests for the critical section, for multiple sites, then the
higher priority sites should be given preference over the lower priority sites subject to the
condition that lower priority sites should not starve for the critical section.  
b. Any site can enter the critical section only after making a request for critical section.
c. The algorithm should be deadlock free. 
 
Design the algorithm to satisfy above requirements. Before writing the algorithm, you have to
mention which data structure you are going to use and what is the role of each. Your algorithm  
should have the following four sections:  
1) Initialization  
2) Requesting Critical Section  
3) Executing Critical Section  
4) Releasing Critical Section  
