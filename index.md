---
layout: cv
title: Justin Vrana's CV
---

<!-- ### TODO update project description, update summary -->


# Justin Vrana 

<div class="profilepic">
  <img src="https://secure.gravatar.com/avatar/34f83b6276a1d76d40684e503179e6cd?s=200">
</div>

> sythetic biologist \| software engineer


<div id="webaddress">
<a href="mailto:justin.vrana@gmail.com">justin.vrana@gmail.com</a>
| <a href="https://jvrana.github.io/markdown-cv/">jvrana.github.io</a>
| <a href="https://www.linkedin.com/in/justin-vrana-bioe/">LinkedIn</a>
| <a href="https://www.github.com/jvrana">GitHub</a>
| <a href="https://scholar.google.com/citations?user=X5KqrDIAAAAJ&hl=en">Google Scholar</a>
| <div itemscope itemtype="https://schema.org/Person"><a itemprop="sameAs" content="https://orcid.org/0000-0002-0862-0824" href="https://orcid.org/0000-0002-0862-0824" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon">https://orcid.org/0000-0002-0862-0824</a></div>
</div>

<hr>

## Currently

**PhD Candidate in Bioengineering at the University of Washington**<br>*(expected graduation: June 2021)*

### Research interests

Synthetic biology \| cellular computation \| computer-aided design and manufacturing \| laboratory automation \| democratization of science

## Summary

I am a trained researcher with 10 years experience in software engineering and synthetic biology.
I believe in the power of using biology as an engineering medium to improve our world. To this end,
I am passionate about building genetic and software tools that facilitate rapid prototyping and engineering
of new organisms.

