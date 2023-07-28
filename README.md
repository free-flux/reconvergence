# reconvergence
Raw data, notebooks and plots accompanying the article ``*Does Reflective Equilibrium Help Us Converge?*''

## Contents
- **[data](data)**
  - [data_full_spectrum_convergence_rand_ex_all_configs.csv.tar.gz](data/data_full_spectrum_convergence_rand_ex_all_configs.csv.tar.gz)
      - 30 randomly generated dialectical structures with sentence pool size 7
      - 2186 sets of initial commitments (full spectrum)
      - 5 configuration of weights
      - Total number of simulation setups: 327900
  - [data_two_point_convergence_binned_sp_7_all_configs.csv.tar.gz](data/data_two_point_convergence_binned_sp_7_all_configs.csv.tar.gz)
      - 13000 randomly generated dialectical structures with sentence pool size 7
      - 2 sets of initial commitments per structure
      - 5 configuration of weights
      - Total number of simulation setups: 130000
  - [weightings_ensemble.csv.tar.gz](data/weightings_ensemble.csv.tar.gz)
      - 10 randomly generated dialectical structures with sentence pool size 7
      - 100 sets of initial commitments per structure
      - 276 configuration of weights
      - Total number of simulation setups: 276000
- **[plots](plots)**: Various figures resulting from the analysis of simulation results.
- **Notebooks**
  - [convergence_data_generation.ipynb](convergence_data_generation.ipynb): setting up and running simulations with modules `tau` and `rethon`
  - [convergence_data_preprocessing.ipynb](convergence_data_preprocessing.ipynb): preprocessing raw data by additional calculations for compatibility and similarity
  - [two_point_convergence_exploration.ipynb](two_point_convergence_exploration.ipynb): analysing the two-point ensemble (unique outputs, compatibility, similarity) and creating plots
  - [full_spectrum_exploration.ipynb](full_spectrum_exploration.ipynb): analysing the full-spectrum ensemble ("anything goes") and creating plots
  - [weightings_selection.ipynb](weightings_selection.ipynb): selecting promising weight configuration for simulations and creating plots
