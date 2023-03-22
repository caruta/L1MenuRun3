# L1Menu_Collisions2023_v1_1_0

[![online preview](https://img.shields.io/badge/Online%20preview-click%20here-blue)](https://htmlpreview.github.io/?https://github.com/caruta/L1MenuRun3/blob/master/development/L1Menu_Collisions2023_v1_1_0/L1Menu_Collisions2023_v1_1_0.html)



**Comment:** 
New version of 2023 menu with the addition of new VBF seeds [CMSLITDPG-1099](https://its.cern.ch/jira/browse/CMSLITDPG-1099).

<br/>

The following seeds have been added:
   - `L1_DoubleJet_60_30_Mass_Min500_DoubleJetCentral50` (bit 507)
   - `L1_DoubleJet40_Mass_Min450_IsoEG10er2p1_RmOvlp` (bit 508)
   - `L1_DoubleJet_80_30_Mass_Min500_Mu3` (bit 509)
   - `L1_DoubleJet_65_30_Mass_Min400_METHF65` (bit 510)

N.B. : The seed `L1_DoubleJet35_Mass_Min450_IsoTau45er2p1_RmOvlp_dR0p5 ` has not been added because it was already present in the menu (bit 362).
<br/>

**NOTE**: The default behavior of the script sets the prescales of seeds using NotBptx or Bptx to zero. This is due to problems emulating NotBptx in ZeroBias. If you wish to include the prescale information for these seeds, use the --includeBptx option.
