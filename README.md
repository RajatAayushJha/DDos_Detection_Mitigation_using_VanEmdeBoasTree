# DDos_Detection_Mitigation_using_VanEmdeBoasTree
This project focusses on alleviating malicious traffic from DDoS attacks since many famous websites have been attacked by them and massive losses have been reported in recent years. 
We propose a Priority Queue-Based scheme to analyse the interval of the arrival times of incoming packets in order to distinguish malicious traffic from normal traffic and to take care of malicious attacks clogging the network. 
The proposed Priority Queue-based scheme in this project not only effectively decreases the flows of malicious packets from DDoS attacks with various packet rates, but also provides smooth and constant flows for packets sent by normal users. 
Our priority queue-based scheme performs much better than other schemes when the number of the DDoS nodes becomes large.
Further the threshold to identify attackers will be optimized using Genetic Algorithm for improved performance in any situation. 

We analyze the interval time of incoming packets and use the harmonic mean to identify the malicious traffic. The malicious traffic will be pushed into the low priority queue and get low priority services from the server. By this mechanism, the normal user will be able to obtain better QoS from the server.
This harmonic mean will be optimized by a specialized genetic algorithm, therefore no matter the situation will perform better than manually initializing the harmonic mean.
