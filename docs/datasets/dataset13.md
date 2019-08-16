Table 1: Proposed event, lepton, missing transverse momentum and jet variable content of a data dataset for educational
purposes. The content presented is a further slimmed down version of the ntuple produced by the HH -> bbtautau
version of the CxAODFramework.

| branchname          | type            | description                                                                  |
| ------------------  | --------------  | --------------------------------------------------------------------------   |
| runNumber           | int             | run identifier                                                               |
| eventNumber         | int             | event identifier                                                             |
| channelNumber       | int             | simulated data dataset ID e.g. WW ! `` 361600                             |
| mcWeight            | float           | weight of a simulated event |
| SF_PILEUP           | float           | scalefactor for pileup reweighting |
| SF_ELE              | float           | scalefactor for electron efficiency, only ,1 if electron selected & tagged |
| SF_MUON             | float           | scalefactor for muon efficiency, only ,1 if muon selected & tagged |
| SF_PHOTON           | float           | scalefactor for photon efficiency, only ,1 if photon selected & tagged |
| SF_TAU              | float           | scalefactor for tau efficiency, only ,1 if tau selected & tagged |
| SF_BTAG             | float           | scalefactor for b-tagging algorithm, only ,1 if b-jet selected & tagged |
| SF_LepTRIGGER       | float           | scalefactor for different operating efficiencies of used lepton triggers |
| SF_PhotonTRIGGER    | float           | scalefactor for different operating efficiencies of used photon triggers |
| SF_TauTRIGGER       | float           | scalefactor for different operating efficiencies of used tau triggers |
| SF_DiTauTRIGGER     | float           | scalefactor for different operating efficiencies of used ditau triggers |
| trigE               | bool            | boolean whether a standard trigger has fired in the egamma stream |
| trigM               | bool            | boolean whether a standard trigger has fired in the muon stream |
| trigP               | bool            | boolean whether a standard trigger has fired in the photon stream |
| trigT               | bool            | boolean whether a standard trigger has fired in the tau stream |
| trigDT              | bool            | boolean whether a standard trigger has fired in the ditau stream |
| lep_n               | int             | number of preselected leptons |
| lep_truthMatched    | vector<bool\>   | boolean indicating whether the lepton is matched to a simulated lepton |
| lep_trigMatched     | vector<bool\>    | boolean signifying whether the lepton is triggering the event |
| lep_pt              | vector<float\>   | transverse momentum of the lepton |
| lep_eta             | vector<float\>   | pseudo-rapidity of the lepton |
| lep_phi             | vector<float\>   | azimuthal angle of the lepton |
| lep_E               | vector<float\>   | energy of the lepton |
| lep_z0              | vector<float\>   | z-coordinate of the track associated to the lepton wrt. primary vertex |
| lep_charge          | vector<int\>     | charge of the lepton |
| lep_type            | vector<int\>     | number signifying the lepton type (e or ) |
| lep_isTightID       | vector<bool\>    | boolean indicating whether lepton satisfies tight ID reconstruction criteria |
| lep_ptcone30        | vector<float\>   | scalar sum of track pT in a cone of R=0.3 around lepton |
| lep_etcone20        | vector<float\>   | scalar sum of track ET in a cone of R=0.2 around lepton |
| lep_d0              | vector<float\>   | d0 of track associated to lepton at point of closest approach (p.o.a.)|
| lep_d0sig           | vector<float\>   | d0 significance of track associated to lepton at p.o.a. |
| met_et              | float            | transverse energy of the missing momentum vector |
| met_phi             | float            | azimuthal angle of the missing momentum vector |
| jet_n               | int              | number of preselected jets |
| jet_pt              | vector<float\>   | transverse momentum of the jet |
| jet_eta             | vector<float\>   | pseudo-rapidity of the jet |
| jet_phi             | vector<float\>   | azimuthal angle of the jet |
| jet_E               | vector<float\>   | energy of the jet |
| jet_jvt             | vector<float\>   | jet vertex tagging of the jet |
| jet_trueflav        | vector<int\>     | flavour of the simulated jet |
| jet_truthMatched    | vector<bool\>    | boolean indicating whether the jet is matched to a simulated jet |
| jet_MV2c10          | vector<float\>   | weight from algorithm based on Multi-Variate technique |


