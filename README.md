# Cpu Optimized Google Cloud

## Files

- design.csv: the parameters for all of the individual jobs in the experiments
- Run[hybrid|normal|optimized].ipynb: used for running the Spark experiments on Google Cloud
- Export.ipynb: used for exporting the logs to results.csv and analyzing it
- results.csv: the results of running the first experiments
- Anova-project.ipynb: used for running ANOVA analysis on the results
- design-withoptimization.csv: the scheduled jobs for running the optimized experiment
- plotting.ipynb: used for visualizing the results.csv data
- decider.ipynb: used to predict the best configurations to run a job on 
