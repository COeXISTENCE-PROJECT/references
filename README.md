# References
----

List of problems that we address within the `COeXISTENCE` project with the relavant literature on them.

The base is the reference list used in the proposal:  [here](files/full_references_from_proposal.pdf).

Each section starts with a narrative part, which is expanded gradually and with a list of papers (with comments).


---

## Research problems

### Route choice

> We assume humans are Rational Utility Maximizers (Manski, 1977), thus when they travel they maximize their utility (McFadden, 1980), i.e. in the route choice context, they make subjectively rational choices (Ben-Akiva et al, 1984), or boundedly rational (Xuan and Liu, 2016). 

1. Manski, Charles F. "The structure of random utility models." Theory and decision 8, no. 3 (1977): 229. [paper](https://idp.springer.com/authorize/casa?redirect_uri=https://link.springer.com/content/pdf/10.1007/BF00133443.pdf&casa_token=iIIBTGiW6sAAAAAA:sU5jZAzd8vLB_uG505C2iH65Am9JCAPJ1Y2Rn8dfzS0h3dCYqb_yfY3-MnmSwyKZzm9jxt_42cw-4dJG)

2. McFadden, Daniel. "Econometric models for probabilistic choice among products." Journal of Business (1980): S13-S29. [paper](https://www.jstor.org/stable/pdf/2352205.pdf?casa_token=tPP6IUW9sSQAAAAA:jPNwc-QOSdozwWo4sBcIAp64w0pCDS2W3VsnE5vDnPBZ1BgRl8lax6O-38aK5FFdR33GW8DTme6tr14mPXrSGVDQeki_jauTStWAyiCKVDJRWYr6XCw)
3. Ben-Akiva, M., Bergman, M. J., Daly, A. J., & Ramaswamy, R. (1984). Modelling inter urban route choice behaviour. In Papers presented during the Ninth International Symposium on Transportation and Traffic Theory held in Delft the Netherlands, 11-13 July 1984..
4. Di, Xuan, and Henry X. Liu. "Boundedly rational route choice behavior: A review of models and methodologies." Transportation Research Part B: Methodological 85 (2016): 142-179. [doi](https://doi.org/10.1016/j.trb.2016.01.002)
5. K-shortest path search [wiki](https://en.wikipedia.org/wiki/K_shortest_path_routing#:~:text=The%20k%20shortest%20path%20routing,the%20loopless%20k%20shortest%20paths)
   

###  User Equilibrium

> Since users are rational utility maximizers, who minimize their travel costs (minimize utility), they adjust their choices to maximize the _expected_ utility.

1. Klein, Ido, and Eran Ben-Elia. "Emergence of cooperation in congested road networks using ICT and future and emerging technologies: A game-based review." Transportation Research Part C: Emerging Technologies 72 (2016): 10-28. [paper](https://www.sciencedirect.com/science/article/pii/S0968090X16301620?casa_token=XWbhB5f7O6QAAAAA:f5o19RDcbLXSNVQ96-nv60fgMnaRcWIA2-Vfg95r6L6LuoZDGinNsouxH_mOIQHTpa42pr9TqQ)
2. D. A. Lazar, E. Bıyık, D. Sadigh, and R. Pedarsani, “Learning how to dynamically route autonomous vehicles on shared roads,” Transportation research part C: emerging technologies, vol. 130, p. 103 258, 2021. [doi](https://doi.org/10.1016/j.trc.2021.103258)
3. J. Wang, S. Peeta, and X. He, “Multiclass traffic assignment model for mixed traffic flow of human-driven vehicles  and connected and autonomous vehicles,” Transportation Research Part B: Methodological, vol. 126, pp. 139–168,  2019. [paper](https://sites.gatech.edu/peeta/files/2021/01/2019-Wang-Peeta-He-TR-B.pdf)





### Reinforcement learning

#### papers

#### materials and courses

1. Sergei Levine Course on [YT](https://www.youtube.com/watch?v=JHrlF10v2Og&list=PL_iWQOsE6TfXxKgI1GgyV1B_Xa0DxE5eH)
2. RL book by [Sutton]( https://www.google.pl/books/edition/Reinforcement_Learning_second_edition/sWV0DwAAQBAJ?hl=pl&gbpv=1&dq=sutton+barto&printsec=frontcover)

### Microsimulation 

### Connected autonomous vehicles

> Connected Autonomous Vehicles can independenty traverse the urban network without human intervention (Level 5+).

1. [Self-driving car wiki](https://en.wikipedia.org/wiki/Self-driving_car) - and SAE Levels.


---

## Software

* Simulator: [SUMO](https://eclipse.dev/sumo/) and Assignment in SUMO [here](https://sumo.dlr.de/docs/Demand/Dynamic_User_Assignment.html)
* SUMo-RL [repo](https://github.com/LucasAlegre/sumo-rl) - very relevant simulator - it integrates SUMO with RL, yet on the traffic signal control level. We may inspire from that a lot.
* RL Stable baselines [repo](https://stable-baselines.readthedocs.io/en/master/)
  


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
