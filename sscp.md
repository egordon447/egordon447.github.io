---
layout: single
title: ""
permalink: /data/sscp/
---

[← Back to Data](/data/)

# Small State Coverage Project (SSCP)

Small states and fully self-governing non-state territories are routinely excluded from the datasets political scientists and economists rely on, often because of arbitrary thresholds. In a review of 30 democratic transition studies, coverage ranged from 36% to 91% of the states that existed in each study’s time period, with a median of 73% (Gordon, 2024).

The Small State Coverage Project (SSCP) extends existing, widely-used datasets to these excluded polities. This is intended as a live project, and I add new datasets and polities as I need them in my own research. 

## Why this exists

My research focuses on small states and fully self-governing non-state territories as cases that are theoretically informative, often because conventional analyses tend to exclude them. SSCP is the infrastructure I've built to start the work of filling this gap, made available for others working on the same kinds of cases or who want to be more inclusive in their analyses.

## Scope

SSCP's coverage is defined by the case list used in my research on small state sovereignty (Gordon, 2024): 224 polities in the time period 1800-2026 (212 of which currently exist). For each dataset, a polity is either covered (already in the original source or added by SSCP), in scope but not yet covered, or out of scope for that particular source. Each dataset’s README lists the gaps and the reasons for them.


## What's included

| Dataset | Extends | Polities added | Version | DOI |
|---|---|---|---|---|
| Fractionalisation | Alesina et al. (2003) and RCS-Dem 2.0 | up to 38 | v1.0 | [10.7910/DVN/EVCQXC](https://doi.org/10.7910/DVN/EVCQXC) |
| Oil and Gas Wealth | Ross & Mahdavi (2015) | 39 | v1.0 | [10.7910/DVN/9PBISP](https://doi.org/10.7910/DVN/9PBISP) |
{% comment %} | Conflict | Correlates of War | [N] | v1.0 | |
| Contiguity | Gleditsch-Ward-style distance data | [N] | v1.0 | |
| Colonialism | [source] | [N] | v1.0 | | {% endcomment %}

Each dataset extension comes with its own README documenting construction method, exact coverage, variables, and known limitations. 

{% comment %} [Full coverage matrix, showing exactly which polities are covered by which dataset, coming soon.] {% endcomment %}

## Access and citation

SSCP is hosted on [Harvard Dataverse](https://dataverse.harvard.edu/dataverse/sscp).

Cite the project as a whole:

> Gordon, E. R. 2026. "Small State Coverage Project (SSCP): Extending Political Science and Economics Datasets to Small and Micro States." Harvard Dataverse. https://dataverse.harvard.edu/dataverse/sscp.

To cite a specific dataset:

> Gordon, E. R. 2026. "Small State Coverage Project (SSCP): Oil and Gas Wealth." v1.0. Harvard Dataverse. https://doi.org/10.7910/DVN/9PBISP.

## Research using SSCP

- Gordon, E. R. (2026). *Small democracies don't die: Population size and democratic breakdown.* Working paper, IPSA 2026 WiPS session. Uses fractionalisation and oil and gas wealth.
- Gordon, E. R. (2024). *Patterns of exclusion: Uncovering selection bias in the democratic transition literature.* Paper presented at the IPSA World Congress, 2024. Uses oil and gas wealth.


## References 
Alesina, A., Devleeschauwer, A., Easterly, W., Kurlat, S., & Wacziarg, R. (2003). "Fractionalization." Journal of Economic Growth, 8(2), 155-194. (Also circulated as NBER Working Paper No. 9411.)

Brown, D., & James, P. (2019). Religious characteristics of states dataset project – demographics v. 2.0 (RCS-Dem 2.0), countries only. https://doi.org/10.17605/OSF.IO/7SR4M

Gordon, E. R. (2024). Patterns of exclusion: Uncovering selection bias in the democratic transition literature
[Paper presented at the IPSA World Congress, 2024]

Ross, Michael L., and Paasha Mahdavi. (2015). "Oil and Gas Data, 1932-2014." Harvard Dataverse. https://doi.org/10.7910/DVN/ZTPW0Y.


## Reporting issues

SSCP is maintained on an ongoing basis. If you notice a state that should be covered but isn't, or spot an error, please contact me through [email](mailto:Emma.Gordon@gsi.uni-muenchen.de), using the [Harvard Dataverse contact form](https://dataverse.harvard.edu/dataverse/sscp), or through [GitHub](https://github.com/egordon447/sscp/issues).
