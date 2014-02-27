#SnowyOwl

**SnowyOwl** is a gene prediction pipeline that uses RNA-Seq data to train and provide hints for the generation of Hidden Markov Model (HMM)-based gene predictions, and to evaluate the resulting models. The pipeline has been validated and streamlined by comparing its predictions to manually curated gene models in three fungal genomes, and its results show substantial increases in sensitivity and selectivity over previous gene predictions. Sensitivity is gained by repeatedly running the HMM gene predictor Augustus with varied input parameters, and selectivity by choosing the models with best homology to known proteins and best agreement to the RNA-Seq data. **SnowyOwl** has successfully predicted genes in 26 novel fungal genomes.
The pipeline can be installed locally for high throughput and control over configuration. It can also be run on a remote server through a convenient web interface for occasional use.

###Features

- Gene prediction using RNA-Seq data
- High sensitivity and specificity
- Pipeline streamlined and validated with manually curated gene models
- Highly configurable
- Default configuration for ascomycete and basidiomycete fungi
- Install and run locally for control and flexibility
- Run remotely through a web interface for convenience

**SnowyOwl** is available [here](http://sourceforge.net/projects/snowyowl/)
