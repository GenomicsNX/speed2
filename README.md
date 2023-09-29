This repository hosts an R-package for signaling pathway enrichment analysis and pathway signatures derived from a large number of manually curated pathway perturbation experiments across many different cell types in human cells. Genes are scored based on causal influences of pathway perturbations as opposed to pathway memberships. Here you can perform an enrichment analysis on a list of human genes against the SPEED2 gene signature database.

Install using: 

```r
library(devtools)
install_github("molsysbio/speed2")
library(speed2)
```

For usage, see:

```r
vignette("speed2")
```

https://speed2.sys-bio.net/index.html

