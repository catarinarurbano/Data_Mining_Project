# Data Mining Project
  The impact of the World War II has affected not only the economic and political sectors as also the health of many Americans, especially the ones who fought and served their own nation. The purpose of this study consists in formulating a marketing approach for our clusters, given the data set provided by Paralyzed Veterans of America. The approaches taken into consideration include some feature engineering and treatment, outlier removal, data imputation, feature selection, among others. Directed towards the understanding of the different donor’s segments, we applied several clustering techniques, with the purpose of exploring the distinct characteristics of the classes, to develop a consistent solution for the problem provided. Analysing the various clustering algorithms, our final decision was the Kmeans, which despite of its limitations, proved to be the one with the better discrimination ability. As it is a real-life problem, our donors can be split into three main groups based on their neighbourhoods: 'Single People ', 'Wealthy People' and 'Countryside People'. This outcome is a reflection of the path we followed, so it might be distinct from other approaches. Nonetheless, we believe we came up with an objective and good one. 

Our final results were the following:
## Clusters Profile:
- Cluster Single People - This class can be described by having a fewer proportion of married people, which is enhanced by the great amount of people that were never married (MARR1, MARR4), living in non-family household (HHD6) / one-person household (HHN1), where we can highlight the percentage of the male householders above the mean (HHD10). As there are more people living alone, it is in agreement with their occupation of multi (2+) unit structures (DW4). Moreover, there are less people with bigger houses (HUR2) and a lower percentage of the owner-occupied houses comparing to the population mean (HU1), which is according to the previous assessment. In addition, most of these people live in urbanized areas (POP90C1, POP90C3), with a higher percentage of public sewer (HC19). Lastly, this group has an income slightly below the average (IC1, IC10, IC11). 

- Cluster Wealthy People – This group of donors can be characterized by their high income (IC1, IC10, IC11, IC12), which is above the population average, and extra income as dividends, rents, etc (HHAS3). Also, they live in a neighbourhood where it is hard to find inhabitants with low income (IC6). Additionally, they have a great purchase power, reflected by their big houses (+6 rooms) (HUR2) and possibility to pay high rents (HV3). Probably, this is the result of more of the neighbours having a BSc degree (EC7), where we can highlight that more people pursued a career in management (OCC2). These people live mainly in highly urbanized areas (POP90C1, POP90C3; Category “A” of GEOCODE2 more frequent), whose properties are mostly owned by them (HOMEOWNR; HU1). 

- Cluster Countryside People – This last cluster represents the ones who live in rural and metropolitan areas (POP90C1, POP90C3, Categories “C” and “D” of GEOCODE2 more frequent, Category “T2” of Domain more frequent), with lower percentage of public sewer (HC19). There are less people with BSc’s degree (EC7), whose income is a little below the mean (IC1) and in the neighbourhood fewer people have high income (IC10, IC11). Furthermore, as a consequence those are the ones who pay lower rents (HV3). The largest group of donors is represented in this cluster. 

### Marketing Strategy for each cluster:
  The Marketing proposal for the ones who are single consists in creating a donor’s card individual and untransmissible with a several of benefits according to the number of points it has which increases proportionally to the value of the donation. These benefits include self-love sessions, spa, body treatment, trips, historical museums, adrenaline experiences and blind dates. These options are the result of the partnerships between the PVA and the enterprises who offer them. This offer would be sent by an appealing email with all the details and its advantages explained, having the chance to choose between an online card or a physical one. 

  Secondly, our main recommendations for a marketing strategy for the richest people consists in organizing galas or solemn dinners where great part of the recipes will be converted to the PVA Association. In this type of activity, to provide an atmosphere of relaxation there will be a happy hour and live music performed by the most respected artists that have agreements with the PVA organization. 
  Also, these people will be invited to go to some lectures and expositions directly organized by the PVA in order to better understand its history and purpose as a non-profit association.  
  Another suggestion would be to create partnerships with auction companies, where part of the recipe would go to the association. 

  Finally, our approach for the rural people would be sweepstakes, whose prize would be symbolic, but attractive. The entry on this contest would be the donation, which has in account the lower income of these people, as asking for a less significant amount. Also, taking into consideration this is the most populated cluster, the fact that it is a donation of lower value can be overcome by the possibility of gathering more participants and achieving the aimed total value. In order to do this door-to-door campaign, it would be required some volunteers to help spreading the opportunity: our suggestion is to make agreements with the scouts of all over the America that usually are willing to support this type of initiatives and exist in large scale. 
