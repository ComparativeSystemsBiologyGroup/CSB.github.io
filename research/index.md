---
title: Comparative Systems Biology Lab  Lab
layout: default
group: research
---

<div class="row">

# What's comparative or evolutionary systems biology
Comparative genomics is fundamental to guide experiments and provides tools for functional infor-mation transfer across genomes. Performing similar set of experiments on the same biological systemin different organisms, will enable the reconstruction of the corresponding networks of regulations.However, it is hard to imagine that we will be able to elucidate how the system evolved without adetailed understanding of its dynamical properties: evolution selects genetic circuits on the basis oftheir activity: in general, we may say that evolution selects a system’s arrangement on the basis ofthe input/output response with additional features also important, such as the robustness to changesin physical or biological conditions. Mathematical modelling of ”orthologous” biological systems indifferent organisms can provide information about how arrangement variations affect evolutionarymeaningful properties of the circuit, a mission that is almost impossible for static reconstructions.Modelling could for instance show how the often-redundant regulations of functionally important regulators affect the dynamic properties of the system. A natural question is how the different regulatoryschemes working in related species affect the dynamical properties of the system, to extrapolate im-portant evolutionary insights on the selective pressures that might have shaped the system. Are thealternative arrangements all similarly robust with respect to evolutionary or environmental variations?Can we understand which evolutionary changes are responsible for optimizing such robustness? Whatspecific property follows a particular arrangement? By integrating different sources of information intomeaningful mathematical models, we can study the dynamics of a system at a detail level impossibleto achieve through wet-lab experiments. That is, redundant, reduced or simply different regulations characterizing different organisms can be traced through experiment and comparative genomics, butunderstanding their effects on the properties of the system can best be achieved through dynamic models. While the study of a single model allows to understand its specific properties, it does notprovide understanding about the evolution of a system’s structure. We propose an approach that wecall Comparative Systems Biology, whose aim is to introduce evolutionary thinking in modelling approaches through the comparison of the reconstructions of “orthologous” systems in different species. Clearly we are working on many different issues, but this is where we would like to go! 

(PDF) Manifest of the Comparative Systems Biology Unit. Available from: https://www.researchgate.net/publication/333748732_Manifest_of_the_Comparative_Systems_Biology_Unit [accessed Mar 13 2023].

</div>

<div class="row">

### DNA replication provides a selective force for directing genome rearrangements toward the formation of operons

<div class="col-md-7 order-md-1">

Metabolic Control Analysis studies showed that non-coordinated variations in enzyme concentrations can perturb fluxes and metabolite pools. Here, we focused on the integration of these concepts with the effect of DNA replication on transcripts abundance and how this may play a pivotal role for metabolic operon formation.
DNA replication is nowadays considered as a global regulator of gene expression that overlap to classical transcriptional regulation in Bacteria. In certain species, copy number (CN) variations are wide and correlated with growth rate; fast growing E. coli cells can for instance harbor up to 10 active replication forks. This translates in differences of genes’ CN accordingly to their genomic position which can lead to dramatic stoichiometric differences of their transcripts. Our theoretical treatment shows that CN can translate into perturbations of metabolite homeostasis which can be minimized by reducing the difference in CNs of functionally related genes. This can be achieved by the evolutionary calibration of gene position along the chromosome, or promoter parameters. Our simulations with a realistic metabolic system demonstrated that gene clustering is a more effective stategy in Bacteria. A prediction of our hypothesis is that species where the CNs varies over a wider range, should have tighter gene organization, which we confirmed by means of comparative genomics analysis.
In this work we identified a plausible selective force for clustering related genes into operons; this force is moreover able to select for intermediate steps thus providing a drive to the progressive formation of gene clusters during evolution.


</div>

<div class="row">

### Modelling the effects of DNA replication on transcript abundance

<div class="col-md-7 order-md-2">

While in mono-ploid species DNA replication can at most double a locus’ copy number (CN), fast-growing species like E. coli can have a steeper positional bias in CNs consequent to the presence of multiple active replication forks per cell. Since in Bacteria a locus can be expressed just after its replication, CN affects the abundance of transcripts. In this work we integrated models describing the genomic position- and division time-dependent CN variations of loci (Bremer & Churchward, 1977) into classical transcription regulation systems, to study their interactions. Results indicate that thanks to replication, the sensitivity of transcript abundance to the abundance of the regulator gains a positional pattern, with origin-proximal loci being more responsive and with an increased dynamic range of transcription rates. 
The variance of transcript abundance is a combination of the variance of CNs, the variance of the transcription rate and their covariance. The latter is evolutionary interesting, because depending on its sign may amplify or demote the transcriptional regulator activity. By simulating the system over the range of possible covariances, we add that the input/output relations in the system become richer. 
In summary, our work shows that the presence of replication introduces an extra-dimension in transcriptional regulation, reinforcing its role as a global regulator of gene expression, in addition to supercoiling. Additional approaches that may benefit from our work concern variance estimation in differential gene expression analysis, the estimation of promoter kinetic parameters using gene expression data and gene regulatory network reconstruction.

</div>

<div class="col-md-5 order-md-1 align-self-center">
<img class="img-fluid" src="static/img/pub/gemo23.png" alt="Sensitivities">
</div>
</div>
<div class="row">

### 

<div class="col-md-7 order-md-1 ">

Active DNA replication of circular genomes in prokaryotes produces a gradient of copy number of loci that decreases toward the terminus, an effect particularly evident in mero-oligoploid species. Several genomic asymmetries unfold over the ori/ter axis, such as GC skew, the orientation of coding sequences, abundance of phages, mutation rate, highlighting that the fundamental role of replication goes well beyond the mere copying of the genome and impacts on multiple genome features. On the other hand, the mechanistic basis for those patterns is still under debate.  Here we show that active DNA replication enables bacterial species to lower the fitness threshold under which an allele is practically neutral; this is achieved by its role as a multiplier of the probability of fixation of an allele in the population thus providing a simple and elegant solution to several unexplained genomic patterns observed since long, like an increased mutation rate toward the terminus. Additionally, by introducing DNA replication in simple graph models we highlight its role as a device for generating genomic variations. More in detail, the translocation of a gene in an actively copied chromosome, results in chromosomes with different events for the gene (translocation, duplication or deletion). 


</div>

<div class="col-md-3 order-md-2 align-self-center">

<img class="img-fluid" src="static/img/pub/replication_and_translocations_fig1.png" alt="Translocations">
</div>
</div>

