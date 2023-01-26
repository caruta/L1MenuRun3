# L1Menu_Collisions2022_v1_4_0_testing

[![online preview](https://img.shields.io/badge/Online%20preview-click%20here-blue)](https://htmlpreview.github.io/?https://github.com/caruta/L1MenuRun3/blob/master/development/L1Menu_Collisions2022_v1_4_0_testing/L1Menu_Collisions2022_v1_4_0_testing.html)


**Comment:** 
Copy of the v1_4_0 menu with some changes in the thresholds of few seeds for testing purposes [CMSLITDPG-1092](https://its.cern.ch/jira/browse/CMSLITDPG-1092).
Changes w.r.t. the v1_4_0:

   - TripleMu_5_3_3 &rarr; TripleMu_5_3p5_3 (bit 79)
   - TripleMu_5_3_3_SQ &rarr; TripleMu_5_3p5_3_SQ (bit 80)
   - L1_TripleMu_5SQ_3SQ_0OQ_DoubleMu_5_3_SQ_OS_Mass_Max9 &rarr; L1_TripleMu_5SQ_3p5SQ_0OQ_DoubleMu_5_3p5_SQ_OS_Mass_Max9 (bit 87)
   - L1_TripleMu_5SQ_3SQ_0_DoubleMu_5_3_SQ_OS_Mass_Max9 &rarr; L1_TripleMu_5SQ_3p5SQ_0_DoubleMu_5_3p5_SQ_OS_Mass_Max9 (bit 88)
   - L1_SingleEG36er2p5 &rarr; L1_SingleEG37er2p4 (bit 168)
   - L1_SingleIsoEG30er2p5 &rarr; L1_SingleIsoEG31er2p4 (bit 192)
   - L1_DoubleEG_25_12_er2p5 &rarr; L1_DoubleEG_25_13_er2p4 (bit 218)
   - L1_DoubleEG_LooseIso22_12_er2p5 &rarr; L1_DoubleEG_LooseIso22_13_er2p5 (bit 223)
   - L1_DoubleIsoTau34er2p1 &rarr; 271 L1_DoubleIsoTau34er2p0 (bit 271)
   - L1_SingleJet180 &rarr; L1_SingleJet180er2p4 (bit 313)

    
 **NOTE**: In order to correctly perform pure rate studies with this menu, the following seeds should be switched off: 
   - L1_TripleMu_3SQ_2p5SQ_0OQ_Mass_Max12 (bit 83)
   - L1_SingleIsoEG30er2p1 (bit 193)
   - L1_SingleJet180er2p5 (bit 322)
