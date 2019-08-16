# Analysis codes
This is an analysis code that may be used to analyse the data of the ATLAS published dataset.

## git and gitlab
Ideally, you are able to clone a git repository, and you have an GitLab account (if you want to contribute :)


Table 1: Proposed content of a data sample for educational purposes. The content presented is a further slimmed
down version of the tuple produced by AnalysisTop.

| branchname                | type            |description |
| -----------------         | --------------  | ---------- |
| runNumber                 | int             | runNumber |
| eventNumber               | int             | eventNumber |
| channelNumber             | int             | channelNumber |
| mcWeight                  | float           | weight of an MC event |
| pvxp_n                    | int             | number of primary vertices |
| vxp_z                     | float           | z-position of the primary vertex |
| trigE                     | bool            | boolean whether a standard trigger has fired in the egamma stream |
| trigM                     | bool            | boolean whether a standard trigger has fired in the muon stream |
| passGRL                   | bool            | signifies whether event passes the GRL may be put in isGoodEvent |
| hasGoodVertex             | bool            | signifies whether the event has at least one good vertex |
| lep_n                     | int             | number of preselected leptons |
| lep_truthMatched          | vector<bool\>    | boolean indicating whether the lepton is matched to a truth lepton |
| lep_trigMatched           | vector<bool\>    | boolean signifying whether the lepton is the one triggering the event |
| lep_pt                    | vector<float\>   | transverse momentum of the lepton |
| lep_eta                   | vector<float\>   | pseudo-rapidity of the lepton |
| lep_phi                   | vector<float\>   | azimuthal angle of the lepton |
| lep_E                     | vector<float\>   | energy of the lepton |
| lep_z0                    | vector<float\>   | z-coordinate of the track associated to the lepton wrt. the primary vertex |
| lep_charge                | vector<float\>   | charge of the lepton |
| lep_flag                  | vector<int\>     | bitmask implementing object cuts of the top group |
| lep_type                  | vector<int\>     | number signifying the lepton type (e, mu, tau) of the lepton |
| lep_ptcone30              | vector<float\>   | ptcone30 isolation for the lepton |
| lep_etcone20              | vector<float\>   | etcone20 isolation for the lepton |
| lep_trackd0pvunbiased     | vector<float\>   | d0 of the track associated to the lepton at the point of closest approach (p.o.a.) |
| lep_tracksigd0pvunbiased  | vector<float\>   | d0 signifcance of the track associated to the lepton at the p.o.a. |
| met_et                    | float           | Transverse energy of the missing momentum vector |
| met_phi                   | float           | Azimuthal angle of the missing momentum vector |
| jet_n                     | int             | number of selected jets |
| jet_pt                    | vector<float\>   | transverse momentum of the jet |
| jet_eta                   | vector<float\>   | pseudorapidity of the jet |
| jet_phi                   | vector<float\>   | azimuthal angle of the jet |
| jet_E                     | vector<float\>   | energy of the jet |
| jet_m                     | vector<float\>   | invariant mass of the jet |
| jet_jvf                   | vector<float\>   | JetVertexFraction of the jet |
| jet_flag                  | vector<int\>     | bitmask implementing object cuts of the top group |
| jet_trueflav              | vector<int\>     | true flavor of the jet |
| jet_truthMatched          | vector<int\>     | information whether the jet matches a jet on truth level |
| jet_SV0                   | vector<float\>   | SV0 weight of the jet |
| jet_MV1                   | vector<float\>   | MV1 weight of the jet |
| scaleFactor_BTAG          | float           | scalefactor for btagging |
| scaleFactor_ELE           | float           | scalefactor for electron efficiency |
| scaleFactor_JVFSF         | float           | scalefactor for jet vertex fraction |
| scaleFactor_MUON          | float           | scalefactor for muon efficiency |
| scaleFactor_PILEUP        | float           | scalefactor for pileup reweighting |
| scaleFactor_TRIGGER       | float           | scalefactor for trigger |
| scaleFactor_ZVERTEX       | float           | scalefactor for z-vertex reweighting |
