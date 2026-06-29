# Aus_mussels

This is a coding directory to go through the process of analyzing whole genome sequencing, Australian mussel data. Here is a breif abstract for the project at it's current stage (30 June 2026):

Hybrid zones are powerful systems to study the evolutionary forces that shape natural populations. The warm-adapted Mediterranean mussel Mytilus galloprovincialis was introduced to Southeastern Australia where it hybridizes with the cool-adapted native Australian mussel Mytilus planulatus. In sampled regions with distinct hybrid groups, hybridization occurs along a thermal gradient, where mussels in the warmer northern waters have higher genomic proportions of M. galloprovincialis and mussels in the cooler southern regions have higher genomic proportions of M. planulatus. To test the hypothesis that selection favoring warm-adapted M. galloprovincialis ancestry shapes geographic patterns of genetic diversity, wße conducted a single generation larval selection experiment in hybrids. Using a split-brood design, we reared three families in two treatments: one that reflects contemporary temperature conditions (control) and one that reflects future warming climate projections (warm). Larval mussels were reared for 19 days, and genomic samples were taken on Days 1, 10, and 19 to coincide with key developmental stages. We calculated pairwise comparisons between genomes of mussel larvae raised at control and warm temperatures and at distinct mussel life stages. Genomic comparisons of hybrid larvae raised at control vs. warm temperatures will give insight into how M. galloprovincialis and M. planulatus genomes may interact in the context of projected future thermal challenges. Furthermore, identifying genomic regions associated with asymmetric introgression will reveal the genetic architecture underlying thermal adaptation, elucidating candidate genes important for hybrid survival and improving our understanding of how organisms adapt to warmer temperatures.

Here is the repository structure for my HPC Code:
-aus_mussels/
  -data/
    -cram/
    -dedup/
    -mapped/
    -quality_reports/
    -reference/
    -trimmed/
    -variants/
  -scripts/

Additionally, troubleshooting and justification steps can be found in code_notebook.Rmd. 

Authors: Emily Dombrowski, Samantha Howitt, Alex Berry, Craig Sherman, Cynthia Riginos, Brent Lockwood
Funding sources: 
* National Science Foundation, Graduate Research Fellowship
* Australian Research Council Grant, "Some Like it Hot"
