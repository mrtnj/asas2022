
---
title: "Problematizing selection mapping from an animal science perspective"
subtitle: "Handout to a talk given at ASAS 2022"
author: "Martin Johnsson"
date: "2022-06-14"
output: pdf_document
bibliography: references.bib
---

# Introduction

Genomes cited as examples of the development of farm animal genomics: chicken [@hillier_sequence_2004], pig [@groenen_analyses_2012], cattle [@elsik_genome_2009]. SNP chips cited: cattle [@matukumalli_development_2009], pig [@ramos_design_2009], chicken [@groenen_development_2011].

@rubin_whole-genome_2010 performed a large scale, at the time, selection mapping study of domestic chickens. For a follow-up, see @qanbari_genetics_2019.

There are many other examples of selection mapping in domestic animals; some have identified known loci for mono- or oligogenic traits and large-effect loci for complex traits, e.g. @rubin_strong_2012 in pigs and @druet_identification_2013, @qanbari_classic_2014 and @freitas_genetic_2021 in cattle.

We published two population genetic studies on the feral chickens of Kauai, looking at population structure [@gering_mixed_2015] and selection mapping [@johnsson_feralisation_2016]. More is coming as Dom Wright, Eben Gering and their groups have continued working on feralisation.

The neural crest cell hypothesis for domestication entails that universal domestication traits are due to changes in the migration and proliferation of neural crest cells [@wilkins_domestication_2014]. Some selection mapping studies (e.g @pendleton_comparison_2018 in dogs and @wang_genomic_2018 in the farm fox selection experiment) have identified genes and pathways that they interpret as support for the neural crest cell hypothesis. See @johnsson_neural_2021 for a criticism along the lines of this talk.


# Population genetic limitations

## Selection mapping works best for recent selection

A simulation study shows how a linkage disequilibrium-based selection signatures are mostly erased within 0.1 $N_e$ generations [@przeworski_signature_2002]. The result that a neutral new mutation has an expected fixation time of $4 N_e$ is due to @kimura_average_1969.

@girdland_flink_establishing_2014 and @loog_inferring_2017 found that the _TSHR_ sweep (from @rubin_whole-genome_2010) happened around 500-1000 years ago, too recently to be selection during early domestication.


## Works best for simple architectures

Jain & Stephan analyzed a population polygenic model of adaptation after an environmental shift [@jain_modes_2017; @jain_rapid_2017], illustrating how adaptation can proceed either by small or large shifts in allele frequency, depending on the effect and mutation rates.


## Depends on genome features

@johri_recommendations_2022 discuss how features of the genome like mutation, recombination and historical natural selection, as well as population history, affects the ability to detect selection and ought to be modelled if we want to be certain that it is selection we detect.

An example is @hartfield_using_2021, who modelled population history in the Holstein breed, checking the ability of their chosen method (singleton density scores) to detect polygenic adaptation (and found it lacking).


# Practical concerns

## Researcher degrees of freedom

Examples of some of the selection mapping methods cited: $H_{12}$ [@garud_recent_2015], _EHH_ [@sabeti_detecting_2002], _iHS_ [@voight_map_2006], _hapFLK_ [@fariello_detecting_2013], singleton density score [@field_detection_2016].


## Annotation term enrichment

@wijesooriya_urgent_2022 recently discussed researcher degrees of freedom in annotation term enrichment.

@pavlidis_critical_2012 simulated neutral variants on the _Drosophila_ genome, took the tails of the distribution and found enriched annotation terms that one could spin hypothetical stories around.


## Finding the function of individual sweeps

Because the selected allele will likely be fixed or close to fixed, one needs some intercrossing or comparative strategies to perform genetic analysis [@johnsson_integrating_2018]. Examples of investigating the function of sweepp haplotypes in crosses of chickens: _BCO2_ [@fallahshahroudi_domestic_2019], _TSHR_ [@fallahshahroudi_effects_2021], _ADRA2C_ [@elfwing_strong_2014].


# Discussion

The Charlesworth quote is from @charlesworth_defence_2019.

# References
