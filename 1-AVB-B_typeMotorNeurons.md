### **1)	On the importance of the command neuron AVB and B-type motor-neurons in the worm’s crawling:**

AVB command neuron together with B-type motor neurons function in the deriving the forward locomotion. There are seven dorsal and eleven ventral B-type motor neurons spread over the body of the worm. Considering a neural circuit, shown in Figure 1A and 1B, consist of only AVBL/R and all the B-type motor-neurons on the dorsal and ventral sides, one can highlight some attractive fundamental architectural design properties within the circuit:

-	AVBL/R synapse onto all B-type motor neurons with an average number of 10 connections to the dorsal and 8 connections to the ventral motor neurons. Among the motor neurons VB2 is getting the highest number of gap-junctions which can be an indicator of the importance of the VB2 in signaling. Many motor neurons receive a similar number of connections form AVB (with the assumption of the equally distributed weights of each synaptic connection). This presumably implies that the objective of AVB can be in the initiation of a forward-locomotion action as well as equal distribution of the forward-command for several motor-neurons. 

![openworm-pic2-avb-to-bmotorneurons](https://cloud.githubusercontent.com/assets/20689408/23712539/93e249f8-0423-11e7-8a13-f05732312d2f.png)
_**Figure 1.** AVB and B-type motor neurons neural circuit. A) AVBR\L and dorsal motor neuron neural circuit. Green lines are bidirectional gap junctions. Blue arrows represent excitatory synapses. Numbers on each line/arrow represent the number of synaptic connection between neurons. (Note that for instance 4/3, stands for 4 connections from AVBL and 3 connections from AVBR.) B) AVBR\L and ventral motor neuron neural circuit. C)  Worm's muscles [2]._

-	By looking at the sequential lateral connections among dorsal B-type motor-neurons, one can observe that DB1, DB2 and DB3 are strongly coupled through their gap-junctions while weakening their correlation rate with the rest of the synced motor-neurons DB4, DB5, DB6 and DB7, through a weak gap-junction between DB3 and DB4. This can potentially indicate that the activity of the dorsal B-type motor-neurons can be decoupled where the neurons 1 to 3 can be responsible for exciting part-A muscle cells shown in figure 1C, and the rest being responsible for the stimulation of the muscles depicted in part-B. 

-	Such property holds for the ventral B-type motor neurons as well. Neurons VB2 and VB3 are strongly coupled while they get gradually decoupled to the rest of the motor neurons by means of the weak connections among VB3, VB4 and VB5. Therefore, we assume that the first group including VB1 to VB4 excites part-A muscles cells and second group including VB5 to VB11 excites part-B of the body-wall muscles. 

-	**Hypothesis 1:** Like many other biological optimal networks such as beta cell hubs in islet functional architecture [3], I assume there exist hub neurons within the network of motor neurons in the C. elegans connectome which distribute commands within the network.  This is explainable by looking at the connections from AVB to the motor neurons where the first group of motor neurons and specially their hubs (DB1 and VB2) are getting stimulated the most and in the next group DB7 and VB11 gets the most number of connections. The hypothesis can be further supported by an analysis on the connectivity of the motor neurons and muscle cells which will be included within the next discussions.

Such property has been observed also within the D-type dorsal and ventral motor neurons which will be explained in the next discussion. 


References:

[1] wormwiring, http://wormwiring.org/hermaphrodite/herm.php

[2] wormbrowser, http://browser.openworm.org

[3] Johnston, Natalie R., et al. "Beta cell hubs dictate pancreatic islet responses to glucose." Cell Metabolism 24.3 (2016): 389-401.