Table 2: Proposed photon, fatjet, hadronic tau truth information and systematics estimation variable content of a data
dataset for educational purposes. The content presented is a further slimmed down version of the ntuple produced by
the HH -> bbtautau version of the CxAODFramework


| branchname          | type               | description |
| ------------------- | -----------------  | ----------- |
| photon_n            | int                | number of preselected photons |
| photon_truthMatched | vector<bool\>      | boolean indicating whether the photon is matched to a simulated photon |
| photon_trigMatched  | vector<bool\>      | boolean signifying whether the photon is triggering the event |
| photon_pt           | vector<float\>     | transverse momentum of the photon |
| photon_eta          | vector<float\>     | pseudo-rapidity of the photon |
| photon_phi          | vector<float\>     | azimuthal angle of the photon |
| photon_E            | vector<float\>     | energy of the photon |
| photon_isTightID    | vector<bool\>      | boolean indicating whether photon satisfies tight ID reconstruction criteria |
| photon_ptcone30     | vector<float\>     | scalar sum of track pT in a cone of R=0.3 around photon |
| photon_etcone20     | vector<float\>     | scalar sum of track ET in a cone of R=0.2 around photon |
| photon_convType     | vector<int\>       | information whether and where the photon was converted |
| fatjet_n            | int                | number of preselected fatjets |
| fatjet_pt           | vector<float\>     | transverse momentum of the fatjet |
| fatjet_eta          | vector<float\>     | pseudo-rapidity of the fatjet |
| fatjet_phi          | vector<float\>     | azimuthal angle of the fatjet |
| fatjet_E            | vector<float\>     | energy of the fatjet |
| fatjet_m            | vector<float\>     | invariant mass of the fatjet |
| fatjet_truthMatched | vector<int\>       | information whether the fatjet is matched to a simulated fatjet |
| fatjet_D2           | vector<float\>     | weight from algorithm for W/Z boson tagging |
| fatjet_tau32        | vector<float\>     | weight from algorithm for top quark tagging |
| tau_n               | int                | number of preselected taus |
| tau_pt              | vector<float\>     | transverse momentum of the tau |
| tau_eta             | vector<float\>     | pseudo-rapidity of the tau |
| tau_phi             | vector<float\>     | azimuthal angle of the tau |
| tau_E               | vector<float\>     | energy of the tau |
| tau_isTightID       | vector<bool\>      | boolean indicating whether tau satisfies tight ID reconstruction criteria |
| tau_truthMatched    | vector<bool\>      | boolean indicating whether the tau is matched to a simulated tau |
| tau_trigMatched     | vector<bool\>      | boolean signifying whether the tau is triggering the event |
| tau_nTracks         | vector<int\>       | number of tracks in the tau decay |
| tau_BDTid           | vector<float\>     | Boosted Decision Tree identification number of the tau |
| ditau_m             | float              | mass of ditau system, from the Missing Mass Calculator |
| truth_pt            | vector<float\>     | transverse momentum of the simulated particle in t decay chain (t, W, b, lep, ) |
| truth_eta           | vector<float\>     | pseudo-rapidity of the simulated particle in t decay chain (t, W, b, lep, ) |
| truth_phi           | vector<float\>     | azimuthal angle of the simulated particle in t decay chain (t, W, b, lep, ) |
| truth_E             | vector<float\>     | energy of the simulated particle in t decay chain (t, W, b, lep, ) |
| truth_pdgid         | vector<int\>       | PDG ID number of the simulated particle in t decay chain (t, W, b, lep, ) |
| lep_pt_syst         | vector<float\>     | quadrature sum of systematic shifts that affect lep_pt, to provide an estimate |
| met_et_syst         | loat               | quadrature sum of systematic shifts that affect met_pt, to provide an estimate |
| jet_pt_syst         | vector<float\>     | quadrature sum of systematic shifts that affect jet_pt, to provide an estimate |
| photon_pt_syst      | vector<float\>     | quadrature sum of systematic shifts that affect photon_pt, to provide an estimate |
| fatjet_pt_syst      | vector<float\>     | quadrature sum of systematic shifts that affect fatjet_pt, to provide an estimate |
| tau_pt_syst         | vector<float\>     | quadrature sum of systematic shifts that affect tau_pt, to provide an estimate |
