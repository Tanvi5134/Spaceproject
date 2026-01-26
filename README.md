ESTIMATION OF THE HUBBLE CONSTANT AND THE AGE OF UNIVERSE USING TYPE LA SUPERNOVAE DATA

The goal of this project was to esƟmate the Hubble constant (H₀) and the age of the universe using observational data from Type Ia Supernovae. The analysis was conducted using real data from the Pantheon+SH0ES dataset and involved
applying cosmological principles and fitting models within the flat ΛCDM framework.

Methodology
-Data Source: Pantheon+SH0ES.dat supernova dataset
-Extracted redshift (zHD) and distance modulus (MU_SH0ES)
-Used the ΛCDM model
-Fitted the model to the data using scipy.optimize.curve_fit
-Plotted redshift vs distance, residuals, and estimated cosmic parameters

Key Results
- Estimated Hubble Constant H0 = 72.66 km/s/Mpc
- EsƟmated Age of Universe = 12.35 Gyr
- Ωₘ(Matter density parameter) = 0.357
- Low-z H0 = 72.80 km/s/Mpc
- High-z H0 = 73.65 km/s/Mpc
- Residuals centred around 0, indicaƟng good model fit.
- Plot 2 (model fit overlay) was not included due to technical limitations, but model behaviour is reflected in results.

Inferences
 - The calculated H₀ is slightly higher than Planck18’s 67.4 km/s/Mpc, supporting late-time measurements (e.g., SH0ES).
- The universe is expanding, and the model fits the observaƟonal data well.
- The small difference in H₀ between low-z and high-z supports current debates around the Hubble tension.

Reflection
This project taught me how to handle real astrophysical data, apply scientific models, and draw conclusions from observed cosmic behaviour. I also gained experience in Python, curve fitting, and cosmological principles — and learned how science is used to uncover the structure and history of the universe.

Attachments
2_hubble parameter.ipynb (Jupyter notebook pdf)
2_Supernova_Cosmology_Handout.pdf (handout with answers)
Plots:
 Plot 1: Redshift vs Distance Modulus
 Plot 3: Residuals 
