Abstract:

Predicting at design time all context conditions a software will be exposed to is a very challenging mission for the engineering of self-adaptive systems. Unexpected contexts can be the cause of failures in self-adaptive systems, possibly leading the system to have undesired behaviors. The anticipation, at design time, of context as potential sources of uncertainties is important in order to implement the appropriate adaptation plans. This paper proposes a data mining and analysis process to unveil context sets and their correlation still at software design time. Thus, it is possible to spot sources of uncertainty in self-adaptive systems at early stages of the software development lifecycle and verify how they impact the system’s dependability attributes, such as reliability, availability, safety, etc. Our approach employs a data mining process relying on the constructs of a contextual goal model (CGM) to suitably elicit as well as map contexts to the system’s behavior from a design perspective. We experimentally evaluated our proposal on a Body Sensor Network system (BSN), by simulating a myriad of resources that could lead to a variability space of 4096 possible context conditions. Our results show that our approach is able to elicit contexts that would significantly affect a high percentage of BSN assisted patients with high health risk profile. The knowledge gained enables one to implement the system in a way that better attends the reliability needs of such health profile. Additionally, we explored the scalability of the mining process in the BSN context, showing it is able to perform under a minute even for simulated data at the size of over five orders of magnitude. This research supports the development of self-adaptive systems by anticipating at design time contexts that might restrain the achievability of system goals by means of a sound and efficient data mining process.

  This repository is a vehicle to share the images, datasets, results and other complementary outputs that support the understanding of the method and the replication of the experiments. We structured the repository as follows:

    1 - BSN: Files relevant to the description and representation of the BSN structure and operation;

    2 - Evaluation Graphs: Outputs from the data mining method, containing results concerning the scalability and the contribution itself;

    3 - Generated Datasets: Datasets generated by the simulated prototype, object of the Data Mining process.
