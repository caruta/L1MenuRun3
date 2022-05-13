# Dedicated PS table of the L1Menu_Collisions2018_v2_1_0 for rate studies - Scenario 2018

**Description of PS table**
Prescale table for rate studies in 2018 scenario, to check the impact of higher L1 seed thresholds, as reported in JIRA ticket [https://its.cern.ch/jira/browse/CMSHLT-2295].

The PS columns are the following:
* 2E+34 => Menu with lower pT threshold seeds enabled
* 1.9E+34 => Menu with lower pT threshold seeds NOT enabled (except for low pt muon seeds: last 3 seeds in the table below)
* 1.8E+34 => Menu with lower pT threshold seeds NOT enabled (including low pt muon seeds)

A comparison between the lower thresholds at the end and at the beginning of 2018 (corresponding to the different scenarios in the PS table) is shown in the table below.

| **Lower thresholds seeds (end 2018)**           | **Higher threshold seeds (start of 2018)**   |
|-------------------------------------------------|----------------------------------------------|
| L1_SingleLooseIsoEG28er2p5                      |                                              |
| L1_SingleLooseIsoEG30er2p5                      |                                              |
| L1_SingleLooseIsoEG28er2p1                      |                                              |
| L1_SingleLooseIsoEG26er1p5                      |                                              |
| L1_SingleIsoEG28er1p5                           |                                              |
| L1_DoubleEG_25_12_er2p5                         | L1_DoubleEG_25_14_er2p5                      |
| L1_SingleEG36er2p5 (+ L1_SingleEG38er2p5)       | L1_SingleEG40er2p5                           |
| L1_SingleIsoEG28er2p5 (+ L1_SingleIsoEG30er2p5) | L1_SingleIsoEG32er2p5                        |
| L1_SingleIsoEG28er2p1                           | L1_SingleIsoEG30er2p1                        |
| L1_LooseIsoEG28er2p1_Jet34er2p5_dR_Min0p3       | L1_LooseIsoEG30er2p1_Jet34er2p5_dR_Min0p3    |
| L1_LooseIsoEG26er2p1_HTT100er                   | L1_LooseIsoEG28er2p1_HTT100er                |
| L1_DoubleJet_110_35_DoubleJet35_Mass_Min620     | L1_DoubleJet_115_40_DoubleJet40_Mass_Min620  |
| L1_TripleJet_95_75_65_DoubleJet_75_65_er2p5     | L1_TripleJet_100_80_70_DoubleJet_80_70_er2p5 |
| L1_DoubleIsoTau32er2p1                          | L1_DoubleIsoTau34er2p1                       |
| L1_ETMHF100 (+ L1_ETMHF110)                     | L1_ETMHF130                                  |
| L1_ETMHF100_HTT60er                             | L1_ETMHF110_HTT60er                          |
| L1_HTT320er_QuadJet_70_55_40_40_er2p4           | L1_HTT320er_QuadJet_80_60_er2p1_45_40_er2p3  |
|-------------------------------------------------|----------------------------------------------|
| L1_DoubleMu4_SQ_OS_dR_Max1p2                    | L1_DoubleMu4p5_SQ_OS_dR_Max1p2               |
| L1_DoubleMu8_SQ                                 | L1_DoubleMu9_SQ                              |
| L1_Mu6_HTT240er                                 | L1_Mu6_HTT250er                              |
