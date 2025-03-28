The cross sections for difermion production via VBF at 10 Tev muon colliders, up to the linear order in SMEFT Wilson coefficients (quadratic terms for cHq is also included).
The dim-6 SMEFT operators considered are: 

$O_{Hq}  = i \left(H^\dagger \overset{\leftrightarrow}{D}_\mu H \right)\left(\bar{q}_L\gamma^\mu q_L\right)$
  
$O_{Hq}' = i \left(H^\dagger \sigma^a\overset{\leftrightarrow}{D}_\mu H\right) \left(\bar{q}_L\sigma^a\gamma^\mu q_L\right)$
  
$O_{Hu}  = i \left(H^\dagger \overset{\leftrightarrow}{D}_\mu H \right)\left(\bar{u}_R\gamma^\mu u_R\right)$
  
$O_{Hd}  = i \left(H^\dagger \overset{\leftrightarrow}{D}_\mu H \right)\left(\bar{d}_R\gamma^\mu d_R\right)$
  
$O_{H\ell}  = i \left(H^\dagger \overset{\leftrightarrow}{D}_\mu H \right)\left(\bar{\ell}_L\gamma^\mu \ell_L\right)$
  
$O_{H\ell}' = i \left(H^\dagger \sigma^a\overset{\leftrightarrow}{D}_\mu H\right) \left(\bar{\ell}_L\sigma^a\gamma^\mu \ell_L\right)$
  
$O_{He}  = i \left(H^\dagger \overset{\leftrightarrow}{D}_\mu H \right)\left(\bar{e}_R\gamma^\mu e_R\right)$
  
$O_{uH}  = H^\dagger H \bar{q}_L \tilde{H} q_R$
  
$O_{uW}  = (\bar{q} \sigma^{\mu\nu} u) \sigma^i \tilde{H} W^i_{\mu\nu}$
  
$O_{uB}  = (\bar{q} \sigma^{\mu\nu} u) \tilde{H} B_{\mu\nu}$
  
---------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------
calc_xsec_qq compute cross sections (in unit of fb) for qq final states, with arguments:

     i_channel (0-5) specify the final state flavors: 0 - uu,  1 - dd,  2 - ud,  3 - tt,  4 - bb,  5 - tb
     
     i_mqq (0-6) specify the qq invariant mass: 0 - [150, 300],  1 - [300, 500],  2 - [500, 900],  3 - [900, 1600],  4 - [1600, 2800],  5 - [2800, 5000],  6 - [5000, infinity]
     
     i_ptll (0-5) specify the transverse momentum of the qq system: 0 - [20, 60],  1 - [60, 100],  2 - [100, 140],  3 - [140, 200],  4 - [200, 400],  5 - [400, inf]  
     
     cHq, cpHq, cHu, cHd, cuH, cuW, cuB are the corresponding Wilson coefficients for the SMEFT operators OHq, O'Hq, OHu, OHd, OuH, OuW, OuB.
     
     LambdaEFT is the SMEFT cutoff scale in unit of TeV.

     Kinematic cuts are:
        p_{T,j} > 100 GeV
        10^\circ < \theta_j < 170^\circ
        m_{\rm miss} > 200 GeV
---------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------
calc_xsec_qqh compute cross sections (in unit of fb) for qqh final states, with arguments:

     i_channel (0-5) specify the final state flavors: 0 - uu,  1 - dd,  2 - ud,  3 - tt,  4 - bb,  5 - tb
     
     i_mqq (0-0) specify the qqh invariant mass: 0 - [150, inf]
     
     i_ptll (0-0) specify the transverse momentum of the qqh system: 0 - [20, inf]
     
     cHq, cpHq, cHu, cHd, cuH, cuW, cuB are the corresponding Wilson coefficients for the SMEFT operators OHq, O'Hq, OHu, OHd, OuH, OuW, OuB.
     
     LambdaEFT is the SMEFT cutoff scale in unit of TeV.

     Kinematic cuts are:
        p_{T,j} > 100 GeV
        10^\circ < \theta_j < 170^\circ
        m_{jj} > 150 GeV
        m_{\rm miss} > 200 GeV
