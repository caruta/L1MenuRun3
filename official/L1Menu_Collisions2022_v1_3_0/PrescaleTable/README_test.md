# Testing prescale tables for the L1Menu_Collisions2022_v1_3_0

Few notes on the content of the lumi columns:
- **2p00e34**: copy of the same column from the last PS table used online (i.e. L1Menu_Collisions2022_v1_3_0-13.6TeV).
- **1p90e34**: copy of 2p00e34 + 
    - `L1_LooseIsoEG28er2p1_Jet34er2p5_dR_Min0p3` disabled (keeping `L1_LooseIsoEG30er2p1_Jet34er2p5_dR_Min0p3`).
- **1p80e34**: copy of 2p00e34 + 
    - `L1_LooseIsoEG28er2p1_HTT100er` disabled (keeping `L1_LooseIsoEG30er2p1_HTT100er`).
- **1p70e34**: copy of 2p00e34 + 
    - `L1_LooseIsoEG22er2p1_IsoTau26er2p1_dR_Min0p3` disabled (keeping `L1_LooseIsoEG24er2p1_IsoTau26er2p1_dR_Min0p3`).
- **1p60e34**: copy of 2p00e34 + 
    - `L1_LooseIsoEG28er2p1_Jet34er2p5_dR_Min0p3` disabled, 
    - `L1_LooseIsoEG28er2p1_HTT100er` disabled and 
    - `L1_LooseIsoEG22er2p1_IsoTau26er2p1_dR_Min0p3` disabled.
- **1p50e34**: copy of 2p00e34 + 
    - `L1_DoubleIsoTau32` and `L1_DoubleIsoTau32` disabled (keeping L1_DoubleIsoTau35).