During my PhD work, I have built among the 
[largest genetic circuits using CRISPR in Baker's yeast (2017)](https://www.nature.com/articles/ncomms15459).
Currently, I am working on high-throughput genetic circuit characterization methods in human cells
and using deep learning to understand synthetic gene circuits. Additionally, I am working with [DAPRA](https://www.darpa.mil/program/synergistic-discovery-and-design)
to develop a computer-aided manufacturing system to automate the design-build-test-learn cycle
for engineered organisms. I've worked on several projects related to lab automation,
including an Amazon Catalyst-backed project for developing a mammalian engineering cloud laboratory and
a collaborative project to improve reproducibility of clinical laboratory tests in low-resource settings 
using human-in-the-loop automation.

I am currently finishing up a few projects and related publications before 
my anticipated graduate in 2019/2020. I am searching
for jobs at intersection of software engineering and synthetic biology.

## Education

`2014-2020`
__Ph.D, University of Washington-Seattle (expected 2019/2020)__

Department of Bioengineering

Advisor: Eric Klavins

Dissertation: Automating the design and construction of engineered S. cerevisiae strains using end-to-end computer-aided design, planning, and manufacturing.

`2007-2010`
__BS, University of Wisconsin-Madison__
- Department of Chemistry (Honors in the Major)
- Department of Philosophy
- _Graduation with Distinction_
- _Dean's List (2007-2011)_

`2009-2010`
__Certificate in Computer Science, University of Wisconsin-Madison__

## Technical Skills

### Computation

Programming Languages: Python, Ruby, JavaScript, Java, C/C++, BASH

Web Development: Flask, Ruby on Rails, React, Jekyll, HTML, CSS, Bootstrap

Software tools: Git, GitHub, Docker, Docker-Compose, SQL, UNIX commands

Modeling and data analysis: TensorFlow, graph neural networks, NumPy, SciPy, dynamical modeling, ODE simulation/modeling

### Wetlab

Yeast: cell culture, transformations, genomic integrations, CRISPR multiplex integration

Mammalian: cell culture, plasmid transfections, lentivirus production, microscopy

Molecular biology: gibson assembly, golden gate, HT library cloning

Assay: flow cytometery, cell sorting, Illumina NGS, single-cell RNA Seq

## Awards

`2018`
[__DLA Piper $2,500 Best Idea with Global Reach__](https://bioe.uw.edu/a-alpha-bio-nanodropper-ola-simple-finish-strong-win-32500-at-2018-uw-business-plan-competition/)
For for OLASimple, a start up centered around a drug-resistance detection diagnostic
and accompanying lab automation software.

`2018`
[__UW Business Plan Competition (Final 16)__](https://blog.foster.uw.edu/sweet-16-2018-uw-business-plan-competition/)
For business plan for OLASimple.

`2017`
[__$100K Amazon Catalyst Grant__](https://catalyst.amazon.com/uw/projects/)
For UW BIOFAB, a cloud laboratory for genetic engineering to expand to automated
mammalian cell work.

`2015`
[__Top prize, 2015 CSN Sandbox Competition__](http://www.csne-erc.org/engage-enable/post/vertigone-takes-top-prize-2015-tech-sandbox-competition)
For VertiGone, an app & hardware that detects the onset of a fall and helps reorient patients using 3D auditory cues.

`2010`
Phi Beta Kappa

`2010`
iGEM Gold Award

`2008`
Sophomore Honors Research Apprentice Grant

`2007-2010`
William F. Vilas Grant

`2007-2011`
Anthony Delorenzo Grant

## Software Projects

`2019-present`
[Terrarium](https://github.com/jvrana/Terrarium)<br>
Terrarium is a dynamic computer-aided process planner ([CAPP](https://en.wikipedia.org/wiki/Computer-aided_process_planning))
for biology designed for agile manufacturing of biological products, such as E Coli & Yeast strains, or Mammalian cell
lines. The software automatically plans scientific experiments in Aquarium using historical planning data and current
laboratory inventory and solves an MST optimization problem to give optimal and valid operational workflows.

`2017-present`
[DASi Automated DNA Assembly](https://github.com/jvrana/DASi-DNA-Design)<br>
DASi is an automatic DNA cloning plan designer aimed for operating on small budgets by
focusing on material re-use and a dead-simple user interface. The software converts a nucleotide sequence,
or a library of sequences, to an executable molecular assembly plan while optimizing material cost, assembly
efficiency, and assembly time. No molecular biology expertise is required to use DASi.
DASi produced plans can be automatically executed using a biofabrication facility
(such as the [UW-BIOFAB](http://www.uwbiofab.org/).

`2016-present`
[Aquarium](https://www.aquarium.bio/)/[Trident](https://github.com/klavinslab/trident)<br>
Aquarium, a open-source human-in-the-loop laboratory automation system that enables rapid,
flexible, and reproducible workflow development and execution. Trident (developed by Justin Vrana),
is the fully-featured Python interface for Aquarium that allows high-throughput scripted experiment
submission, fast data mining, and machine learning on experimental data.

### Mini Projects

[BenchlingAPI](https://github.com/klavinslab/benchling-api) The unofficial Python API for Benchling.

[jdna](https://jvrana.github.io/jdna/index.html) A Python DNA sequence editor that represents sequences as a linked
list. It includes basic molecular reaction simulations and a viewer class.

[pyblast-bio](https://github.com/jvrana/pyblast) Python wrapper for installing and using NCBI's BLAST algorithms.

[keats](https://github.com/jvrana/keats) Keats is a Python build, installation, and workflow manager.

## Experience

`2018-present`
[**Researcher for DARPA Synergistic Design and Discovery (SD2)**](https://www.darpa.mil/program/synergistic-discovery-and-design)
UW-Seattle<br>
I am currently the lead for design and build for yeast construction for the SD2 DARPA program, for which
I consult on building genetic circuit and act as software developer. I have developed python-based automation tools
 for automating the design and build of engineered yeast strains.
Borrowing concepts from computer-aided manufacturing, I created the first computer-aided process planner 
for biology, allowing researchers to design and build new plasmids and yeast strains with no prior knowledge of
molecular biology or laboratory operations. Currently, I am working with mathematicians at Duke and 
Montana State University to implement and test a new dynamic genetic circuit design tool. So far, we have used
the automation tools I have developed to automatically design experiments to build and test 350 new yeast strains and
plan over 2000 laboratory operations. Using docker and cloud computing tools, I deployed my software to 
the Texas Advanced Computer Center (TACC) cluster for automated integration with other teams within the program.


`2014-present`
**Graduate Researcher** UW-Seattle<br>
Lab of Eric Klavins, Deparment of Bioengineering<br>
I designed, built and tested genetic circuits for digital computation using CRISPR/dCas9
in yeast. At the time (2017), built the largest genetic circuit ever constructed in a 
eukaryote. Performed mathematical modeling of behavior and fitted experimental results using
differential evolution optimization. Performed parameter sensitivity analysis. In addition to this
research, I have also performed continuous development and testing of Aquarium, a laboratory operating system for 
reproducible experimental execution. I was the main developer for Aquarium's Python API and machine 
learning tools for data mining and experiment design tools, contributing over 350K lines of code.

`2017-2019`
**Software lead**, OLA Simple, Seattle, Washington<br>
I was the lead for the automation software that paired with an innovative point of care lab diagnostics. I developed
code (Ruby/Ruby-on-Rails/Docker) the provides inventory tracking and highly reproducible protocol instruction 
for clinical diagnostic assay to detect drug-resistance in HIV patients. I traveled to  implemented
the diagnostic kit and software in Nairobi, Kenya to simulate low-resource settings. 98% of new users were able
successfully complete diagnostic assay using the automation software.

`2017-2018`
**Amazon Catalyst Fellow** UW-Seattle<br>
Development of digitally guided protocols and workflows in which users are able to design custom mammalian cell lines,
develop experimental workflows to assay them, view and analyze data, and execute experiments, all from the comfort of
a coffee shop.

`2016-2017`
**Workflow Developer** UW BIOFAB, University of Washington-Seattle<br>
Founding member of the synthetic biology foundry UW-BIOFAB. Developed highly reproducible
human-in-the-loop automation workflows for molecular cloning and yeast
strain construction. Consulted team on scientific validity of experiments 
and procedure.

`2011-2014`
**Research Assistant** University of Colorado-Denver<br>
Lab of Chandra Tucker. 
Developed light inducible systems for gene expression, protein targeting, endocytosis, actin
polymerizationin both yeast and mammalian cells. Characterized light dependent dimerization of 
phytochrome and cryptochrome proteins to develop novel red/blue light inducible protein dimerization 
systems. Analyzed of non-amyloid protein aggregation to understand protein recycling in yeast and 
mammalian cells. Developed code and hardware for optogenetic [light delivery systems](https://github.com/jvrana/OptogeneticsLightBox).

`2008-2011`
**Research Assistant** University of Wisconsin-Madison<br>
Lab of David C Schwartz, Department of Chemistry and Genetics<br>
Developed platform for single molecule dynamic studies and confined 2-dimensional biochemistry. 
Used lab built genomic optical mapping to construct low-resolution genome maps for bacterial, plant, and human genomes.
Used university high-throughput computing cluster to assembly whole genomes.

`2010–2011`
**Research Intern** University of Wisconsin International Genetically Engineered Machines Team (iGEM)<br>
Lab of Brian Pfleger, Department of Chemical and Biological Engineering<br>
Developed of recombination based genetic circuit in E. Coli for detection of sequential environmental input
Developed of bacterial peptide delivery system for probiotic therapy.

`2008-2009`
**Undergraduate Research Scholar** University of Wisconsin-Madison<br>
Lab of Lingjun Li, Department of Chemistry<br>
Used MALDI TOF/TOF mass spectrometry to analyze
peptide-level responses to environmental stress in crustaceans.

`2007-2008`
**Undergraduate Researcher** University of Wisconsin-Madison<br>
Lab of Mark Brownfield, School of Veterinary Medicine.<br>
Used immunihistochemistry to identify lcoation of serotonin receptor 
variants in rat brain and adrenal glands.

## [Publications](https://scholar.google.com/citations?user=X5KqrDIAAAAJ&hl=en)

<!-- A list is also available [online](https://scholar.google.com/citations?user=X5KqrDIAAAAJ&hl=en) -->

### Journals

`2021`
**Aquarium: open-source laboratory software for design, execution and data management**
__Justin Vrana__, Orlando de Lange, Yaoyu Yang, Garrett Newman, Ayesha Saleem, Abraham Miller, Cameron Cordray, 
Samer Halabiya, Michelle Parks, Eriberto Lopez, Sarah Goldberg, Benjamin Keller, Devin Strickland, Eric Klavins
Oxford University Press Synthetic Biology (accpeted)

`2021`
**Simpler and faster Covid-19 testing: Strategies to streamline SARS-CoV-2 molecular assays**
Nuttada Panpradist, Qin Wang, Parker S Ruth, Jack H Kotnik, Amy K Oreskovic, Abraham Miller, Samuel WA Stewart, 
__Justin Vrana__, Peter D Han, Ingrid A Beck, Lea M Starita, Lisa M Frenkel, Barry R Lutz
EBioMedicine 64, 103236

`2019`
**OLA-Simple: A software-guided HIV-1 drug resistance test for low-resource laboratories**
N Panpradist, IA Beck, __J Vrana__, N Higa, D McIntyre, PS Ruth, I So, ...
EBioMedicine 50, 34-44

`2017`
**Digital logic circuits in yeast with CRISPR-dCas9 NOR gates.**<br>
MW Gander, __JD Vrana__, WE Voje, JM Carothers, E Klavins<br>
Nature communications 8, 15459

`2016`
**Benchmarking of optical dimerizer systems.**<br>
GP Pathak, D Strickland, __JD Vrana__, CL Tucker<br>
ACS synthetic biology 3 (11), 832-838

`2014`
**Peripheral nervous system defects in a mouse model for peroxisomal biogenesis disorders**<br>
MG Hanson, VL Fregoso, __JD Vrana__, CL Tucker, LA Niswander<br>
Developmental biology 395 (1), 84-95

`2014`
**An optimized optogenetic clustering tool for probing protein interaction and function**<br>
A Taslimi, __JD Vrana__, D Chen, S Borinskaya, BJ Mayer, MJ Kennedy, CL Tucker<br>
Nature communications 5, 4925

`2014`
**Tools for controlling protein interactions using light**<br>
CL Tucker, __JD Vrana__, MJ Kennedy<br>
Current protocols in cell biology 64 (1), 17.16. 1-17.16. 20

`2013`
**Optical control of protein-protein interactions to modulate cellular function**<br>
A Taslimi, G Pathak, __JD Vrana__, CL Tucker<br>
CLEO: 2013, 1-2

`2013`
**Optogenetic control of cell function using engineered photoreceptors**<br>
GP Pathak\*, __JD Vrana__\*, CL Tucker<br>
Biology of the Cell 105 (2), 59-72
\*co-first author

`2012`
**Rapid profiling of disease alleles using a tunable reporter of protein misfolding**<br>
AMC Pittman, MD Lage, V Poltoratsky, __JD Vrana__, A Paiardini, A Roncador, CL Tucker<br>
Genetics 192 (3), 831-842

`2012`
**Light-dependent, dark-promoted interaction between Arabidopsis cryptochrome 1 and phytochrome B proteins**<br>
RM Hughes, __JD Vrana__, J Song, CL Tucker<br>
Journal of Biological Chemistry 287 (26), 22165-22172

### In Preparation<br>(08/2019)

`2019`
**Development and evaluation of OLA-Simple 1.0: a software-guided test kit for low-resource laboratories to detect drug resistance in HIV**<br>
Nuttada Panpradist, Ingrid A. Beck, __Justin Vrana__, Nikki Higa, David McIntyre, Parker S. Ruth, Isaac So,
Enos C. E. Kline, Ross Milne, Ruth Kanthula, Annie Wong-On-Wing, [...], Jaime Soria, James Lai, Eric Klavins, Lisa M. Frenkel, Barry R. Lutz<br>
Science Translational Medicine (__in review__)

`2019`
**Implementation of an interactive mobile application to pilot a same-day HIV drug resistance assay from whole-blood in Kenya.**<br>
**Justin Vrana**, Ingrid A  Beck, Nuttada Panpradist, Nikki Hilga, Daisy Ko, Ruth Kanthula, Bhavna Chohan, James Lai, Michael Chung, Eric Klavins, Lisa M Frenkel, Barry Lutz<br>

`2019`
**End-to-end integration of experiment design, execution and analysis for engineered biological systems.**<br>
**Justin Vrana**, Ben Keller, Dany Fu, Andrei Lapets, Douglas Densmore, Eric Klavins<br>

`2020`
**Characterization and design of CRISPR-based cellular information processing systems in mammalian cells using single cell RNA-Seq.**<br>
**Justin Vrana**, Eric Klavins<br>

### Invited Talks

`2019`
**Aquarium: a laboratory operating system for reproducible experimental design and execution**
SIMB (Society for Industrial Microbiology and Biotechnology), Automation session, Washington, D.C.

### Poster Presentations

`2019`
**Software-Enable Design and Automated Construction of CRISPR Gene Circuits in S. cerevisiae**
Poster and lightning talk.
SEED (Synthetic Biology: Engineering, Evolution, and Design), New York City, NY

`2016`
**Rational Design of Large Crispr/dCas9 Transcriptional Logic Circuits in Eukaryotic Cells**
Poster and lightning talk.
SEED (Synthetic Biology: Engineering, Evolution, and Design), Chicago, IL

## Teaching

`2019`
**Teaching Assistant**, UW-Seattle
Electrical and computer engineering 590: Advanced Programming for Embedded Systems.
Course on C/C++. Embedded device communication using C/C++. Google testing framework. Automated grading scripts.

## Projects in the News

`2018`
[UW News - A-Alpha Bio, Nanodropper, OLASimple finish stron, win $32,500 at 2018 UW Business Plan Competition](https://bioe.uw.edu/a-alpha-bio-nanodropper-ola-simple-finish-strong-win-32500-at-2018-uw-business-plan-competition/)

`2017`
[GeekWire - UW researchers reprogram genetic code to create digital circuitry inside living cells](https://www.geekwire.com/2017/uw-researchers-turn-living-cells-logic-gates-digital-circuitry/)

`2017`
[UW engineers borrow from electronics to build largest circuits to date in living eukaryotic cells](https://www.washington.edu/news/2017/05/25/uw-scientists-borrow-from-electronics-to-build-largest-circuits-to-date-in-living-eukaryotic-cells/)

`2015`
[VertiGone takes top prize at 2015 Tech Sandbox competition](http://www.csne-erc.org/engage-enable/post/vertigone-takes-top-prize-2015-tech-sandbox-competition)

`2015`
[Changing the world: Faculty and students demonstrate CSE’s impact to the UW Foundation Board](https://news.cs.washington.edu/2015/09/15/changing-the-world-faculty-and-students-demonstrate-cses-impact-to-the-uw-foundation-board/)

<!-- ### Footer

Last updated: August 2019 -->


