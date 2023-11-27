# References
----

List of problems that we address within the `COeXISTENCE` project with the relavant literature on them.

The base is the reference list used in the proposal:  [here](files/full_references_from_proposal.pdf).

Each section starts with a narrative part, which is expanded gradually and with a list of papers (with comments).


---

# Research problems

## Route choice

> We assume humans are Rational Utility Maximizers (Manski, 1977), thus when they travel they maximize their utility (McFadden, 1980), i.e. in the route choice context, they make subjectively rational choices (Ben-Akiva et al, 1984), or boundedly rational (Xuan and Liu, 2016).

[More detailed sandbox](route_choice.md)

1. Manski, Charles F. "The structure of random utility models." Theory and decision 8, no. 3 (1977): 229. [paper](https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/content/pdf/10.1007/BF00133443.pdf&casa_token=iIIBTGiW6sAAAAAA:sU5jZAzd8vLB_uG505C2iH65Am9JCAPJ1Y2Rn8dfzS0h3dCYqb_yfY3-MnmSwyKZzm9jxt_42cw-4dJG)

2. McFadden, Daniel. "Econometric models for probabilistic choice among products." Journal of Business (1980): S13-S29. [paper](https://www.jstor.org/stable/pdf/2352205.pdf?casa_token=tPP6IUW9sSQAAAAA:jPNwc-QOSdozwWo4sBcIAp64w0pCDS2W3VsnE5vDnPBZ1BgRl8lax6O-38aK5FFdR33GW8DTme6tr14mPXrSGVDQeki_jauTStWAyiCKVDJRWYr6XCw)
3. Ben-Akiva, M., Bergman, M. J., Daly, A. J., & Ramaswamy, R. (1984). Modelling inter urban route choice behaviour. In Papers presented during the Ninth International Symposium on Transportation and Traffic Theory held in Delft the Netherlands, 11-13 July 1984..
4. Di, Xuan, and Henry X. Liu. "Boundedly rational route choice behavior: A review of models and methodologies." Transportation Research Part B: Methodological 85 (2016): 142-179. [doi](https://doi.org/10.1016/j.trb.2016.01.002)
5. Zhu S, Levinson D. Do people use the shortest path? An empirical test of Wardrop’s first principle. PloS one. 2015; 10(8):e0134322. [doi[(https://doi.org/10.1371/journal.pone.0134322)
6. K-shortest path search [wiki](https://en.wikipedia.org/wiki/K_shortest_path_routing#:~:text=The%20k%20shortest%20path%20routing,the%20loopless%20k%20shortest%20paths)
   

##  User Equilibrium

> Since users are rational utility maximizers, who minimize their travel costs (minimize utility), they adjust their choices to maximize the _expected_ utility.
> Maybe they somehow converge to the _user equilibrium_ (Wardrop's paraphrase of Nash equilibrium).
> Such _equilibrium_ may be either deterministic (when travel times and utility formulas are fixed and homogenous) (Wardrop, 1952), or stochastic (when either travel times, or demand or users perception or users taste variations are non-determnistic) (Daganzo and Sheffi, 1997).
>
> The travellers experience utilities of the action they have chosen and learn the expected travel times (Bogers et al., 2007).
> Which may be expressed either algoritmhically (to find the equilibrium) or behaviourally, as realistic adaptation and day-to-day learning (Watling and Cantarella, 2016).
>
> This proces, however is never optimal. As we either are _rationalLY inattentive_ (Jiang, Fosgerau, 2019). A rationally inattentive agent has abundance of information, which she/he cannot process and so chooses which pieces of information to process. In doing so, the agent optimizes (the expected utility - cost of information). The cost of information is given by change of information (Shannon) entropy. This model could be useful in situations where there is a rich transportation information source, which drivers can readily use.  
> A comprehensive basic review of the rational inattention theory (done for the European Central Bank?) can be found in (Maćkowiak, Matějka, Wiederholt, 2023). For mathematical derivation in case of discrete choice, see (Matějka and McKay, 2015). An even more general result, linking discrete choice and rational inattention (giving rise not only to MNL) was obtained in (Fosgerau et al., 2020)
> 
> This can also be observed in laboratory experiments (Selten et al. 2007) or from the field observations (Arriagada et al., 2022) or (Ramirez, Leclercq et al., 2021). (Yildirimoglu, 2108) evaluates 20k tracks of Shenzen taxis to veriy equilibrium.

1. Nash Equilibrium [wiki](https://en.wikipedia.org/wiki/Nash_equilibrium)
5. Wardrop Equilibruim [wiki](https://en.wikipedia.org/wiki/John_Glen_Wardrop)
6. Wardrop, J. G. (1952). Road paper. some theoretical aspects of road traffic research. Proceedings of the institution of civil engineers, 1(3), 325-362. [pdf](https://doi.org/10.1680/ipeds.1952.11259)
7. Enide A. I. Bogers, Michel Bierlaire, and Serge P. Hoogendoorn. 2007. Modeling Learning in Route Choice. Transportation Research Record 2014, 1 (2007), 1–8. [pdf](https://doi.org/doi:10.3141/2014-01)
8. Hazelton, Martin L. "Some remarks on stochastic user equilibrium." Transportation Research Part B: Methodological 32, no. 2 (1998): 101-108. [doi](https://doi.org/10.1016/S0191-2615(97)00015-5)
9. Daganzo, Carlos F., and Yosef Sheffi. "On stochastic models of traffic assignment." Transportation science 11, no. 3 (1977): 253-274. [pdf](https://pubsonline.informs.org/doi/epdf/10.1287/trsc.11.3.253)
10. Yang, Hai. "System optimum, stochastic user equilibrium, and optimal link tolls." Transportation science 33, no. 4 (1999): 354-360. [pdf](https://pubsonline.informs.org/doi/epdf/10.1287/trsc.33.4.354)
11. Cantarella, Giulio E., and David P. Watling. "A general stochastic process for day-to-day dynamic traffic assignment: Formulation, asymptotic behaviour, and stability analysis." Transportation Research Part B: Methodological 92 (2016): 3-21. [pdf](https://eprints.whiterose.ac.uk/99558/1/Cantarella%20%26%20Watling%20Part%20B%202016.pdf)
12. Gentile, Guido. "Solving a Dynamic User Equilibrium model based on splitting rates with Gradient Projection algorithms." Transportation Research Part B: Methodological 92 (2016): 120-147. [pdf](https://iris.uniroma1.it/bitstream/11573/899213/1/Gentile_preprint_Dynamic-user_2016.pdf)
13. Klein, Ido, and Eran Ben-Elia. "Emergence of cooperation in congested road networks using ICT and future and emerging technologies: A game-based review." Transportation Research Part C: Emerging Technologies 72 (2016): 10-28. [paper](https://www.sciencedirect.com/science/article/pii/S0968090X16301620?casa_token=XWbhB5f7O6QAAAAA:f5o19RDcbLXSNVQ96-nv60fgMnaRcWIA2-Vfg95r6L6LuoZDGinNsouxH_mOIQHTpa42pr9TqQ)
2. D. A. Lazar, E. Bıyık, D. Sadigh, and R. Pedarsani, “Learning how to dynamically route autonomous vehicles on shared roads,” Transportation research part C: emerging technologies, vol. 130, p. 103 258, 2021. [doi](https://doi.org/10.1016/j.trc.2021.103258)
3. J. Wang, S. Peeta, and X. He, “Multiclass traffic assignment model for mixed traffic flow of human-driven vehicles  and connected and autonomous vehicles,” Transportation Research Part B: Methodological, vol. 126, pp. 139–168,  2019. [paper](https://sites.gatech.edu/peeta/files/2021/01/2019-Wang-Peeta-He-TR-B.pdf)
4. JOSEPH N. PRASHKER & SHLOMO BEKHOR (2004) Route Choice Models Used in the Stochastic User Equilibrium Problem: A Review, Transport Reviews, 24:4, 437-463, [DOI](https://doi.org/10.1080/0144164042000181707)
5. New Formulations of the Stochastic User Equilibrium with Logit Route Choice as an Extension of the Deterministic Model [pdf](https://www.researchgate.net/profile/Guido-Gentile/publication/327925599_New_Formulations_of_the_Stochastic_User_Equilibrium_with_Logit_Route_Choice_as_an_Extension_of_the_Deterministic_Model/links/6018a0a345851517ef31e7c5/New-Formulations-of-the-Stochastic-User-Equilibrium-with-Logit-Route-Choice-as-an-Extension-of-the-Deterministic-Model.pdf)
6. Gege Jiang, Mogens Fosgerau, Hong K. Lo, Route choice, travel time variability, and rational inattention, Transportation Research Part B: Methodological, [doi](https://www.sciencedirect.com/science/article/abs/pii/S0191261518311433)
7. Matějka, F., & McKay, A. (2015). Rational Inattention to Discrete Choices: A New Foundation for the Multinomial Logit Model. The American Economic Review, 105(1), 272–298. http://www.jstor.org/stable/43497060  (mathematical derivation of the rational inattention model in the case of discrete choice. Interestingly, a kind of multinomial logit model is a consequence, however it seem not to suffer from the blue bus-red bus paradox)
8. Andrew Caplin, Mark Dean, John Leahy, Rational Inattention, Optimal Consideration Sets, and Stochastic Choice, The Review of Economic Studies, Volume 86, Issue 3, May 2019, Pages 1061–1094, https://doi.org/10.1093/restud/rdy037
9. Maćkowiak, Bartosz, Filip Matějka, and Mirko Wiederholt. 2023. "Rational Inattention: A Review." Journal of Economic Literature, 61 (1): 226-73.
DOI: 10.1257/jel.20211524, pdf: https://www.ecb.europa.eu/pub/pdf/scpwps/ecb.wp2570~a3979fbfa5.en.pdf.
10. Fosgerau, M., Melo, E., de Palma, A. and Shum, M. (2020), DISCRETE CHOICE AND RATIONAL INATTENTION: A GENERAL EQUIVALENCE RESULT. International Economic Review, 61: 1569-1589. https://doi.org/10.1111/iere.12469
   
#### Empirical observations and model estimations

1. Arriagada, J., Munizaga, M. A., Guevara, C. A., & Prato, C. (2022). Unveiling route choice strategy heterogeneity from smart card data in a large-scale public transport network. Transportation Research Part C: Emerging Technologies, 134, 103467. [doi](https://doi.org/10.1016/j.trc.2021.103467)
2. Swiss OD matrices and model estimations [doi](https://doi.org/10.3929/ethz-b-000023520)
3. Selten, Reinhard, Thorsten Chmura, Thomas Pitz, Sebastian Kube, and Michael Schreckenberg. "Commuters route choice behaviour." Games and Economic Behavior 58, no. 2 (2007): 394-406. [doi](https://doi.org/10.1016/j.geb.2006.03.012)
4. Ramirez, Humberto Gonzalez, Ludovic Leclercq, Nicolas Chiabaut, Cécile Becarie, and Jean Krug. "Travel time and bounded rationality in travellers’ route choice behaviour: A computer route choice experiment." Travel Behaviour and Society 22 (2021): 59-83. [doi](https://doi.org/10.1016/j.tbs.2020.06.011)
5. Helbing, Dirk. "Dynamic decision behavior and optimal guidance through information services: Models and experiments." In Human Behaviour and Traffic Networks, pp. 47-95. Berlin, Heidelberg: Springer Berlin Heidelberg, 2004.
6. 7. Yildirimoglu, Mehmet, and Osman Kahraman. "Searching for empirical evidence on traffic equilibrium." PloS one 13, no. 5 (2018): e0196997. [pdf](https://sci-hub.se/10.1371/journal.pone.0196997)


## Reinforcement learning

> The human behaviour in Traffic highly resembles the Reinforcement Loop.

 1. Fangfang Wei, Shoufeng Ma, Ning Jia, "A Day-to-Day Route Choice Model Based on Reinforcement Learning", Mathematical Problems in Engineering, vol. 2014, Article ID 646548, 19 pages, 2014. [doi](https://doi.org/10.1155/2014/646548)

### papers

### materials and courses

1. Sergei Levine Course on [YT](https://www.youtube.com/watch?v=JHrlF10v2Og&list=PL_iWQOsE6TfXxKgI1GgyV1B_Xa0DxE5eH)
2. RL book by [Sutton]( https://www.google.pl/books/edition/Reinforcement_Learning_second_edition/sWV0DwAAQBAJ?hl=pl&gbpv=1&dq=sutton+barto&printsec=frontcover)

## Microsimulation 

## Connected autonomous vehicles

> Connected Autonomous Vehicles can independenty traverse the urban network without human intervention (Level 5+).

1. [Self-driving car wiki](https://en.wikipedia.org/wiki/Self-driving_car) - and SAE Levels.


---

## Software

* Simulator: [SUMO](https://eclipse.dev/sumo/) and Assignment in SUMO [here](https://sumo.dlr.de/docs/Demand/Dynamic_User_Assignment.html)
* SUMO-RL [repo](https://github.com/LucasAlegre/sumo-rl) - very relevant simulator - it integrates SUMO with RL, yet on the traffic signal control level. We may inspire from that a lot.
* RL Stable baselines [repo](https://stable-baselines.readthedocs.io/en/master/)
* [FLOW](https://flow-project.github.io/) simulator for RL - it inspired me a lot during grant writing. It is SUMO + RLLib and the focus is on traffic flow rather than equilibrium, but also very relevant.
  
---

## Source files

* [B1_final.pdf](files/B1_final.pdf) - proposal - short version
* [B2_final.pdf](files/B2_final.pdf) - proposal - long version
* [references from proposal](files/full_references_from_proposal.pdf)

----- 
**Rules to add and edit:**

1. Add relevant papers to respective sections (or add a new section)
2. Cite papers below with a doi link (let's use google scholar APA)
3. Add .bib to the bilbiography file (from scholar)
4. Add one page description in the narrative part
5. If the file is not availble online - please try sci-hub or RG or other sources to download it and put into `files` folder.
