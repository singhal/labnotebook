## Thoughts 
1. Lower diversity in lower recombination areas could be for two reasons
	- recombination is mutagenic
	- purifying selection (background selection) and directional selection (selective sweep) work on longer haplotypes, and therefore, reduce diversity along a wider swath
	- do we discuss both?
2. Broad scale patterns are similar; this is commonly known to be true. But, what does it mean, if anything, when fine-scale patterns of recombination are similar?
3. recombination is all about access to the genome. PRDM9 pries the genome open to give access. In species without PRDM9, look for other areas of access. PRDM9 evolves quickly, so recombination evolves quickly in species with it. In species without, more stable.
	- but why then does recombination appear to change so quickly across very syntenic bird genomes? inversions?
4. could PAR recombination patterns be less compelling because sex-averaged?
5. Need to mention that our results are sex-averaged, in general, and reference Backstrom et al map for any sense of how the two sexes might differ, if at all.
6. What do we want to say about inversions, if anything?
7. How do we talk about these hotspots persisting? The nature of these hotspots is changing because the GC* results suggest their base composition is changing. Yet, our comparative results suggest that we still have tons of shared hotspots. So, would this make it unlikely that there is a locally-based sequence based trigger for hotspots? Unless the trigger is GC/CpG content itself? 
	- But then why the weird MEME motif results?
8. Interesting that what triggers DSB is conserved across species although the mechanism of how that trigger is set varies. Somehow seems to go against notions of how one would expect mechanisms to be conserved.
9. I wonder if poly / divergence in coldspots vs. unique hotspots vs. shared hotspots vs. rest of the genome is the same?
10. Have our hotspots reached GC-content equilibrium? Or are they still becoming more GC-rich?
11. any worth in trying to see if a linear model has any predictive power of recombination rates in this system? (GC content, repeats, TSS, SNP density, divergence, telomere distance)
12. Report proportion of recombination in sequence in a way that allows us to understand how peaky recombination is?
	- why do other papers always assume this is because of hotspots and not because of heterogeneity along the chromosome?
13. When recombination is so heteregenous across the chromosome, and it has such a big impact on genome content & diversity, what does this mean?
14. We really have no explanations for what structures either fine-scale or broad-scale patterns -- problem?
15. There are some issues of using same reference for LTF and ZF -- namely, we are assuming conserved synteny, and any rearrangements might then be seen as regions of high recombination. How should we address this? Maybe just by pointing out few fixed inversions, the high correlation in broad rates, and the high percentage of shared hotspots?

## To Download
1. D.G. Mets, B.J. Meyer, Cell 139, 73 (2009).
2. V.Borde et al., EMBO J. 28, 99 (2009).
3. Lichten M, Goldman AS (1995) Meiotic recombination hotspots. Annu Rev Genet 29(1):423–444.
4. Lichten, M. & de Massy, B. The impressionistic landscape of meiotic recombination. Cell 147, 267–270 (2011).
5. Kauppi, L. et al. Distinct properties of the XY pseudoautosomal region crucial for male meiosis. Science 331, 916–920 (2011).
6. Strathern JN, Shafer BK, McGill CB (1995) DNA synthesis errors associated with double-strand-break repair. Genetics 140: 965–972.


