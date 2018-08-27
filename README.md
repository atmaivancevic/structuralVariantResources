# Structural Variant Resources 
ALL the things. Also mention other github/basecamp/stack overflow sites that this was inspired by (e.g. geocarvalho github on sv-cnv-studies)

## 1. Introduction to structural variation

### 1.1 Overviews

Copy Number Variations Detection: Unravelling the Problem in Tangible Aspects. [do Nascimento et al 2017](https://www.computer.org/csdl/trans/tb/2017/06/07484749-abs.html).

A decade of structural variants: description, history and methods to detect structural variation. [Escaramís et al 2015](https://academic.oup.com/bfg/article/14/5/305/184088).

The functional impact of structural variation in humans. 
[Hurles et al 2008](https://www.sciencedirect.com/science/article/pii/S0168952508000784?via%3Dihub). 

### 1.2 SVs in disease

### 1.3 SVs in evolution

## 2. Detecting SVs in whole genome data
### 2.1 Genome quality checks
### 2.2 Stuctural variant calling methods

##### Split read (SR): 

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).

#### Paired read (PR):

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).

#### Read depth (RD):

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).

#### Local re-assembly (LR):

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).

#### Combination methods:

Many of the above use a combination of different signals. E.g. DELLY; GenomeStrip. 

#### Other:
##### Mobile element callers:

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).

##### Short repeat expansions:

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).

##### Graph reference genomes:

[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).
[SOFTWARE](link): DESCRIPTION. [AUTHOR et al YEAR, Genome Research](paperlink).




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





