# MsCaviar Simulation Scripts
In order to evaluate the performance of MsCAVIAR as compared with other methods, we performed a simulation study. 
In order to select realistic loci for fine-mapping, we identified regions in a trans-ethnic GWAS of rheumatoid arthritis \cite{ra_real_data} that contained peak SNPs with p-values of less than 0.0001 and contained ten or more SNPs in a 100kbp region centered around that peak. For each such locus, we used the 1000 Genomes project \cite{1000genomes} to generate LD matrices for the SNPs at that locus for both European and East Asian populations. Out of these loci, we selected one region with relatively low LD, where 20\% of the SNPs have LD equal to or higher than 0.5, and one region with relatively high LD, where 80\% of the SNPs have LD equal to or higher than 0.5 (Figure \ref{fig:equal}, LD matrices). These represent easier and more difficult scenarios, respectively, for fine mapping, since LD makes signals more difficult to distinguish. We pruned groups of SNPs that were in perfect LD in one or more of the populations, leaving one SNP for each. If a group of SNPs were in perfect LD in one population, but not the other, we retained the SNP with the highest Z-score in the other population in order to retain the most signal.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc