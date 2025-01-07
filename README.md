# VIX_LHeston
Implementation of pricing VIX term structure under SV models (INCOMPLETE version)

## Description of each file

  - utils: functions to compute model-based VIX term structure under LHeston;
  
  - estimation_LHeston-2011: details of parameter estimation for LHeston model using VIX term structure data for the whole period;

## What we do
  - Derived a analytical formula of VIX under LHeston model, which can be seen as an analytical approximation for pricing VIX under rHeston model (the formula isAn verified through degenerated cases and Monte Carlo simulation);
  - Conducted an empirical analysis of the pricing performance of the VIX term structure for several commonly used continuous-time stochastic volatility models, including Heston, Bates, SVCJ, and LHeston.
