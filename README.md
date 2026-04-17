Generates and analyzes data for the universal statistical topography.

Core Dependencies:
    - numpy, pandas, matplotlib, seaborn, scipy, sklearn, gplearn
    - joblib, tqdm; for optimization efficiency
    - hdim_opt (depends on numpy, scipy); for QUASAR optimization, Lorentzian KDE, isotropization
 
Relevant Notes:
- All function definitions are in the first few cells; code execution in the following cells. Each section is titled for clarity.
- Optimization cell defaults to a lower 'n_points'/'popsize'/'maxiter' block for testing; can uncomment top hyperparameter block for full reproducibility.
  - If analyzing test optimization data, ensure the KDE read_csv points to 'spacetime_histories_test' (line 15).
- plot_resolution = 'high' saves high-res plots; 'low' for a quick analysis
