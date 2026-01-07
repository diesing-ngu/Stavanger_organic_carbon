## Spatial models of organic carbon stocks, carbon reactivity index and \delta ^13^ C in fjord sediments in Stavanger

### Overview

This is an R project to model and spatially predict organic carbon stocks, the carbon reactivity index ([Smeaton and Austin, 2022](https://doi.org/10.1029/2021GL097481)) and \delta^13^C of surface sediments in fjords in Stavanger municipality (SW Norway) by using a quantile regression forest ([Meinshausen, 2006](https://jmlr.org/papers/volume7/meinshausen06a/meinshausen06a.pdf)) framework.

Initially, the input dataset needs to be downloaded from Zenodo ([Diesing and Smeaton, 2026](https://doi.org/10.5281/zenodo.18172827)). This is achieved with download_data.Rmd in the folder 'input_data'. The three response variables organic carbon stocks, the carbon reactivity index and \delta ^13^ C are modelled and predicted separately by using the same overall workflow. Finally, the resulting predictions are used in an unsupervised classification (regionalisation).

### Licensing

<p xmlns:cc="http://creativecommons.org/ns#" >This work is licensed under <a href="https://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">CC BY-NC 4.0<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""></a></p>