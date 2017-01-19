# research-software-decay-study
Code for a study of RCUK software outcomes to assess how long they stay maintained.

The aim of this study is to understand how long software which is developed and reported by RCUK funded projects continues to be maintained.

## Methodology

1. Use the [Gateway to Research API](http://gtr.rcuk.ac.uk/resources/GtR-2-API-v1.6.pdf) to download data on all projects which report software outcomes
2. Create a subset of this data which includes only those outcomes which include a URL to a Github repository
3. Identify if the Github repository still exists using the [Github v3 API](https://developer.github.com/v3/)
4. For those that exist, identify the length of time between the reported end date of the project and the last commit date in the repository

## Licensing

Data from Gateway to Research is public sector information licensed under the [Open Government Licence v2.0](public sector information licensed under the Open Government Licence v2.0) which allows adaptation and redistribution of the information.

Code developed as part of this study is being made available under the [3-Clause BSD License] (https://opensource.org/licenses/BSD-3-Clause)

## Acknowledgements

Neil Chue Hong was supported by the UK EPSRC, BBSRC and ESRC Grant EP/N006410/1 for the UK Software Sustainability Institute.

Simon Hettrick and Olivier Philippe conducted a previous study of ResearchFish outcomes which this work extends.
