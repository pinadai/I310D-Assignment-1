# I310D-Assignment-1
## Assignment 1: Data Collection & Curation

### Goal of this project:

To determine the median life expectancies of animals in North American zoos and aquariums, as well as gauge in which age range the death of zoo/aquarium animals is most common. To attempt to execute best practices for scientific research in designing and implementing. To make my findings fully reproducible by others.

### Links to any relevant API documentation:

Not applicable. Publicly accessible dataset from https://data.world/animals/zoo-animal-lifespans was used. 

### License of data:

https://github.com/pinadai/I310D-Assignment-1/blob/main/LICENSE

MIT License

Copyright (c) 2022 pinadai

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

### Source data:

https://data.world/animals/zoo-animal-lifespans - dataset from data.world. 

Data citation from data.world: Che-Castaldo, J. P., Byrne, A., Perišin, K., & Faust, L. J. figshare https://doi.org/10.6084/m9.figshare.7539968 (2018)

Click [here](https://docs.google.com/spreadsheets/d/1Y7SFJJlGVhCN7JYyhqADmDtbPLFaFSgSElvBwlrpe0A/edit?usp=sharing) to see source data file.

### Data type and description for each attribute in the data:

**Species Common Name** <class 'str'>: Common species name of vertebrate animal in North American zoo and/or aquarium

**Scientific Name** <class 'str'>: Scientific species name of vertebrate animal in North American zoo and/or aquarium 

**Taxon Class** <class 'str'>: Describes which vertebrate taxa the species resides in

**Overall Sample Size** <class 'numpy.float64'>: Total recorded number of animals in that specific species

**Overall MLE**  <class 'numpy.float64'>: Overall median life expectancy of that specific species

**Male Sample Size** <class 'numpy.float64'>: Total number of male-classified animals for that specific species

**Male MLE** <class 'numpy.float64'>: Median life expectancy for male animals in a specifc species

**Female Sample Size** <class 'numpy.float64'>: Total number of female-classified animals for that specific species 

**Female MLE** <class 'numpy.float64'>: Median life expectancy for female animals in a specific species

### Any known issues or potential issues:

- The specific North American zoos & aquariums were not thoroughly specified by the source data description. Zoos and aquariums could have different policies on life expectancy situations, and since North America includes the United States and Canada, more detailed information about this could've been useful.
- Not completely sure how this data was collected and buy whom. Collectors of the source data could've been biased on what information they chose to include in this dataset. 




    
    
