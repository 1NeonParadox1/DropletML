# DropletML

Predicting droplet impact dynamics using machine learning.
# DATASET
This dataset contains 1498 datapoints from experimental investigations of droplet impact, spreading, and rebound on superhydrophobic laser-textured surfaces. Data was collected for twelve surface types featuring square grids of laser-made channels with spacings ranging from 50 μm to 800 μm, with either deep or shallow channels. Droplet impact tests were conducted using water and water-glycerol mixtures at droplet viscosity up to 160 mPa∙s, with high-speed imaging at 5000 fps. Extracted parameters include maximum spreading factor, contact time, rebound efficiency, and maximum lamella velocity, alongside key droplet properties such as diameter, velocity, density, surface tension, viscosity, Weber number, and Reynolds number. A supplementary dataset provides analogous data for impacts on a smooth hydrophobic surface (125 further datapoints), mimicking the regions between the laser-made channels. Additionally, scanning electron microscopy images of all surfaces and both static and dynamic contact angle measurements are included. The data was collected between April and December 2024 at the Faculty of Mechanical Engineering, University of Ljubljana, Slovenia. Data on fabrication of surfaces, testing procedures and data reduction is provided in the dataset description file.

The dataset is valuable for research of surface wetting, surface engineering, droplet impacts and for anti-icing applications. It can aid in validating theoretical and numerical models of droplet dynamics, optimizing superhydrophobic surfaces for self-cleaning and drag reduction, and developing machine learning models for droplet impact prediction. The data is particularly relevant for designing anti-icing surfaces by minimizing contact time and maximizing the rebound efficiency, with further applications in 3D printing, coating technologies, and inkjet printing.

Institutions - Univerza v Ljubljani Fakulteta za strojnistvo
Published: 16 March 2025

## Roadmap
- v0.1: Dataset exploration and baseline Linear Regression
- v0.2: Decision Tree, Random Forest, XGBoost
- v0.3: Physics-based feature engineering
- v0.4: Model explainability (SHAP)
- v0.5: Streamlit application
