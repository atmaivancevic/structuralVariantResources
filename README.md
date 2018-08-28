# Structural Variant Resources 

A collated list of useful tools and papers for structural variant analysis.

For each category, papers are sorted by year of publication and provided in the following format:

*Title. Author Year, Journal (link_to_paper).*

Tools include both the software/GitHub link and the original paper, as follows:

*Software (link_to_software): Description. Author Year, Journal (link_to_paper).*

Table of Contents:





## 1. Introduction to structural variation


Introduction
============

- A decade of structural variants: description, history and methods to detect structural variation. [Escaramís et al 2015, Brief Funct Genomics](https://academic.oup.com/bfg/article/14/5/305/184088).

- The functional impact of structural variation in humans. 
[Hurles et al 2008, Trends Genet](https://www.sciencedirect.com/science/article/pii/S0168952508000784?via%3Dihub). 

## 2. Detecting SVs in whole genome data
### 2.1 Genome quality checks

- How complete are ‘complete’ genome assemblies? An avian perspective. [Peona et al 2018, Mol. Ecol. Resour](https://onlinelibrary.wiley.com/doi/abs/10.1111/1755-0998.12933).

- The Oxford Nanopore MinION: delivery of nanopore sequencing to the genomics community. [Jain et al 2016, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-1103-0).

- Resolving the complexity of the human genome using single-molecule sequencing. [Chaisson et al 2015, Nature](https://www.nature.com/articles/nature13907).

- Performance comparison of whole-genome sequencing platforms. [Lam et al 2011, Nature Biotech](https://www.nature.com/articles/nbt.2065).

### 2.2 Stuctural variant calling methods

The following tools were collated from recent reviews, e.g.:

- Recent advances in the detection of repeat expansions with short-read next-generation sequencing. [Bahlo et al 2018, F1000Research](https://f1000research.com/articles/7-736/v1).

- Detection of Genomic Structural Variants from Next-Generation Sequencing Data. [Tattini et al 2015, Front Bioeng Biotechnol](https://www.frontiersin.org/articles/10.3389/fbioe.2015.00092/full).

- Transposable element detection from whole genome sequence data. [Ewing et al 2015, Mobile DNA](https://mobilednajournal.biomedcentral.com/articles/10.1186/s13100-015-0055-3).

#### Split read (SR): 

- [Socrates](http://bioinf.wehi.edu.au/socrates/): Identification of genomic rearrangements in tumour genomes by re-aligning soft clipped reads. [Schroder et al 2014, Bioinformatics](https://academic.oup.com/bioinformatics/article/30/8/1064/257640).

- [MultiBreak-SV](https://github.com/raphael-group/multibreak-sv): Characterization of structural variants with single molecule and hybrid sequencing approaches. [Ritz et al 2014, Bioinformatics](https://academic.oup.com/bioinformatics/article/30/24/3458/2422243).

- [Gustaf](https://github.com/seqan/seqan/tree/master/apps/gustaf): Detecting and correctly classifying SVs in the NGS twilight zone. [Trappe et al 2014, Bioinformatics](https://academic.oup.com/bioinformatics/article/30/24/3484/2422148).

- [SVseq2](http://www.engr.uconn.edu/~jiz08001/): An improved approach for accurate and efficient calling of structural variations with low-coverage sequence data. [Zhang et al 2012, BMC Bioinformatics](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-13-S6-S6).

- [Splitread](http://splitread.sourceforge.net/): Detection of structural variants and indels within exome data. [Karakoc et al 2012, Nature Methods](https://www.nature.com/articles/nmeth.1810).

#### Paired read (PR):

- [The CLEVER Toolkit](https://bitbucket.org/tobiasmarschall/clever-toolkit): Clique-enumerating variant finder. [Marschall et al 2012, Bioinformatics](https://academic.oup.com/bioinformatics/article/28/22/2875/243930).

- [VariationHunter](http://variationhunter.sourceforge.net/Home): Simultaneous structural variation discovery among multiple paired-end sequenced genomes. [Hormozdiari et al 2011, Genome Research](https://genome.cshlp.org/content/21/12/2203).

- [BreakDancer](http://breakdancer.sourceforge.net/): An algorithm for high-resolution mapping of genomic structural variation. [Chen et al 2009, Nature Methods](https://www.nature.com/articles/nmeth.1363).

- [PEMer](http://sv.gersteinlab.org/pemer/): A computational framework with simulation-based error models for inferring genomic structural variants from massive paired-end sequencing data. [Korbel et al 2009, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2009-10-2-r23).

- [MoDIL](http://compbio.cs.toronto.edu/modil/): Detecting small indels from clone-end sequencing with mixtures of distributions. [Lee et al 2009, Nature Methods](https://www.nature.com/articles/nmeth.f.256).

#### Read depth (RD):

- [CODEX](https://github.com/yuchaojiang/CODEX2): A normalization and copy number variation detection method for whole exome sequencing. [Jiang et al 2015, Nucleic Acids Research](https://academic.oup.com/nar/article/43/6/e39/2453417).

- [ONCOCNV](http://boevalab.com/ONCOCNV/): Multi-factor data normalization enables the detection of copy number aberrations in amplicon sequencing data. [Boeva et al 2014, Bioinformatics](https://academic.oup.com/bioinformatics/article/30/24/3443/2422154).

- [EXCAVATOR](https://sourceforge.net/projects/excavatortool/): Detecting copy number variants from whole-exome sequencing data. [Magi et al 2013, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2013-14-10-r120).

- [CoNIFER](http://conifer.sourceforge.net/): Copy number variation detection and genotyping from exome sequence data. [Krumm et al 2012, Genome Research](https://genome.cshlp.org/content/22/8/1525).

- [XHMM](http://atgu.mgh.harvard.edu/xhmm/tutorial.shtml): Discovery and statistical genotyping of copy-number variation from whole-exome sequencing depth. [Fromer et al 2012, Am. J. Hum. Genet](https://www.sciencedirect.com/science/article/pii/S000292971200417X?via%3Dihub).

- [CNAnorm](http://www.precancer.leeds.ac.uk/software-and-datasets/cnanorm/): Correcting for cancer genome size and tumour cell content enables better estimation of copy number alterations from next-generation sequence data. [Gusnanto et al 2012, Bioinformatics](https://academic.oup.com/bioinformatics/article/28/1/40/218361).

- [cn.MOPS](http://www.bioinf.jku.at/software/cnmops/): Mixture of Poissons for discovering copy number variations in next-generation sequencing data with a low false discovery rate. [Klambauer et al 2012, Nucleic Acids Research](https://academic.oup.com/nar/article/40/9/e69/1136601).

- [CNVnator](https://github.com/abyzovlab/CNVnator): An approach to discover, genotype, and characterize typical and atypical cnvs from family and population genome sequencing. [Abyzov et al 2011, Genome Research](https://genome.cshlp.org/content/21/6/974).

- [ExomeCNV](http://www2.uaem.mx/r-mirror/web/packages/ExomeCNV/index.html): Exome sequencing-based copy-number variation and loss of heterozygosity detection. [Sathirapongsasuti et al 2011, Bioinformatics](https://academic.oup.com/bioinformatics/article/27/19/2648/231564).

- [JointSLM](http://www.mybiosoftware.com/jointslm-0-1-detect-recurrent-copy-number-variations-depth-coverage-data.html): Detecting common copy number variants in high-throughput sequencing data by using jointslm algorithm. [Magi et al 2011, Nucleic Acids Res](https://academic.oup.com/nar/article/39/10/e65/1309398).

- [ReadDepth](https://github.com/chrisamiller/readdepth): A parallel r package for detecting copy number alterations from short sequencing reads. [Miller et al 2011, PLoS ONE](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0016327).

- [BIC-seq](http://compbio.med.harvard.edu/BIC-seq/): Copy number variation detection in whole-genome sequencing data using the bayesian information criterion. [Xi et al 2011, Proc. Natl. Acad. Sci.](http://www.pnas.org/content/108/46/E1128).

- [CNAseg](https://www.compbio.group.cam.ac.uk/software/cnaseg): A novel framework for identification of copy number changes in cancer from second-generation sequencing data. [Ivakhno et al 2010, Bioinformatics](https://academic.oup.com/bioinformatics/article/26/24/3051/288761).

- [SegSeq](https://software.broadinstitute.org/software/cprg/?q=node/39): High-resolution mapping of copy-number alterations with massively parallel sequencing. [Chiang et al 2009, Nature Methods](https://www.nature.com/articles/nmeth.1276).

- [CNV-seq](http://tiger.dbs.nus.edu.sg/CNV-seq/): A new method to detect copy number variation using high-throughput sequencing. [Xie et al 2009, BMC Bioinformatics](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-10-80).

- [RDXplorer](http://rdxplorer.sourceforge.net/): Sensitive and accurate detection of copy number variants using read depth of coverage. [Yoon et al 2009, Genome Research](https://genome.cshlp.org/content/19/9/1586).

#### Local re-assembly (LR):

- [TIGRA](http://bioinformatics.mdanderson.org/main/TIGRA): A targeted iterative graph routing assembler for breakpoint assembly. [Chen et al 2014, Genome Research](https://genome.cshlp.org/content/24/2/310).

- [Cortex](http://cortexassembler.sourceforge.net/): De novo assembly and genotyping of variants using colored de bruijn graphs. [Iqbal et al 2012, Nature Genetics](https://www.nature.com/articles/ng.1028).

- [Magnolya](https://sourceforge.net/projects/magnolya/): De novo detection of copy number variation by co-assembly. [Nijkamp et al 2012, Bioinformatics](https://academic.oup.com/bioinformatics/article/28/24/3195/245056).

#### Combination methods:

##### PR + SR:

- [LUMPY](https://github.com/arq5x/lumpy-sv): A probabilistic framework for structural variant discovery. [Layer et al 2014, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2014-15-6-r84).

- [SoftSearch](https://omictools.com/softsearch-tool?t=tab-tool-variant-0): Integration of Multiple Sequence Features to Identify Breakpoints of Structural Variations. [Hart et al 2013, PLoS ONE](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0083356).

- [MATE-CLEVER](https://bitbucket.org/tobiasmarschall/clever-toolkit): Mendelian-inheritance-aware discovery and genotyping of midsize and long indels. [Marschall et al 2013, Bioinformatics](https://academic.oup.com/bioinformatics/article/29/24/3143/194997).

- [DELLY](https://github.com/dellytools/delly): Structural variant discovery by integrated paired-end and split-read analysis. [Rausch et al 2012, Bioinformatics](https://academic.oup.com/bioinformatics/article/28/18/i333/245403).

- [PRISM](http://compbio.cs.toronto.edu/prism/): Pair-read informed split-read mapping for base-pair level detection of insertion, deletion and structural variants. [Jiang et al 2012, Bioinformatics](https://academic.oup.com/bioinformatics/article/28/20/2576/202193).

- [Pindel](https://github.com/genome/pindel): A pattern growth approach to detect break points of large deletions and medium sized insertions from paired-end short reads. [Ye et al 2009, Bioinformatics](https://academic.oup.com/bioinformatics/article/25/21/2865/2112044).

##### RD + PR:

- [GASVPro](http://compbio.cs.brown.edu/projects/gasv/): An Integrative Probabilistic Model for Identification of Structural Variation in Sequencing Data. [Sindi et al 2012, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2012-13-3-r22).

- [inGAP-sv](http://ingap.sourceforge.net/): A novel scheme to identify and visualize structural variation from paired end mapping data. [Qi et al 2011, Nucleic Acids Res.](https://academic.oup.com/nar/article/39/suppl_2/W567/2507282).

- [CNVer](http://compbio.cs.toronto.edu/CNVer/): Detecting copy number variation with mated short reads. [Medvedev et al 2010, Genome Research](https://genome.cshlp.org/content/20/11/1613).

- [SVDetect](http://svdetect.sourceforge.net/Site/Home.html): A tool to identify genomic structural variations from paired-end and mate-pair sequencing data. [Zeitouni et al 2010, Bioinformatics](https://academic.oup.com/bioinformatics/article/26/15/1895/188785).

##### RD + SR:

- [SVseq](http://www.engr.uconn.edu/~jiz08001/): An approach for detecting exact breakpoints of deletions with low-coverage sequence data. [Zhang et al 2011, Bioinformatics](https://academic.oup.com/bioinformatics/article/27/23/3228/235808).

##### PR + LR:

- [HYDRA-SV](https://code.google.com/archive/p/hydra-sv/): Genome-wide mapping and assembly of structural variant breakpoints in the mouse genome. [Quinlan et al 2010, Genome Research](https://genome.cshlp.org/content/20/5/623).

- [NovelSeq](http://novelseq.sourceforge.net/Home): Detection and characterization of novel sequence insertions using paired-end next-generation sequencing. [Hajirasouliha et al 2010, Bioinformatics](https://academic.oup.com/bioinformatics/article/26/10/1277/194099).

##### SR + LR:

- [CREST](https://www.stjuderesearch.org/site/lab/zhang): Maps somatic structural variation in cancer genomes with base-pair resolution. [Wang et al 2011, Nature Methods](https://www.nature.com/articles/nmeth.1628).

##### PR + SR + RD:

- [Genome STRiP (v2.0)](http://software.broadinstitute.org/software/genomestrip/): A new CNV discovery and genotyping pipeline. Large multiallelic copy number variations in humans. [Handsaker et al Nature Genetics, 2015](https://www.nature.com/articles/ng.3200).

##### PR + SR + LR:

- [GRIDSS](https://github.com/PapenfussLab/gridss): Sensitive and specific genomic rearrangement detection using positional de Bruijn graph assembly. [Cameron et al Genome Research, 2017](https://genome.cshlp.org/content/early/2017/11/02/gr.222109.117.abstract).

#### Other:
##### Tools for detecting mobile element transpositions:

- [MELT](http://melt.igs.umaryland.edu/): Population-scale mobile element discovery and biology. [Gardner et al 2017, Genome Research](https://genome.cshlp.org/content/27/11/1916).

- [T-lex/T-lex2](http://petrov.stanford.edu/cgi-bin/Tlex.html): Genotyping, frequency estimation and re-annotation of transposable elements using single or pooled next-generation sequencing data. [Fiston-Lavier et al 2015, Nucleic Acids Res.](https://academic.oup.com/nar/article/43/4/e22/2410985).

- [DD_DETECTION](https://bitbucket.org/mkroon/dd_detection): Detecting dispersed duplications in high-throughput sequencing data using a database-free approach. [Kroon et al 2015, Bioinformatics](https://academic.oup.com/bioinformatics/article/32/4/505/1744181).

- [Jitterbug](http://sourceforge.net/projects/jitterbug/): Somatic and germline transposon insertion detection at single-nucleotide resolution. [Henaff et al 2015, BMC genomics](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-015-1975-5).

- [ITIS](http://bioinformatics.psc.ac.cn/software/ITIS/): A bioinformatics tool for accurate identification of transposon insertion sites using next-generation sequencing data. [Jiang et al 2015, BMC Bioinformatics](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-015-0507-2).

- [Mobster](https://sourceforge.net/projects/mobster/): Accurate detection of mobile element insertions in next generation sequencing data. [Thung et al 2014, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-014-0488-x).

- [Tangram](https://github.com/jiantao/Tangram): A comprehensive toolbox for mobile element insertion detection. [Wu et al 2014, BMC Genomics](https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-15-795).

- [TE-Tracker](http://www.genoscope.cns.fr/externe/tetracker/): Systematic identification of transposition events through whole-genome resequencing. [Gilly et al 2014, BMC Bioinformatics](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-014-0377-z).

- [TranspoSeq](https://www.broadinstitute.org/cancer/cga/transposeq): Somatic retrotransposition in human cancer revealed by whole-genome and exome sequencing. [Helman et al 2014, Genome Research](https://genome.cshlp.org/content/24/7/1053).

- [TraFiC](https://github.com/cancerit/TraFiC): Extensive transduction of nonrepetitive DNA mediated by L1 retrotransposition in cancer genomes. [Tubio et al 2014, Science](http://science.sciencemag.org/content/345/6196/1251343).

- [TEMP](https://github.com/JialiUMassWengLab/TEMP): A computational method for analyzing transposable element polymorphism in populations. [Zhuang et al 2014, Nucleic Acids Res](https://academic.oup.com/nar/article/42/11/6826/1431591).

- [RetroSeq](https://github.com/tk2/RetroSeq): Transposable element discovery from next-generation sequencing data. [Keane et al 2013, Bioinformatics](https://academic.oup.com/bioinformatics/article/29/3/389/257479).

- [GRIPper](https://github.com/adamewing/GRIPper): Retrotransposition of gene transcripts leads to structural variation in mammalian genomes. [Ewing et al 2013, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2013-14-3-r22).

- [RelocaTE](https://github.com/srobb1/RelocaTE): The use of RelocaTE and unassembled short reads to produce high-resolution snapshots of transposable element generated diversity in rice. [Robb et al 2013, G3](http://www.g3journal.org/content/3/6/949).

- [Tea](http://compbio.med.harvard.edu/Tea/): Landscape of somatic retrotransposition in human cancers. [Lee et al 2012, Science](http://science.sciencemag.org/content/337/6097/967).

- [ngs_te_mapper](https://github.com/bergmanlab/ngs_te_mapper): Whole Genome Resequencing Reveals Natural Target Site Preferences of Transposable Elements in Drosophila melanogaster. [Linheiro et al 2012, Plos ONE](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0030008).

- [TE-Locate](http://sourceforge.net/projects/te-locate/): A Tool to Locate and Group Transposable Element Occurrences Using Paired-End Next-Generation Sequencing Data. [Platzer et al 2012, Biology](http://www.mdpi.com/2079-7737/1/2/395).

##### Tools for detecting short repeat expansions:

- [STRetch](https://github.com/Oshlack/STRetch): Detecting and discovering pathogenic short tandem repeat expansions. [Dashnow et al 2018, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1505-2).

- [exSTRa](https://github.com/bahlolab/exSTRa): Detecting tandem repeat expansions in cohorts sequenced with short-read sequencing data. [Tankard et al 2018, BioRxiv](https://www.biorxiv.org/content/early/2018/07/25/157792).

- [ExpansionHunter](link): Detection of long repeat expansions from PCR-free whole-genome sequence data. [Dolzhenko et al 	2017, Genome Research](https://genome.cshlp.org/content/27/11/1895).

- [TREDPARSE](https://github.com/humanlongevity/tredparse): Profiling of Short-Tandem-Repeat Disease Alleles in 12,632 Human Whole Genomes. [Tang et al 2017, Am J Hum Genet](https://www.sciencedirect.com/science/article/pii/S0002929717303828?via%3Dihub).

##### Tools for building a graph reference genome:

- [Variation Graph](https://github.com/vgteam/vg): Sequence variation aware genome references and read mapping with the variation graph toolkit. [Garrison et al 2017, BioRxiv](https://www.biorxiv.org/content/early/2017/12/15/234856).

- [Graph Genome Suite (Commercial)](https://www.sevenbridges.com/graph/): Fast and Accurate Genomic Analyses using Genome Graphs. [Rakocevic et al 2017, BioRxiv](https://www.biorxiv.org/content/early/2018/03/20/194530).

### 2.3 Filtering false calls

##### Validated SVs for benchmarking: 

- [Genome in a Bottle](http://jimb.stanford.edu/giab/): A human genome standard. [2015, Nature Biotech](https://www.nature.com/articles/nbt0715-675a).

##### General purpose genomic tools:

- [BCFtools/csq](https://samtools.github.io/bcftools/bcftools.html): Haplotype-aware variant consequences. [Danecek et al 2017, Bioinformatics](https://academic.oup.com/bioinformatics/article/33/13/2037/3000373).

- [BEDTools](https://bedtools.readthedocs.io/en/latest/): The Swiss-Army Tool for Genome Feature Analysis. [Quinlan 2014, Curr. Protoc. Bioinformatics](https://currentprotocols.onlinelibrary.wiley.com/doi/abs/10.1002/0471250953.bi1112s47).

- [GenomicRanges](https://bioconductor.org/packages/release/bioc/html/GenomicRanges.html): Software for computing and annotating genomic ranges. [Lawrence et al 2013, PLoS Comput Biol](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1003118).

### 2.4 Standardizing output

- [FusorSV](https://github.com/TheJacksonLaboratory/SVE): An algorithm for optimally combining data from multiple structural variation detection methods. [Becker et al 2018, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1404-6).

- [MetaSV](http://bioinform.github.io/metasv/): An accurate and integrative structural-variant caller for next generation sequencing. [Mohiyuddin et al 2015, Bioinformatics](https://academic.oup.com/bioinformatics/article/31/16/2741/321286).

## 3. Identifying medically relevant SVs

##### Recommended reading:

- American College of Medical Genetics standards and guidelines for interpretation and reporting of postnatal constitutional copy number variants. [Kearney et al 2011, Genet Med](https://www.nature.com/articles/gim92011110).

### 3.1 Population frequencies

- [gnomAD](http://gnomad.broadinstitute.org/): Genome Aggregation Database, a coalition of investigators seeking to aggregate and harmonize exome and genome sequencing data from a variety of large-scale sequencing projects. [Lek et al 2016, Nature](https://www.nature.com/articles/nature19057).

- [ExAC](http://exac.broadinstitute.org/): Exome Aggregation Consortium. [Lek et al 2016, Nature](https://www.nature.com/articles/nature19057).

- [Genome of the Netherlands Project](http://www.nlgenome.nl/): A high-quality human reference panel reveals the complexity and distribution of genomic structural variants. [Hehir-Kwa et al 2016, Nat Commun](https://www.nature.com/articles/ncomms12989).

- [1000 Genomes Project](http://www.internationalgenome.org/): A global reference for human genetic variation. [The 1000 Genomes Project Consortium et al 2015, Nature](https://www.nature.com/articles/nature15393).

### 3.2 Gene annotation

- [GenePANDA (broken link?)](http://genepanda.tianlab.cn): A novel network-based gene prioritizing tool for complex diseases. [Yin et al 2017, Sci Rep](https://www.nature.com/articles/srep43258).

- [Vcfanno](https://github.com/brentp/vcfanno): Fast, flexible annotation of genetic variants. [Pedersen et al 2016, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0973-5).

- [ENCODE](https://www.encodeproject.org/): An integrated encyclopedia of DNA elements in the human genome. [ENCODE Project Consortium 2012, Nature](https://www.nature.com/articles/nature11247).

- [GLAD4U](http://glad4u.zhang-lab.org/index.php): Deriving and prioritizing gene lists from PubMed literature. [Jourquin et al 2012, BMC Genomics](https://bmcgenomics.biomedcentral.com/articles/10.1186/1471-2164-13-S8-S20).

- [UCSC Genome Browser](https://genome.ucsc.edu/): The Human Genome Browser at UCSC, gene tracks available. [Kent et al 2002, Genome Research](https://genome.cshlp.org/content/12/6/996).

### 3.3 Impact prediction

- [DOMINO](https://wwwfbm.unil.ch/domino/index.html): Using Machine Learning to Predict Genes Associated with Dominant Disorders. [Quinodoz et al 2017, Am J Hum Genet](paperlink).

- [SVScore](https://github.com/lganel/SVScore): SVScore: an impact prediction tool for structural variation. [Ganel et al 2017, Bioinformatics](https://academic.oup.com/bioinformatics/article/33/7/1083/2748212).

- [VEP](https://asia.ensembl.org/info/docs/tools/vep/index.html): The Ensembl Variant Effect Predictor. [McLaren et al 2016, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0974-4).

- [SnpEFF](http://snpeff.sourceforge.net/): A program for annotating and predicting the effects of single nucleotide polymorphisms. [Cingolani et al 2012, Fly](https://www.tandfonline.com/doi/abs/10.4161/fly.19695).

- [ANNOVAR](http://annovar.openbioinformatics.org/en/latest/): Functional annotation of genetic variants from high-throughput sequencing data. [Wang et al 2010, Nucleic Acids Res](https://academic.oup.com/nar/article/38/16/e164/1749458).

### 3.4 Visualization

- [Samplot](https://github.com/ryanlayer/samplot): A command line tool for rapid, multi-sample structural variant visualization. Samplot takes SV coordinates and bam files and produces high-quality images that highlight any alignment and depth signals that substantiate the SV. [Ryan Layer 2018, GitHub](https://github.com/ryanlayer/samplot).

- [New Genome Browser](https://github.com/epam/NGB): A web-based NGS data viewer with SV visualization capabilities, high performance, scalability, and cloud data support. [EPAM Systems 2017, GitHub](https://github.com/epam/NGB).

- [Ribbon](http://genomeribbon.com/): For visualizing complex genome alignments and structural variation. [Nattestad et al 2016, BioRxiv](https://www.biorxiv.org/content/early/2016/10/20/082123).

- [CGDV](https://cgdv-upload.persistent.co.in/cgdv/): Another webtool for Circos genomics and transcriptomics data. [Jha et al 2016, BMC Genomics](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-017-4169-5).

- [ClicO FS](http://codoncloud.com:3000): An interactive web-based service of Circos. [Cheong et al 2015, Bioinformatics](https://academic.oup.com/bioinformatics/article/31/22/3685/241292).

- [GASVPro](http://compbio.cs.brown.edu/projects/gasv/): An integrative probabilistic model for identification of structural variation in sequencing data. [Sindi et al 2012, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2012-13-3-r22).

- [Integrative Genomics Viewer](https://software.broadinstitute.org/software/igv/): A high-performance visualization tool for interactive exploration of large, integrated genomic datasets. [Robinson et al 2011, Nature Biotech](https://www.nature.com/articles/nbt.1754).

- [Pairoscope](http://pairoscope.sourceforge.net/): Quick and simple diagrams indicating the relationship of paired end sequencing reads. It functions by displaying multiple genomic regions, their read depth at each base in the region and arcs within or between regions to indicate pairing information. [David Larson 2010, SourceForge](http://pairoscope.sourceforge.net/).

- [Savant](http://genomesavant.com/p/savant/index): A genome browser for next generation data. [Fuime et al 2010, Bioinformatics](https://academic.oup.com/bioinformatics/article/26/16/1938/217890).

- [Circos](http://circos.ca/): A software package for visualizing data and information in a circular layout. [Krzywinski et al 2009, Genome Research](https://genome.cshlp.org/content/early/2009/06/15/gr.092759.109.abstract).

### 3.5 Crowd curation

- [SV-plaudit](https://github.com/jbelyeu/SV-plaudit): A cloud-assisted framework for manually curating thousands of structural variants. [Belyeu et al 2018, GigaScience](https://academic.oup.com/gigascience/article/7/7/giy064/5026174).
