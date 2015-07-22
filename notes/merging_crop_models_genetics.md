# Merging Crop Models and Genetics Notes

## Day 1

### Morning Session
The traits that we are interested in are quantitative. Vallejos discussing overview of challenge from a physiological perspective. Showing basic QTL mapping with overlapping distributions. This is a nice slide representation, main limitation of QTL from modeling perspective is a single endpoint. Dynamic traits in a single environment have a different problem (Penn State Collaborators have solved this).

Cultivar data --> phenotype --> crop model --> GSPs --> crop model

For the gene based crop sym, you can see the output of the model and the output of the phenotyping and see what the overlap is.

See Drawings in Notebook.

## Day 2
Overview of the basic genetic parameterization of the DSSAT model.

## Day 3 
Parameter estimation for genotype specific effects.

It appears that most of the models are parametrized step by step manually. There are better ways to do this in an automated ways. 

GSP- given genotype would give certain response for the genotype across environments.

There could be a number of parameter values for interacting parameters (e.g. leaf number and photosynthesis), that give the same output from the model (e.g pod size). This is called undefinability or equifinality. 

Now moving into Bayesian stats for parameter estimation for GSPs. Currently using bayesian methods to get an estimate of the mean. Parameter estimation using basic priors to constrain the estimates.

1. Generate vector of candidate parameter values (theta)
2. Simulate crop growth model with theta
3. Calculate the log-liklihood using the prior distribution and measured data
4. Calculate the acceptance/rejection ratio.
5. Sample u = updata theta according to: 

### HPC intro
50,000 cores at the UFL facility. 










