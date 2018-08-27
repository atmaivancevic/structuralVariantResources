# Structural Variant Resources 
ALL the things. Also mention other github/basecamp/stack overflow sites that this was inspired by (e.g. geocarvalho github on sv-cnv-studies)

Listed tools include hyperlinks to the original paper and open source software (if available), and are sorted by publication year (newest first). 

## 1. Introduction to structural variation

### 1.1 Overviews

Copy Number Variations Detection: Unravelling the Problem in Tangible Aspects. [do Nascimento et al 2017, IEEE/ACM Transactions on Computational Biology and Bioinformatics](https://www.computer.org/csdl/trans/tb/2017/06/07484749-abs.html).

A decade of structural variants: description, history and methods to detect structural variation. [Escaramís et al 2015, Brief Funct Genomics](https://academic.oup.com/bfg/article/14/5/305/184088).

The functional impact of structural variation in humans. 
[Hurles et al 2008, Trends Genet](https://www.sciencedirect.com/science/article/pii/S0168952508000784?via%3Dihub). 

### 1.2 SVs in disease

### 1.3 SVs in evolution

## 2. Detecting SVs in whole genome data
### 2.1 Genome quality checks
### 2.2 Stuctural variant calling methods

The following examples were collated from recent reviews, e.g.:

Detection of Genomic Structural Variants from Next-Generation Sequencing Data. [Tattini et al 2015, Front Bioeng Biotechnol](https://www.frontiersin.org/articles/10.3389/fbioe.2015.00092/full).

PAPERTITLE. [AUTHOR et al YEAR, JOURNAL](paperlink).

PAPERTITLE. [AUTHOR et al YEAR, JOURNAL](paperlink).

#### Split read (SR): 

[Socrates](http://bioinf.wehi.edu.au/socrates/): Identification of genomic rearrangements in tumour genomes by re-aligning soft clipped reads. [Schroder et al 2014, Bioinformatics](https://academic.oup.com/bioinformatics/article/30/8/1064/257640).

[MultiBreak-SV](https://github.com/raphael-group/multibreak-sv): Characterization of structural variants with single molecule and hybrid sequencing approaches. [Ritz et al 2014, Bioinformatics](https://academic.oup.com/bioinformatics/article/30/24/3458/2422243).

[Gustaf](https://github.com/seqan/seqan/tree/master/apps/gustaf): Detecting and correctly classifying SVs in the NGS twilight zone. [Trappe et al 2014, Bioinformatics](https://academic.oup.com/bioinformatics/article/30/24/3484/2422148).

[SVseq2](http://www.engr.uconn.edu/~jiz08001/): An improved approach for accurate and efficient calling of structural variations with low-coverage sequence data. [Zhang et al 2012, BMC Bioinformatics](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-13-S6-S6).

[Splitread](http://splitread.sourceforge.net/): Detection of structural variants and indels within exome data. [Karakoc et al 2012, Nature Methods](https://www.nature.com/articles/nmeth.1810).

#### Paired read (PR):

[The CLEVER Toolkit](https://bitbucket.org/tobiasmarschall/clever-toolkit): Clique-enumerating variant finder. [Marschall et al 2012, Bioinformatics](https://academic.oup.com/bioinformatics/article/28/22/2875/243930).

[VariationHunter](http://variationhunter.sourceforge.net/Home): Simultaneous structural variation discovery among multiple paired-end sequenced genomes. [Hormozdiari et al 2011, Genome Research](https://genome.cshlp.org/content/21/12/2203).

[BreakDancer](http://breakdancer.sourceforge.net/): An algorithm for high-resolution mapping of genomic structural variation. [Chen et al 2009, Nature Methods](https://www.nature.com/articles/nmeth.1363).

[PEMer](http://sv.gersteinlab.org/pemer/): A computational framework with simulation-based error models for inferring genomic structural variants from massive paired-end sequencing data. [Korbel et al 2009, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2009-10-2-r23).

[MoDIL](http://compbio.cs.toronto.edu/modil/): Detecting small indels from clone-end sequencing with mixtures of distributions. [Lee et al 2009, Nature Methods](https://www.nature.com/articles/nmeth.f.256).

#### Read depth (RD):

[CODEX](https://github.com/yuchaojiang/CODEX2): A normalization and copy number variation detection method for whole exome sequencing. [Jiang et al 2015, Nucleic Acids Research](https://academic.oup.com/nar/article/43/6/e39/2453417).

[ONCOCNV](http://boevalab.com/ONCOCNV/): Multi-factor data normalization enables the detection of copy number aberrations in amplicon sequencing data. [Boeva et al 2014, Bioinformatics](https://academic.oup.com/bioinformatics/article/30/24/3443/2422154).

[EXCAVATOR](https://sourceforge.net/projects/excavatortool/): Detecting copy number variants from whole-exome sequencing data. [Magi et al 2013, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2013-14-10-r120).

[CoNIFER](http://conifer.sourceforge.net/): Copy number variation detection and genotyping from exome sequence data. [Krumm et al 2012, Genome Research](https://genome.cshlp.org/content/22/8/1525).

[XHMM](http://atgu.mgh.harvard.edu/xhmm/tutorial.shtml): Discovery and statistical genotyping of copy-number variation from whole-exome sequencing depth. [Fromer et al 2012, Am. J. Hum. Genet](https://www.sciencedirect.com/science/article/pii/S000292971200417X?via%3Dihub).

[CNAnorm](http://www.precancer.leeds.ac.uk/software-and-datasets/cnanorm/): Correcting for cancer genome size and tumour cell content enables better estimation of copy number alterations from next-generation sequence data. [Gusnanto et al 2012, Bioinformatics](https://academic.oup.com/bioinformatics/article/28/1/40/218361).

[cn.MOPS](http://www.bioinf.jku.at/software/cnmops/): Mixture of Poissons for discovering copy number variations in next-generation sequencing data with a low false discovery rate. [Klambauer et al 2012, Nucleic Acids Research](https://academic.oup.com/nar/article/40/9/e69/1136601).

[CNVnator](https://github.com/abyzovlab/CNVnator): An approach to discover, genotype, and characterize typical and atypical cnvs from family and population genome sequencing. [Abyzov et al 2011, Genome Research](https://genome.cshlp.org/content/21/6/974).

[ExomeCNV](http://www2.uaem.mx/r-mirror/web/packages/ExomeCNV/index.html): Exome sequencing-based copy-number variation and loss of heterozygosity detection. [Sathirapongsasuti et al 2011, Bioinformatics](https://academic.oup.com/bioinformatics/article/27/19/2648/231564).

[JointSLM](http://www.mybiosoftware.com/jointslm-0-1-detect-recurrent-copy-number-variations-depth-coverage-data.html): Detecting common copy number variants in high-throughput sequencing data by using jointslm algorithm. [Magi et al 2011, Nucleic Acids Res](https://academic.oup.com/nar/article/39/10/e65/1309398).

[ReadDepth](https://github.com/chrisamiller/readdepth): A parallel r package for detecting copy number alterations from short sequencing reads. [Miller et al 2011, PLoS ONE](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0016327).

[BIC-seq](http://compbio.med.harvard.edu/BIC-seq/): Copy number variation detection in whole-genome sequencing data using the bayesian information criterion. [Xi et al 2011, Proc. Natl. Acad. Sci.](http://www.pnas.org/content/108/46/E1128).

[CNAseg](https://www.compbio.group.cam.ac.uk/software/cnaseg): A novel framework for identification of copy number changes in cancer from second-generation sequencing data. [Ivakhno et al 2010, Bioinformatics](https://academic.oup.com/bioinformatics/article/26/24/3051/288761).

[SegSeq](https://software.broadinstitute.org/software/cprg/?q=node/39): High-resolution mapping of copy-number alterations with massively parallel sequencing. [Chiang et al 2009, Nature Methods](https://www.nature.com/articles/nmeth.1276).

[CNV-seq](http://tiger.dbs.nus.edu.sg/CNV-seq/): A new method to detect copy number variation using high-throughput sequencing. [Xie et al 2009, BMC Bioinformatics](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-10-80).

[RDXplorer](http://rdxplorer.sourceforge.net/): Sensitive and accurate detection of copy number variants using read depth of coverage. [Yoon et al 2009, Genome Research](https://genome.cshlp.org/content/19/9/1586).

#### Local re-assembly (LR):

[TIGRA](http://bioinformatics.mdanderson.org/main/TIGRA): A targeted iterative graph routing assembler for breakpoint assembly. [Chen et al 2014, Genome Research](https://genome.cshlp.org/content/24/2/310).

[Cortex](http://cortexassembler.sourceforge.net/): De novo assembly and genotyping of variants using colored de bruijn graphs. [Iqbal et al 2012, Nature Genetics](https://www.nature.com/articles/ng.1028).

#### Combination methods:

##### PR + SR:

[LUMPY](https://github.com/arq5x/lumpy-sv): A probabilistic framework for structural variant discovery. [Layer et al 2014, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2014-15-6-r84).

[SoftSearch](https://omictools.com/softsearch-tool?t=tab-tool-variant-0): Integration of Multiple Sequence Features to Identify Breakpoints of Structural Variations. [Hart et al 2013, PLoS ONE](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0083356).

[MATE-CLEVER](https://bitbucket.org/tobiasmarschall/clever-toolkit): Mendelian-inheritance-aware discovery and genotyping of midsize and long indels. [Marschall et al 2013, Bioinformatics](https://academic.oup.com/bioinformatics/article/29/24/3143/194997).

[DELLY](https://github.com/dellytools/delly): Structural variant discovery by integrated paired-end and split-read analysis. [Rausch et al 2012, Bioinformatics](https://academic.oup.com/bioinformatics/article/28/18/i333/245403).

[PRISM](http://compbio.cs.toronto.edu/prism/): Pair-read informed split-read mapping for base-pair level detection of insertion, deletion and structural variants. [Jiang et al 2012, Bioinformatics](https://academic.oup.com/bioinformatics/article/28/20/2576/202193).

[Pindel](https://github.com/genome/pindel): A pattern growth approach to detect break points of large deletions and medium sized insertions from paired-end short reads. [Ye et al 2009, Bioinformatics](https://academic.oup.com/bioinformatics/article/25/21/2865/2112044).

##### RD + PR:

[inGAP-sv](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[CNVer](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[GASVpro](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SVDetect](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

##### RD + SR:

[SVseq](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

##### PR + LR:

[HYDRA](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[NovelSeq](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

##### SR + LR:

[CREST](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

##### PR + SR + RD:

[Genome STRiP (v2.0)](http://software.broadinstitute.org/software/genomestrip/): A new CNV discovery and genotyping pipeline. Large multiallelic copy number variations in humans. [Handsaker et al Nature Genetics, 2015](https://www.nature.com/articles/ng.3200).

GRIDDS

#### Other:
##### Tools for detecting mobile element transpositions:

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

##### Tools for detecting short repeat expansions:

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

##### Tools for building a graph reference genome:

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, JOURNAL](paperlink).

### 2.3 Filtering false calls
### 2.4 Standardizing output

## 3. Identifying medically relevant SVs
### 3.1 Population frequencies
### 3.2 Gene annotation
### 3.3 Impact prediction

### 3.4 Visualization

[Circos](http://circos.ca/): A software package for visualizing data and information in a circular layout. [Krzywinski et al 2009, Genome Research](https://genome.cshlp.org/content/early/2009/06/15/gr.092759.109.abstract).

[Pairoscope](http://pairoscope.sourceforge.net/): Quick and simple diagrams indicating the relationship of paired end sequencing reads. It functions by displaying multiple genomic regions, their read depth at each base in the region and arcs within or between regions to indicate pairing information. [David Larson 2010, SourceForge](http://pairoscope.sourceforge.net/).

[Savant](http://genomesavant.com/p/savant/index): A genome browser for next generation data. [Fuime et al 2010, Bioinformatics](https://academic.oup.com/bioinformatics/article/26/16/1938/217890).

[Integrative Genomics Viewer](https://software.broadinstitute.org/software/igv/): A high-performance visualization tool for interactive exploration of large, integrated genomic datasets. [Robinson et al 2011, Nature Biotech](https://www.nature.com/articles/nbt.1754).

[GASVPro](http://compbio.cs.brown.edu/projects/gasv/): An integrative probabilistic model for identification of structural variation in sequencing data. [Sindi et al 2012, Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2012-13-3-r22).

[ClicO FS](http://codoncloud.com:3000): An interactive web-based service of Circos. [Cheong et al 2015, Bioinformatics](https://academic.oup.com/bioinformatics/article/31/22/3685/241292).

[CGDV](https://cgdv-upload.persistent.co.in/cgdv/): Another webtool for Circos genomics and transcriptomics data. [Jha et al 2016, BMC Genomics](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-017-4169-5).

[Ribbon](http://genomeribbon.com/): For visualizing complex genome alignments and structural variation. [Nattestad et al 2016, bioRxiv](https://www.biorxiv.org/content/early/2016/10/20/082123).

[New Genome Browser](https://github.com/epam/NGB): A web-based NGS data viewer with SV visualization capabilities, high performance, scalability, and cloud data support. [EPAM Systems 2017, GitHub](https://github.com/epam/NGB).

[Samplot](https://github.com/ryanlayer/samplot): A command line tool for rapid, multi-sample structural variant visualization. Samplot takes SV coordinates and bam files and produces high-quality images that highlight any alignment and depth signals that substantiate the SV. [Ryan Layer 2018, GitHub](https://github.com/ryanlayer/samplot).

Usage notes/top picks: Samplot is great and easy to use. 

### 3.5 Crowd curation

[SV-plaudit](https://github.com/jbelyeu/SV-plaudit): A cloud-assisted framework for manually curating thousands of structural variants. [Belyeu et al 2018 GigaScience](https://academic.oup.com/gigascience/article/7/7/giy064/5026174).

## 4. Ongoing problems and complications
### 4.1 Complex genomic regions
### 4.2 Complex diseases
### 4.3 Proband-only singletons

## 5. Conclusions

## 6. Extra reading for the extra keen





