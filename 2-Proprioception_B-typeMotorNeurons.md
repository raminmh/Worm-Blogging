## **2) Proprioception in motor neurons is key for generating the forward locomotion**

Even when all the command interneurons were knocked out, C. elegans was able to generate the crawling [1]. This suggests the significant role of motor neurons in propagation of the bending waves. 

In general, rhythmic behavior is exhibited in animals thanks to the existence of neural circuits named as central pattern generator (CPG) [2]. There can be groups of CPG networks distributing rhythmic activities in an organism. CPG networks therefore should get coordinated with each other. Usually a sensory feedback mechanism exists for such coordination [3, 4, 5]. 

In C. elegans however, such sensory feedback does not exist due to lack of advanced sensory neurons. Accordingly, one argument suggests that the proprioceptive property can be "economically" exhibited by means of individual motor neurons [6, 8]. Electron microscopy illustrated that particularly cholinergic motor neurons (e.g. B-type), induce asynaptic processes all along the posterior without synaptic connections [6, 8]. Such mechanisms have been hypothesized as a [proprioception](http://topics.sciencedirect.com/topics/page/Proprioception) process. 
It has been also seen that the mechanical load from different environments (e.g. water or soil), changes the gait (e.g. swimming or crawling) [7], suggesting an unknown proprioception mechanism [8]. 

Wen et al. in [8], conducted wonderful experiments on quantification of proprioception in the B-type motor neurons of C. elegans.
-	By employing microfluidic devices and in vivo optical neurophysiology, they showed that [8]: “proprioceptive coupling between adjacent body segments constitutes the trigger that derives the bending wave propagation from head to tail.”
-	They showed that the posterior body parts are forced to bend shortly after the neighborhood anterior bending, in the same direction.
-	They quantified the spatial and temporal kinetics of the proprioceptive coupling localized to the B-type motor neurons. 
-	They have also demonstrated [8]: “Proprioception in the C. elegans motor circuit, beyond simply explaining the propagation of an undulatory wave from head to tail, also provides a quantitative explanation for gait adaptation to external load.”

<img width="727" alt="screen shot 2017-03-23 at 18 14 14" src="https://cloud.githubusercontent.com/assets/20689408/24260869/76e8aa08-0ff5-11e7-9d39-c094fb620665.png">

_**Figure 1.**  (Taken from [8]) Symbolic representation of connections from DB and VB motor neurons to some muscle cells through their neuromuscular junctions (Triangles) and their axons along the body of the worm. The asynaptic process shown in the figure illustrates the potential proprioceptive effect of the B-type motor neurons by means of their axons. Axons of the anterior DB motor neurons extend along the body of the worm to the posterior side making it possible to propagate a bending wave [8]._

According to such findings, I believe for modeling the crawling of C. elegans, in our neuron or muscle model one should properly include the biomechanics of the undulatory movement in order to include the proprioception mechanisms. 
Axons of the B-type motor neurons overlap each other along the body from head to tail. While some of them getting activated, they can communicate with their naighbors from the anterior side to the posterior side.  Such overlapping structure together with gap junctions between motor neurons (discussed in the first document) might presumably be the way a wave propagates from neuron to neuron. 
One possible way to include proprioception can be the establishment of hypothetical synapse-like actuators from anterior DB motor neurons along their axons to the muscle segments to which they face and to the neurons they overlap. 


References:

[1] T. Kawano, M.D. Po, S. Gao, G. Leung, W.S. Ryu, M. Zhen, An imbalancing act: gap junctions reduce the backward motor circuit activity to bias C. elegans for forward locomotion, Neuron, 72 (2011), pp. 572–586.

[2] T.G. Brown, The intrinsic factors in the act of progression in the mammal, Proc. R. Soc. Lond. B Biol. Sci., 84 (1911), pp. 308–319.

[3] O.J. Mullins, J.T. Hackett, J.T. Buchanan, W.O. Friesen
Neuronal control of swimming behavior: comparison of vertebrate and invertebrate model systems, Prog. Neurobiol., 93 (2011), pp. 244–269.

[4] X. Yu, W.O. Friesen, Entrainment of leech swimming activity by the ventral stretch receptor, J. Comp. Physiol. A Neuroethol. Sens. Neural Behav. Physiol., 190 (2004), pp. 939–949.

[5] K.G. Pearson, Generating the walking gait: role of sensory feedback, Prog. Brain Res., 143 (2004), pp. 123–129.

[6] J.G. White, E. Southgate, J.N. Thomson, S. Brenner, The structure of the nervous system of the nematode Caenorhabditis elegans, Philos. Trans. R. Soc. Lond. B Biol. Sci., 314 (1986), pp. 1–340.

[7] J.H. Boyle, S. Berri, N. Cohen, Gait modulation in C. elegans: An integrated neuromechanical model, Front. Comput. Neurosci., 6 (2012), p. 10

[8] Wen, Quan, Michelle D. Po, Elizabeth Hulme, Sway Chen, Xinyu Liu, Sen Wai Kwok, Marc Gershow et al. "Proprioceptive coupling within motor neurons drives C. elegans forward locomotion." Neuron 76, no. 4 (2012): 750-761.