### Papers 
### Dumont et al 2011; mouse recombination
* compare two strains of mouse
* "True et al. (1996) examined patterns of genetic map length divergence between sibling species of Drosophila, concluding that extensive differences in megabase-resolution map lengths can accumulate on the timescale of 1 to 3 million years. The comparison of linkage maps developed for a subset of the Apis mellifera and Apis florea genomes, two taxa that diverged 8–10 million years ago (Mya), yielded similar conclusions (Meznar et al. 2010). The genetic map lengths of orthologous intervals are weakly correlated between human, mouse, and rat (Jensen-Seaman et al. 2004) and between chicken and zebra finch (Backstrom et al. 2010), indicating that the distant shared ancestry of a genomic region is a poor predictor of contemporary recombination rates. In contrast, the comparison of genetic linkage maps among Nasonia species (Beukeboom et al. 2010) suggests that broadscale recombination rates are largely conserved in these very recently diverged taxa (1 Mya)."
* see differences in two subspecies (primarily in map length, don't really discuss patterns of distribution along the chromosome) that 

### Pan et al 2011; yeast recombination
* studied recombination by looking at location of DSBs by sequencing DSB
* yeast DSBs are det'd by open chromatin, histone modifications, and binding of TF
* see positive correlation of GC content with Spo11 density and negative correlation with cohesin density (i.e., in areas with more open chromatin)
* many yeast DSBs occur in intergenic regions containing gene promoters
* their hotspots were very narrow -- no more than 300 bp wide
* 88.2% of hotspots overlapped with promoters
* 11% of Spo11 oligos had a match outside a hotspot -- so looks like in yeast all the recombination is happening within a hotspot?
* Spo11 oligos tend to be in promoter regions that are NDR (nucleosome depleted regions)
* argue that variability in nucleosome occupancy across strains could impact stability of hotspots
* see no strong evidence for any one TF with DSBs
* argue that there should be conservation of hotspots across yeast strains because chromatin structure is fairly conserved

### Baudat and Nicolas 1997; yeast control
* Yeast hotspots tend to be in promoters and also near chromosome ends and centromeres.

### Begun and Aquadro 1992; classic rho and pi 
* correlation btn rho and pi

### Stevison et al 2015; primate comparisons
* gives a sense of how quickly rec rate changes
* chimps, bonobos, and gorillas
* see that recombination rate similarity declines more quickly than nucleotide divergence between species
	- divergence and rho correlation are correlated pretty highly, though we don't see that at a genomic scale
* rho as measured across tehse species are all less than 1 (as measured at Kb) -- much narrow range than ZF and LTF
* see that Drosophila and C. elegans have less biased recombination across the genome -- Gini coefficient is less biased

### Smukowski Heil et al 2015; Drosophila comparisons
* Drosophila don't have PRDM9
* No TSS peak - actually see decrease
* also no hotspots
* "These observations set up a model in which organisms without Prdm9 are opportunistic: they form recombinatin hotspots in "windows of opportunity", most often nucleosome depleted regions around promoters/TSS."
* Only C. elegans and Drosophila don't have hotspots?
* see correlation between recombination and diversity
* see correlation of pedigree and LD based maps on the order of ~0.6 to ~0.8 depending on how windows are defined
* argue that recombination rates are less conserved at fine scales across the genome, just like in species with PRDM9

### Christidis 1986; Estrilid karyotype
* he counts 78 chromosomes in long-tailed finch
* see polymorphism for inversion on Z in both, incl. centromere
* see evidence for shifts in centromere location from ZF to LTF
* has evidence of inversion on chr6, but this might not be the same as what we call chr6

### Wijnker et al 2013; A. thaliana
* in Arabidospis, recombination appears to target non-methylated nucleosome free regions at gene promoters
* all about the open chromatin
* also some evidence for avoidance in peri-centromeric regions
* see more recombination in AT rich promoter regions
* genomic rearrangements can lead to false positive NCO-GC calls -- does our masking for switch errors kinda get at this?
* recombination sites are associated with two motifs -- one is AAAA rich and the other is TCTC rich
	- poly-A motifs tend to signify nucleosome-free regions

### Groenen et al 2009; Gallus pedigree
* see enrichment for consensus sequence for cohesion in "hot spots": CCNCCNGGNGG

### Backstrom et al 2010; ZF pedigree
* they already found evidence for telomere effect, so be sure to identify them
* they found 90% of total recombination concentrated into 23% of genome; our values don't seem as high ...
* "On the one hand, GC-rich sequence motifs could act as signals for recombination via, for example, preferential binding of cohesin complexes, which has been shown to mediate the efficiency of double strand break repair in yeast (Sjo ̈gren and Nasmyth 2001)"
* see good correlation bewteen females and males
* the biggest factor explaining recombination rate variation is distance to chromosome end
* find a comparable measure of correlation between ZF and chicken -- 0.50

### Axelsson et al 2012; dog recombination
* birds, some fish, frogs, tunicates, diptera and nematodes all don't have PRDM9 (Oliver et al 2009)
* looks like all dogs and foxes don't have PRDM9
* some long hotspots -- 33 kb
* some clever analyses to suggest that GC peaks explain hotspots rather than v.v. using the panda genome
* they argue the extreme difference in GC bias suggests that the hotspot has been there for a long time -- or is it because their hotspots are just really hot?

### Smukowski and Noor 2011; review
* "Indeed, in flies and humans, variability in recombination rate explains more than 50% of the variation in nucleotide heterozygosity across the genome (Nachman 2002)"
* suppression of recombination of centromeric heterochromatin might be necessary to allow proper segregation

### Meunier and Duret 2004; GC*
* Recombination drives base composition -- useful way to think about it?
* this is the citation for GC*
* at what point does the changes in base composition reach equilibrium? especially if recombination is more likely in GC rich areas, so this is a positive feedback loop?
	- their simulations suggest equilibrium values could take millions of years to reach
	- GC content is generally greater than GC*?? (Fig 3)

### Nabholz et al 2011; avian base composition
* see a link between GC content and recombination in ZF, but cannot determine causality
* do claim that data suggest biased gene conversion

### Kong et al 2010; Decode paper
* males and females don't even share the same hotspots in humans
* point out that our map is sex-averaged?
* see decreased recombination in exons, inverse of what we found

### Smagulova et al 2011; mouse
* mouse hotspots tend to be occupied by nucleosome
* methylation of histones matters too -- but only the testes specific H3K4 marks
* mouse hotspots tend to overlap genes, tend to be correlated with GC content and repeats
* PRDM9 binding predicts most of the DSBs and 94% of hotspots overlap H3K4me3
	- unlike in yeast, H3K4me3 for hotspots and for promoters appear to be different
	
### Brick et al 2012; mouse PRDM9 KO
* weird adaptationist language that suggests PRDM9 prevents recombination from happening near functional elements
* w/o PRDM9, mice still have hotspots, often at H3 lysine 4 (H3K4) trimethylation marks AND see a lot of hotspots at promoters
* "Almost half (44%) of recombination hotspots in the *Prdm9-/-* mice localize to the promoters of annotated genes compared to just 3% in wild type""
* "However, whereas DSBs at yeast promoters form in the upstream nucleosome-depleted region, hotspots in Prdm9-/- mice preferentially form at the most frequently H3K4 trimethylated nucleosome at the +1 position, just downstream of the TSS" - what do birds do?
* PRDM9 KOs are sterile
* why would DSBs at the promoters be subject to inefficient repair and meiotic arrest?
* PRDM9 does not appear to define the localization of hotspots in the PAR - huh.

### Ellegren 2012; flycatcher speciation paper
* pi in individual species not that much less than divergence between individuals
* dxy did not exceed background levels in divergence islands
* divergence driven less by absolute increase in divergence (dxy) and more by increase in net divergence (da) -- says more about population level processes and *probably* gene flow
* Taken together, these results suggest that selection has acted to reduce genetic variability in the very same regions in the two lineages independently. -- seems like recombination could be influential here, too.
* These tests provided no strong evidence of reduced recombination rate in the proximity of divergence islands
* The Z chromosome showed greater than sevenfold higher mean divergence 

### McVean et al 2004; human fine-scale
* 50% of recombination in 10% of sequence in humans; based on just a portion of the genome
* regional rates of recombination span 4 orders of magnitude
* recombination preferentially occurs outside of genes
* hotspots are pretty frequent - occur every 200 kb
* they define hotspots as: 5x are greater rho than regional background
* earlier human results showed an increase of recombination with CpG islands, but this is at a broad scale
* LD based maps

### Myers et al 2005; human fine-scale
* 80% of recombination in 10% of sequence in humans
* LD based maps
* in recombination deserts, found fewer hotspots and they have less intensity
	- do we see the same? hard to test because our recombination deserts are so deserted that we have very little power to identify hotspots
* find no regions larger than 200 kb that are completely devoid of recombination
	- we see some regions that are essentially devoid of recombination, notably chrZ - worth quantifying?
* 25K hotspots occuring every 50 kb
* see evidence for hotspots occurring near genes but not on top of the TSS - more like 30 kb away
* "This suggests a two-stage process for recombination. A possible model is that recombination rates are constrained over large scales, plausibly by physical stresses acting on the DNA and/or by access to the recombination machinery, and that these constraints are slowly evolving and can be reasonably well predicted by sequence and genomic features."

### Winckler et al 2005; human vs. chimp
* first study that showed no evidence of hotspot sharing between human and chimp?
* saw no correlation in recombination rates between the two species even at a broader scale - that's weird. Maybe just too little data?

### Coop et al 2008; comparison in humans
* pedigree based analysis of hutterites
* recapitulate Myers 2005 result of dip at center of TSS with peaks a bit further away from TSS (~50 kb)
* at a broad scale, see recombination rates increase with gene density

### Baudat et al 2010; PRDM9 gene
* H3K4me3 defines yeast and mouse initiation sites
* PRDM9 motif plays a role in 40% of hotspots
* "PRDM9 has been shown to trimethylate H3K4 and is expressed specifically in germ cells during meiotic prophase"
* PRDM9 evolves rapidly, specifically the zf part
* Spo11 actually does the DSB, PRDM9 just helps trigger it
* Set1 in yeast does the methyl transferase-ing that recruits Spo11; does not bind DNA
* In PRDM9 mice KOs, there are some DSBs, so PRDM9 control is not complete
	- does Set1 not have any functional role in mammals? What does a Set1 & PRDM9 mice knockout look like? Probably dead.
	
### Myers et al 2010; PRDM9 gene
* PRDM9 motif often occurs in repeats? THE1 and LINE1?
* "In yeast, mutation of the sole gene, Set1, encoding H3K4me3 reduces crossover activity at 84% of hotspots."

### Parvanov et al 2010; PRDM9 
* same same same

### Auton et al 2012; chimps
* broad-scale rates are conserved but for regions of chromosomal rearrangements
* see increase in recombination as you move toward chromosome ends
* correlation in rho btn humans & chimps at 10 kb scale is 0.10
* correlation in rho btn humans & chimps at 1 Mb scale is 0.60
	- given that hotspots are conserved across species, wouldn't we expect the scale at which we measure correlations would affect the strength of correlation less?
	- but maybe not because hotspots explain so little of the recombination, anyways
	- and it also is an issue of noise
* GC fraction and recombination rate has a partial r of 0.51 in humans, but only 0.11 in chimps - why?
* nucleosome occupancy is disstabilized around promoters and CpG islands - access argument? but PRDM9 helps get access?
* see increase in recombination rate near CpG islands
* "rate elevation around promoters in humans was found to be driven by genes that have a high rate of CpG methylation in sperm, but in chimpanzees it occurs around genes with low rates of sperm CpG methylation"
* in chimps, nothing seems to predict hotspot locations

### de Massy 2014; Pratto review
* only 10% of meiotic recombination events are crossovers, the rest are non-crossovers.
* This review makes it seem like biased BGC is not a given? Should probably explain it more in the talk and in the text.

### Pratto et al 2014; individual maps
* "We also find that PRDM9 heterozygosity affects hotspot strength." and "We can explain less than half of the variation in hotspot intensity by sequence changes at PRDM9 binding sites." --> so does PRDM9 have a role in hotspot heat or not?
* find evidence of recombination-coupled mutagenesis
* why certain DSBs become crossovers is unknown
* autosomal DSB hotspot heats vary over 3 orders of magnitude (so what 5x to 500x??)
* see purine-pyrmidine skew around hotspot centers
	- worth testing here?
* "most human DSB hotspots coincide with H3K4me3 in testis (57%)"
* some DSBs are associated with increased recombination but have not been identified as hotspots
* see more mutations at a DSB hotspot the hotter it is
* "in subtelomeric regions, PRDM9 may define DSBs independent of its methyltransferase activity, or that in these regions, other factors such as the chromatin environment and/or proximity to the nuclear envelope may modulate hotspot strength"

### Liu et al 2015; honeybees
* honeybees have recombination rates on the order of 20 cM / Mb
* honeybees have very high CO rates and very low NCO rates - so maybe the total number of DSBs are the same? The control of them is just different?

### Weber et al 2014; GC & birds
* they argue that the recombinational landscape is conserved in birds (?)
* GC bias in mismatch repair is actually pretty subtle -- just 1.3% GC excess as measured in yeast
* see correlation between life history traits and gBC strength, with the argument that LHT correlates with more meioses which means more chances for gBC in human time
* ground finch and zebra finch have particularly high GC3 contents
* see correlation between GC content and broad scale recombination rates in zebra finch and chicken
* "the reinforcement of GC-rich isochores in birds is indeed related to a connection between the stable avian karyotype and stable recombination landscapes"
	- I suppose there is so little data on comparative recombination rates that an expectation for what conserved looks like doesn't really exist. I suppose compared to humans & chimps, birds are more conserved. Humans & mice ~ finches & flycatchers? Need to check Jetz paper for estimated TMRCA.
	
### Arbeithuber et al 2015; recombinogenic hotspots
* crossovers found by sequencing sperm showed that recombined molecules have more mutations than non-recombined molecules
* see favoring of GC->AT mutations? but see GC alleles more likely to be favored in crossing over
* argue the increased mutation rate could result from the higher methylation rates in hotspots
* complex crossovers (CCOs) are discontinuous recombination tracts with two breakpoints

### Hellsten et al 2013; Mimulus
* used a version of the four-gamete test for heterozygous sites on the same sequencing read to get rec rates from LD
* see a peak of recombination at TSS
* see that recombination tracts are likely to terminate in exons
* "The CpG to GpC dinucleotide ratio in all hotspot and cold spot associated sequences is 1.05 and 0.84, respectively. CpG deficiency is typically caused by higher mutability of the C in methylated CpG (19), suggesting that hotspots are associated with unmethylated CpG islands."
*  see that hotspots are associated with unmethylated CpG islands
	- important distinction (not always being made) is that fine-scale increases in recombination near TSS dos not necessarily mean hotspots occur near TSS -- the plot of distance of hotspots to coldspots to TSS suggest this
* in yeast, DSBs tend to occur in open chromatin where there are no nucleosomes (so again, there is access)
* "this appears to be a derived mechanism in mammals that overrides a PRDM9-independent ancestral eukaryotic recombination initiation process which we speculate was predominantly based on the accessibility of the recombination machinery to DNA"

### Berg et al 2011; PRDM9 hotspots in African

### Boulton et al 1997; hotspot paradox
* how do hotspots survive given they get repaired using template information from inactive alleles on homologs?
* but this assumes stability of hotspots, which has been seen in some species, but not others
* I do not understand the conclusions of this paper

### Gerton et al 2000; yeast hotspots
* coldspots were nonrandomly associated with centromeres and telomeres
* see very fine-scale correlation of GC content with yeast hotspots
* how are cohesins different from nucleosomes?

### Tsai et al 2010; yeast hotspot conservation
* S. cerevisae and S. paradoxus are 10x more divergent than humans vs. chimps, but show evidence for hotspot conservation
* they argue that this conservation is because of the low levels of sex and outcrossing in yeasts, which reduces the effect of gBC
* rates of recombination are higher in intergenic regions
* see connection between rho and GC content, too
* 40 - 50% of hotspots found as shared (though tested a pretty small number)
* argue that hotspots might be maintained if the hotspot sequence is somehow functionally maintained for another reason 
* they argue that these hotspots are relics of a time when there was a more ancient sexually reproducing yeast species

### Rodgers-Melnic et al 2015; maize
* recombination rates vary 1000x across the maize genome
* use GBS data to get recombination rates
* see pretty stable recombination patterns across two very different lines of maize
* in plants, heterochromatic regions (tightly packed DNA) tend to be depleted of crossovers
* similar to Arabidopsis, see suppression of recombination around the centromere
* hypermethylated CpG regions have fewer crossovers
* "Indeed, at the megabase scale, a linear model with terms for GBS marker density, distance from the telomere, DNA methylation, GC content, and repeat content explains ∼85% of the variance in cross-over density"
	- maybe inclusion of GBS marker density worrisome, but otherwise, pretty impressive
	- much of this driven by GBS marker density and telomere distance
* see hotspot conservation across the two lines and some evidence of conservation in teosinte
* in A. thaliana, recombination appears to target AT-rich regions?

### Berg et al 2010; PRDM9 variation
* showed evidence that PRDM9 variation controls hotspots

### Choi et al 2013; arabidopsis hotspots
* in budding yeast, hotspots overlap regions of low nucleosome density
* hotsptos were associated with active chromatin modifications - low DNA methylation, no nucleosomes, H3K4me3
	- but all these features correlate with each other and with TSS
* see suppression of recombination at centromere
* see overlap of hotspots with TSS / TTS (4 - 6% of TSS / TES overlap with a hotspot) 
	- by these metrics, we might see overlap too -- my expectations were a bit more stringent
* their motif results identified A-rich and CTT-repeat motifs being enriched at hot spots
* do all analyses based around defining TSS as hot or not, which seems weird given that only a fraction of their hotspots were centered on TSS -- maybe because more easily allows them to compare across measures?
* "This result is consistent with H2A.Z promoting DSB formation, resection and/or strand invasion during meiotic prophase I."

### Ptak et al 2005; chimps-humans
* see only 8% overlap between two species but based only on 14 Mb sequence

### Kim et al 2007; rho and LD in arabidopsis
* find evidence for hotspots in intergenic regions

### Otto and Lenormand 2002; sex and recombination
* interesting article because it points out the reasons you might want (or might not!) want to have high recombination
* given that, what predictions might you make for how broad scale recombination evolved in birds and also where hotspots are located?
* when recombination increases during periods of strong selection, is the increase even across chromosomes? or does it vary based on aspects of the chromosome or the genic content or the genes under selection?
* there appears to be strong selection to keep the total number of recombination events per chromosome constant through evolutionary time to prevent aneuploidy -- but what about positions of these crossovers?

### Kauppi et al 2004; recombination in mammals
* open chromatin structure is importannt for DSB formation

### Coop and Przeworski 2006; human recombination
* strong correlation between number of chromosome arms in a species and the sex-averaged genetic map
* a reminder that hotspots are defined differently in different studies -- mainly w.r.t. to the scale at which background rho is measured and the expected width of hotspot etc
* no hotspots in Drosophila or C. elegans, both of which have synapsis before recombination
* alpha-hotspots in yeast = TF-binding 
* beta-hotspots in yeast = nucleosome-excluding DNA sequences
* gamma-hotspots in yeast = high GC content
* Drosophila's centromeric regions show extensive rate variation both wihin and between species

### Paigen and Petkov 2010; mammalian hot spots
* first hotspot was found in mouse in 1982 (!)
* say 10% of DSBs are resolved as CO
* PRDM9 - PR/SET does the methylation during meiosis

### Cutter and Payseur 2013; recombination and diversity
* most organisms (14 out of 20) show a positive correlation of recombination rates with polymorphism levels

### Baudat et al 2013; mammalian hot spots
* in PAR, hotspots appear to be PRDM9 independent?
* in S. cervisiae DSBs occur in regions enriched for H3K4me3 

### Buhler et al 2007; yeast DSB
* meiotic DSBs form early in prophase I

### McGaugh et al 2012; recombination & selection in drosophila
* identified regions in d. miranda and d. pse that had similar recombination rates, compared nucleotide diversity and divergence, and determined patterns were consistent with linked selection and not that recombination is mutagenic
* "segregating ancestral polymorphisms may be responsible for correlations between divergence and recombination rate" => how?
* Drosophila lacks some of the proteins necessary for DSB repair and crossover generation that other species have
* there is some evidence that recombination is mutagenic in yeast

### Wallberg et al 2015; honeybees
* methylated genes have reduced recombination
* see a nearly linear relationship between the portion of the genome and the portion of recombination
* see correlation of 0.2-0.4 between recombination map constructed via LD vs. via linkage
* see evidence for higher crossover rates in introns vs. exons
* see a much stronger effect of derived allele frequency in 

### Chan et al 2012; LDhelmet
* no hotspots in Drosophila
* LDhelmet is less noisy than LDhat, performs better under selection and different demographic histories
* plot of recombination rate around TSS looks similar to humans, chimps and mice (no peak at center, peak displaced 10kb to either side of TSS)
* see correlation between rec and diversity that extends over 200 kb
* see good correlation at broad scales, and less correlation at fine scales, between the two populations of dmel -- but used wavelet analysis so hard to compare

### Comeron et al 2012; dmel rec
* find hotspots, but have defined these differently and some of these are really large
* see a lot of variation in CO rates across chromosomes by pedigree -- could this be an issue of power
* also see motifs that tend to have a lot of As associated with crossing over

### Coop and Myers 2007; hotspot death
* BGC ultimately leads to the loss of hotspots
* the possible selective benefits of a hotspot (i.e., ensures proper disjunction) are insufficient to maintain a hotspot under BGC
* their model shows that hotspots can die just as quickly as one would predict, also suggests it is very hard for new hotspots to evolve -- how then do they evolve?
* that we can identify hotspots in human 

### Spencer et al 2006; recombination & diversity in humans
* argue that recombination only affects diversity at the level of hotspots
* argue that other reports of recombination correlating with diversity might be because recombination is correlating with some other genomic measure which correlates with diversity

### Corbett-Dettig et al 2015; ns and rec
* show that the correlation between recombination rate and polymorphism is stronger in species with bigger population sizes
* this argues for the role of natural selection in filtering polymorphism
* this provides an alternative explanation for Lewontin's paradox

### Oliver et al 2009; PRDM9 evolution
* see unexpectedly high rates of evolution in PRDM9 across rodents
* suggest that this has to do with PRDM9's role as a possible "speciation gene" via genomic conflict

### Jensen-Seaman et al 2004; comparative recombination
* rat, mouse, human comparisons
* recombination rate is significantly correlated with GC%, CpG, repetitive elements in all species
	- they also note that many of these sequence features are correlated with each other -- very few people note this, so that's nice
* rats appear to have less variable recombination rates -- has anyone confirmed that rats have hotspots?
* rat and mouse have 0.25 correlation at 10 Mb scale -- given their divergence time (~20 mya); compare that to what we see in LTF & ZF or even ZF & chicken

### Kawakami et al 2014; flycatcher
* flycatcher and zebra finch are entirely syntenic
* inversion breakpoints tend to be located towards the end of chromosomes
* mean sex-averaged rate of 3.1 cM/Mb
* see an increase in recombination near chromosome ends, but nothing compared to what is seen in ZF
* map was 10% longer in males than females
* flycatcher recombination is more similar to chickens than ZF
	- this is both true for shape and total map length

### Auton et al 2013; dogs
* see elevated recombination rates at TSS & CpG but no evidence for association with H3K4me3 marks 
* see r=0.87 btn physical linkage map and their own map
* argue that the link btn distribution of recombination and distribution of sequence cannot be measured in dogs because this link is very sensitive to Ne
* see only overlap of 25% between their hotspots and the ones studied by Axelsson ... pretty low
* see peak of recombination at TSS (3.5x greater) - 29% of hotspots are at TSS and 50% are within 15 Kb
* see no evidence that foxes share hotspots with dogs (6 myr)
* hotspots do overlap with H3K4me3 marks, but this appears to be completely driven by CpG presence
* suggest that loss of PRDM9 is why diverse canids hybridize so readily - are their genomes more syntenic, as well?

### de Massy 2013; Meiotic recombination review
* Spo11 is very conserved evolutionary
* there appears to be a lot less conservation in the rest of the DSB machinery
* S. pombe mutants without some of the cohesion components show reduction in meiotiic recombination rates
* both S. cerevisae and S. pombe tend to have hotspots in NDR
* S. pombe has 10% as many hotspots as S. cerevisae -- that's odd
* argue that hotspots should be more stable in species without PRDM9 - because there is no mutation away from PRDM9 motif
* "The consequences of hotspot localization for genome evolution remain unclear, both at the molecular and evolutionary levels. What is the significance of DSBs being close to or far from regions involved in gene expression?"

### Smeds et al 2014; PAR
* Identified 630 kb PAR in flycatcher
* <1% of the Z chromosome
* see higher GC content on PAR and less recombination 
* female recombination rate is 10x that of males

### Af-Am recombination
* find a West African specific PRDM9 motif

### Li et al 2015; Maize recombination
* crossovers centralized in genic over intergenic regions
* see a peak at the TSS but have low resolution
* see negative crossover interference

### Wagner et al 2010; C. elegans
* xnd-1 determines DSB locations in C. elegans
* in C elegans, recombination targets chromosome ends
* xnd-1 mutants have very different recombination maps
* xnd-1 mutants have different chromatin structure
* pretty elegant work 

### Mancera et al 2008; yeast CO and NCO
* showed that DSB and recombination rates highly correlated
* recombination hotspots had short poly(A) stretches more often then expected
* show a relationship between transcription behavior and recombination hotspots, supporting an access argument again

### Otto et al 2011; PAR
* see elevated rates of recombination on the PAR in a range of organisms -- including the papaya!
* not all species see the difference in recombination rates as expected for heterogametic vs. homogametic sex -- many have the same or lower recombination rates in the homogametic sex

### Webster and Hurst 2012; recombination & evolution
* argue that there is no compelling evidence that recombination rate mediates efficacy of selection -- only a little bit of recombination is sufficient to do its good work
* gBGC only correlates with male but not female recombination?

### Tortereau et al 2012; pigs
* high recombination at ends of chromosomes

### McVicker and Green 2010; germline gene expression
* in humans, crossover rate shows a strong negative correlation with gene expression in germ cells
	- expression and crossover rate are positively correlated in somatic tissues
	- somatic testes tissues also show negative correlation (we likely sampled somatic testes tissues in ZF)
* new hotspots can be created in yeast by inserting NDR sequence into the genome (Kirkpatric et al 1999) -- cool!
* disrupting expression in yeast does not affect recombination
* argue that gene expression in meiotic cells inhibits crossovers
* lowly meiotically expressed genes have nearly constant crossover rate across the TSS, highly meiotically expressed genes experience dip in crossover rate after crossing the TSS

### Berchowitz et al 2009; yeast chromatin
* experimentally show DSBs occur in areas of open chromatin
* but not all DSBs occur in areas of open chromatin (NO PATTERN!)

### Beye et al 2006; honey bee recombination
* have super high levels of recombination -- total map length (across just 16 chromosomes) is 3700
	- M. Webster says that in many (eu)social organisms, see an increase in genetic map compared to asocial sister species
* no correlation between recombination rate and chromosome size
* also see increases at telomeres -- most species see this -- is this for a biophysical reason, perhaps?

### Romanov et al 2014; avian genome and dinosaurs
* show little evidence for karyotypic change in avian genomes when comparing zebra finch, budgerigar, chicken, ostrich, XX and XX
* find no support that chromosomal rearrangements are concentrated in areas of recombination activity (same with our data)
* chickens appear to be most conserved
* see many changes in zebra finch, which they argue is concordant with rapid speciation in zebra finch

### Choi and Henderson 2015; hotspot review
* explain why we removed repeat masked areas -- very likely to be mismapped?
* in S. pombe, hotspots are broader, tend to be in intergenic regions, and aren't as correlated with NDR
* "poly dA:dT sequences located upstream of gene transcriptional start sites, which are known to disfavor nucleosome occupancy (Iyer and Struhl, 1995; Segal and Widom, 2009)"

### flock of bird genomes
* saw that they found higher GC-rich high-variance exons at the ends of chromosomes, where recombination tends to be higher
* see correlation between branch length and GC content - why? An issue with generation time? Also see correlation between branch length and body mass - is this all being driven by passerines being a recent radiation and things like ducks and ratites being more basal?
* genome size just varies from 0.91 to 1.3 Gb in birds - very narrow range
* "Such genomic contraction has also evolved convergently in bats (fig. S11), the only flying mammalian group"
* genes are shorter in birds compared to mammal homolog due to shortening of intron
* background substitution rate was 2e-9 site / year (so mutation rate is likely higher than this?)

### Rockman and Kruglak 2009; c. elegans
* terminal ends of chromosome have almost no recombination

### Mugal et al 2013; birds & GC bias
* find that substitutions in chicken (as calculated by a MSA) are not correlated with gBC content as you'd expect IF you assume GC content is not at equilibrium
* likely just an issue of defining substitutions at such big phylogenetic depths?

### Hey et al 2004; hotspot review
* DSBs are not req'd for the formation of the synaptomeal complex in Drosophila or C. elegans -- DSBs occur after the SC forms

### Deaton and Bird 2011; CpG islands
* CGIs are sites of transcription iniation, even when they are very far from annotated TSS
* CGIs can also be regions in which the nucleosomes are unstable
	- supports an argument of stability
	- CGIs have reduced density of histone H3
* CGIs are significantly more reluctant to assemble into nucleosome structure compared to other DNA portions
* most CGIs are unmethylated; methylating CGIs can be a way to silence genes (as in X-inactivation)
* intergenic CGIs are particularly prone to methylation

### Paapo et al 2012; Medicago
* see hotspots but no increase in GC content at hotspots
* hotspots tend to be near centromeres
* Medicago are high selfers (98%)
* Fine scale map but have very low polymorphism - power issue?
* very low values of rho (0.002)
* identified 2000 hotspots
* see increase in recombination near centromere

### Berglund et al 2015; dog methylation
* see low CpG mutation rates at recombination-associated CGIs -- this is what you'd expect if they weren't methylated
* human hotspots don't have much increase in GC content?
* see increased subsitution rate at CGIs overall, suggestive of bGC

### Fowler et al 2014; fission yeast
* hotspots do not tend to be near promoters; most tend to be in large intergenic regions (IGRs) - argue this is similar to mice? I guess it depends on how you define "most"
* hotspots are more sparse in fission yeast compared to budding yeast
* "In many organisms, rDNA repeats are recombinationally suppressed to prevent chromosome rearrangements"
* argue (like Pan et al 2011) that there are no discontinuities in recombination so not clear what makes a hotspot "hot"
* hotspots in S. pombe are wider and hotter than those in S. cerevisae
* hotspots are not as associated with NDR 
	- see dip in nucleosome occupancy in S. pombe but nothing like S. cerevisae
	- remember in S. cerevisae hotspots are associated with NDR -- unless they are exceptionally wide
* "19% of IGR oligos were within 200 bp of coding gene transcription start sites"

### Hyppa and Smith 2010; fission yeast
* DSBs across chromosomes are pretty constant
* "Crossover invariance involves the choice of sister chromatid versus homolog for DSB repair. At strong DSB hotspots, intersister repair outnumbers interhomolog repair ~3:1, but our genetic and physical data indicate the converse in DSB-cold regions."

### Groenen et al 2009; chicken
* see no evidence of sex-biased difference in recombination rates
* see that there is 3.4x times more CTCF-binding sites in recombination jungles than deserts (CTCF-binding sites are CCCTC-binding factor)

### Kaur and Rockman 2014; C. elegans
* "low-recombination central regions of C. elegans chromosomes are gene dense and enriched for highly expressed genes and markers of open chromatin, while the high-recombination arms are enriched for repetitive sequences, genes with low expression, and markers of closed chromatin." (!!! what?)
* 80% recombination / 60% sequence

### Lynn et al 2004; review
* mutations that reduce recombination tend to lead to increased non-disjunction

### Arnheim et al 2008; review
* "These numbers imply an average of one hot spot approximately every 50 to 100 kb" in humans

### Lichten and Goldman 1995; review
* identify hotspots in yeast
* see that hotspots in yeast are in locations of chromatin hypersenstive to DNase
* provide early evidence of hotspots in humans

### Feldman et al 1997; review
* could population genetic principles explain the range of recombination rates across the chromosomes?

### Duret and Gaultier 2009; review
* transmission distortion from human sperm typing: 74:26 to 83:17
* GC bias comes out of the base-excision repair pathway
* r2 between crossover rate and stationary GC content is 0.36 from human data
* GC rich regions are prone to chromosomal breakage
* platypus genomes are more repeat rich and also have higher GC content than the average mammal 
* how does gBGC influence selection? can be a promoting or retarding force ... interesting to think about

### Charlesworth and Campos 2014; review
* there are more TEs in low recombination areas in drosophila
* "It seems clear that higher rates of recombination facilitate both higher levels of nucleotide site variability and more effective positive and purifying selection. This is in agreement with theoretical predictions and underscores the evolutionary significance of sexual reproduction"

### Ellegren 2013; review
* almost all bird genomes have 2n of 76 to 80
* birds have few interchromosomal rearrangements (could this suggest low levels of NAHR?) but intrachromosomal rearrangements are more common
* breakpoints for inversions tend to be in high recombination areas, though we don't see this in our data
* there are linkage maps for zebra finches, collared flycatchers, blue tits, great reed warblers, and Siberian jays + chickens -- all these are passerines but most of them have too few markers to look at distribution of reocmbination rates
* bird mutation rates in different studies range from 3e-10 to 2.1e-9
* zebra finch pi is 5x - 10x greater than many other bird species for which pi has been estimated
* many bird genomes show a negative correlation between diversity and chromosome size, which could be a function of recombination











