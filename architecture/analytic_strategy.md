Analytic Strategy
--- 

The following text outlines the sequence of analytic procedures to which HRS data is proposed to be submitted en route our preparation to the Gothenburg Workshop in October 28-30, 2015.  

The workshop **AIMS** to design the methodology with which to
> estimate the impact of the transition into retirement on subsequent cognitive decline, physical functioning, and well-being as compared to remaining in work, remaining unemployed, or remaining outside the labour force.  

The **OBJECTIVE** of the workshop is to 
> develop a strategy for implementing a multi-study replication of the statistical analyses that evaluates this impact.   


## Overview


The proposed strategy identifies the following milestones:

 - **Milestone 0** : conceptual model of retirement is defined and operationalized in HRS data. The metric of retirement contains a small number of exhaustive and mutually exclusive categories. Each of these categories (values on the retirement trajectory) describes individual's relationship with the workforce at that moment in time. Tidy data tracking individuals' transitions between categories over time is assembled from the raw databank of the study.  
 
 - **Milestone 1**: Transition data is explored with Markov Chain / Random Walks model. The matrix of transitions shows the population dynamics. Examining the prevalences of and transitions among categories 1) verifies that the conceptual model selected during M0 makes sense in the context of the observed data and 2) forms the basis for the inuition about latent classes, which will be explored with latent transition analysis in Milstone 2.
 
- **Milstone 2**: Retirement trajectories are explored with Latent Transition Analysis (Collins & Lanza, 2010, section 7.4, p.196). Retirement transitions are clustered into latent classes according to the similarity of temporal pattern. Observed pattern from M1 and emergent groupings from LTA lead to formation of reference groups to be compared with respect to their cognitive decline, physical functioning, and well-being. (This comparison is intended to be replicated over studies.)

- **Milestone 3**: Cognitive, physical, and well-being measures are analyzed with Bivariate Growth Curve Model in conjuncture with latent structures from M2. BGCM serves as a precursor to piecewise model to be developed in M4 and sets a meaningful reference point. Rough temporal pattern of the outcome emerge. Threats to statistical conclusion validity are identified. Revision of M2 as necessary. 


- **Milestone 4**: Cognitive, physical, and well-being measures are analyed with Piecewise BGCM in conjuncture with latent structures from M2. We anticipate the failure of M3 to address all relevant threats to validity due to nonlinear dynamics associated with a specific temporal point of retirement.  The most appropriate piecewise function is identified.  As in M3, results involve comparison of reference groups defined in M2. Revision of M2 and/or M3 as necessary.



The models on which we settle at Milestone 4 will be replicated across studies.  

Such cascading roadmap affords flexibility in manuvering through pivotal decisions. For example, different answers to the following  questions imply structural changes in the subsequent milestones:    
- how many exhaustive & exclusive categories should retirement measure contain? (M0)   
- what should these categories be? (M0)  
- how many refernce groups is sufficient to capture the complexity of retirement dynamics? (M2)   
The system of dynamic reporting will allow us to explore these possibilities with relative ease. 


Conceptualizing retirement  as transitions among defined categories is explored in the report [conceptual models of retirement](../reports/conceptual_models_retirement.md)  

Basic data preparation of [RAND HRS files](https://github.com/IALSA/HRS/tree/master/data) is traced in a dedicated repository.  


