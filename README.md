Here are 3 different ways to create a synthetic dataset.  
1st.  This is a VAE and it models the residuals from slopes and intercepts and adds this noise back into the VAE's mean estimates.  This helps keep the within correlation in the synthetic 
dataset similar to the real one.
2nd This attempts to model the dependencies over time directly with a Joint VAE.  
3rd.  This uses a python package CPAR which generates synthetic data through conditional neural networks.  
Results are similar across synthetic generation.  
However when assessing if inferences hold up, the 1st method does the best on the Corsano Dataset.