---------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------
calc_xsec_ee compute cross sections (in unit of fb) for ee or tautau final states, with arguments:
     i_channel (0-1) specify the final state flavors: 0 - ee,  1 - tautau
     
     i_mqq (0-6) specify the ee or tautau invariant mass: 0 - [150, 300],  1 - [300, 500],  2 - [500, 900],  3 - [900, 1600],  4 - [1600, 2800],  5 - [2800, 5000],  6 - [5000, infinity]
     
     i_ptll (0-5) specify the transverse momentum of the ee or tautau system: 0 - [20, 60],  1 - [60, 100],  2 - [100, 140],  3 - [140, 200],  4 - [200, 400],  5 - [400, inf]  
     
     cHl, cpHl, cHe are the corresponding Wilson coefficients for the SMEFT operators OHl, O'Hl, OHe
     
     LambdaEFT is the SMEFT cutoff scale in unit of TeV.

     Kinematic cuts are:
        p_{T,e} > 100 GeV    p_{T,\tau} > 100 GeV
        10^\circ < \theta_e < 170^\circ     10^\circ < \theta_\tau < 170^\circ
        m_{\rm miss} > 200 GeV
---------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------
calc_xsec_eeh compute cross sections (in unit of fb) for eeh or tautauh final states, with arguments:

     i_channel (0-1) specify the final state flavors: 0 - ee,  1 - tautau
     
     i_mqq (0-0) specify the eeh or tautauh invariant mass: 0 - [150, inf]
     
     i_ptll (0-0) specify the transverse momentum of the eeh or tautauh system: 0 - [20, inf]
     
     cHl, cpHl, cHe are the corresponding Wilson coefficients for the SMEFT operators OHl, O'Hl, OHe
     
     LambdaEFT is the SMEFT cutoff scale in unit of TeV.

     Kinematic cuts are:
        p_{T,e} > 100 GeV    p_{T,\tau} > 100 GeV
        10^\circ < \theta_e < 170^\circ     10^\circ < \theta_\tau < 170^\circ
        m_{ee} > 150 GeV     m_{\tau\tau} > 150 GeV
        m_{\rm miss} > 200 GeV

---------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------

The cross sections for Higgs pair production via VBF at 10 Tev muon colliders, up to the linear order in SMEFT Wilson coefficients.

The Higgs are assumed to decay into bb with fixed branching fraction 0.58.

The dim-6 SMEFT operators considered are:

$O_H  = \left(H^\dagger H\right)^3$

$O_{H\Box} = \left(H^\dagger H\right)\Box \left(H^\dagger H\right)$
  
$O_{HD}  = \left(D^\mu H^\dagger H\right) \left(H^\dagger D_\mu H\right)$

$O_{HW}  = \left(H^\dagger H\right) W^i_{\mu\nu} W^{i\mu\nu}$
  
$O_{HB}  = \left(H^\dagger H\right) B_{\mu\nu} B^{\mu\nu}$
  
$O_{HWB} = \left(H^\dagger \sigma^i H\right) W^i_{\mu\nu} B^{\mu\nu}$
  
---------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------
calc_xsec_hh compute cross sections (in unit of fb) for hh final states via VBF, with arguments:

     i_channel (0-5) specify the final state: 0 - WW fusion to vvhh,  1 - ZZ fusion to mumuhh with at least one eta_mu < 6
     
     i_mhh (0-5) specify the hh invariant mass: 0 - [0, 400],  1 - [400, 700],  2 - [700, 1130],  3 - [1130, 2500],  4 - [2500, 5000],  5 - [5000, infinity]
     
     i_pth (0-5) specify the transverse momentum of the softer Higgs: 0 - [0, 100],  1 - [100, 300],  2 - [300, 500],  3 - [500, 700],  4 - [700, 1000],  5 - [1000, inf]
     
     cH, cHbox, cHD, cHW, cHB, cHWB are the corresponding Wilson coefficients for the SMEFT operators OH, OHbox, OHD, OHW, OHB, OHWB
     
     LambdaEFT is the SMEFT cutoff scale in unit of TeV.

     Kinematic cuts are:
        p_{T,b} > 10 GeV
        10^\circ < \theta_b < 170^\circ
