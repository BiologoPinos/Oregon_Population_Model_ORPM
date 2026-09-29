# Oregon_Population_Model_ORPM

The Oregon Population Model (ORPM) is a spatially implicit, stage- and age-structured model of a shallow rocky-reef kelp forest ecosystem. The model explicitly represented the population dynamics of bull kelp (*Nereocystis luetkeana*), sea urchins (*Strongylocentrotus purpuratus* and *Mesocentrotus franciscanus*), and Dungeness crabs (*Metacarcinus magister*), and linked these species and their dynamics to a sea otter (*Enhydra lutris*) predation model.

This model was developed as part of **Andrés Pinos-Sánchez** MSc. thesis research at Oregon State University. We used this model to evaluate the potential effects of sea otter reintroduction and alternative management interventions on two primary response variables: kelp persistence and fishable Dungeness crab biomass density. Kelp persistence was the proportion of stochastic replicates that remained in a kelp-forest state through the duration of our simulated time period, whereas fishable crab biomass density was the biomass of male crabs old enough to be captured by our simulated fishery. All analyses were conducted in MATLAB R2025a (The MathWorks, Inc 2025).

- Scientific Publication: [insert link]
- Thesis Manuscript: [Modeling the effects of sea otter (Enhydra lutris) reintroduction and management strategies on bull kelp (Nereocystis luetkeana) persistence and the Dungeness crab (Metacarcinus magister) fishery](https://ir.library.oregonstate.edu/concern/graduate_thesis_or_dissertations/kd17d2904).

This mdoel works as a sister project/branch of a California trophic model developed by [Hopf et al., 2025](https://conbio.onlinelibrary.wiley.com/doi/10.1111/conl.13130). Hopf's original model (code) was designed to represent symilar dynamics to the ones presented here, but for a California, USA, giant kelp (Macrocystis pyrifera) system. Here we used the same language and sytax to Hopf et al.  

For detailed information about our ORPM model, equations, parameters, and assumptionss please refere to our [Supplementary_Document](insert link).

## Directory

- [Code](https://github.com/BiologoPinos/Oregon_Population_Model_ORPM/tree/ORPM_Thesis_Final/Code) - All scripts and subdirectories for the model.
  - *ORTM_model_otter.m* - Master code.
  - *ORTM_plotting.m* - Plotting fucntions.
- [Model Inputs](https://github.com/BiologoPinos/Oregon_Population_Model_ORPM/tree/ORPM_Thesis_Final/Code/Model%20inputs) - Sea Otter timeseries from [ORSO](https://www.elakhaalliance.org/wp-content/uploads/2023/03/AppenA-RestoreOtterstoOR-digital.pdf).
- [Model Outputs](https://github.com/BiologoPinos/Oregon_Population_Model_ORPM/tree/ORPM_Thesis_Final/Code/Model%20outputs) - Model results.
- [Data & Data_Exploration](https://github.com/BiologoPinos/Oregon_Population_Model_ORPM/tree/ORPM_Thesis_Final/Code/data%20%26%20data_exploration) - Supplementary data.
- [Functions](https://github.com/BiologoPinos/Oregon_Population_Model_ORPM/tree/ORPM_Thesis_Final/Code/functions) - Code + Equations that run the model.


## Authors

Andrés Pinos-Sánchez; https://orcid.org/0000-0002-8292-3575

Jess K. Hopf; https://orcid.org/0000-0003-2207-2366

Leif K. Rasmuson; https://orcid.org/0000-0001-7685-2427

Mark Novak; https://orcid.org/0000-0002-7881-4253

J. Wilson White; https://orcid.org/0000-0003-3242-2454


## Citation

### Scientific Article
Insert citation to paper

### MSc. Thesis
Pinos-Sánchez, Andrés. 2026. “Modeling the effects of sea otter (*Enhydra lutris*) reintroduction and management strategies on bull kelp (*Nereocystis luetkeana*) persistence and the Dungeness crab (*Metacarcinus magister*) fishery.” Oregon State University.


## Funding

This work was supported by the Oregon Ocean Science Trust (project #5: HB5202) and the California Ocean Protection Council (agreement C0874012). Andrés Pinos-Sánchez was also supported by the H. Richard Carlson Scholarship


## Warranty 
All code is provided "as it" and without warranty


## Summary Views

### Process Model Illustration
<img width="9590" height="4653" alt="ORPM_Full_Moddel" src="https://github.com/user-attachments/assets/a832b2cb-c4fc-4e53-88ff-972e5b5d55d9" />

### Kelp Persistence (continuous)
<img width="3168" height="2681" alt="Kelp_Persistense_Results2" src="https://github.com/user-attachments/assets/d1f7aacc-71dc-482b-923a-3ac57e022468" />

### Kelp Persistence (periodic)
<img width="3160" height="2681" alt="Kelp_Persistense_Periodic_Results2" src="https://github.com/user-attachments/assets/be7b7f6f-0494-4b5b-86d2-b94086b9fab8" />

### Fishable Crab Densities
<img width="3146" height="1835" alt="Crab_Fishable_Densities" src="https://github.com/user-attachments/assets/413784a1-ba45-4282-a2ed-99f51381bd6b" />
