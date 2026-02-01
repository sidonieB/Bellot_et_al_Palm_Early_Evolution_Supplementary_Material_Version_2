## Scripts used to run the "younger ages" analysis

mcmc_RUN.Rev: main script that runs the analysis, using the model* scripts and the topological constraints set up in setup_constraints.Rev  
model_CLOCK.Rev: molecular clock model settings  
model_FBDP.Rev: FBD model settings  
model_NSUB.Rev: nucleotide substitution model settings  
setup_constraints.Rev: topological constraints on the placement of extant and fossil taxa  
summarize.Rev: separate script to run after the analysis to summarise the posterior distribution into a maximum clade credibility tree  
