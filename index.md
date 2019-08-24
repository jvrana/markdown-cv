---
layout: cv
title: Justin Vrana's CV
---
<!-- ### TODO update project description, update summary -->


# Justin Vrana
Synthetic biologist, researcher, programmer

<div id="webaddress">
<a href="mailto:jvrana@uw.edu">jvrana@uw.edu</a>
| <a href="https://jvrana.github.io/markdown-cv/">jvrana.github.io</a>
| <a href="https://www.linkedin.com/in/justin-vrana-bioe/">LinkedIn</a>
| <a href="https://www.github.com/jvrana">GitHub</a>
| <a href="https://scholar.google.com/citations?user=X5KqrDIAAAAJ&hl=en">Google Scholar</a>
</div>

## Currently

**PhD Candidate in Bioengineering at the University of Washington**<br>*(expected graduation: 2019/2020)*

### Research interests

Synthetic biology \| cellular computation \| computer-aided design and manufacturing \| laboratory automation \| democratization of science

## Summary

I am a trained engineer with 10 years experience in software engineering and synthetic biology.
I believe in the power of using biology as an engineering medium to improve our world. To this end,
I am passionate about building genetic and software tools that facilitate rapid prototyping and engineering
of new organisms.

During my PhD work, I have built among the 
[largest genetic circuits using CRISPR in Baker's yeast (2017)](https://www.nature.com/articles/ncomms15459).
As an extension to this work, I am currently developing a one-pot high-throughput single cell RNA-seq assay for
characterizing 100,000s of randomly generated genetic circuits in human cells, and am employing deep learning
to understand genetic part performance.

Additionally, I am working with [DAPRA](https://www.darpa.mil/program/synergistic-discovery-and-design)
to develop a computer-aided manufacturing system to automate the design-build-test-learn cycle
for engineered organisms. To automate experiments, we use the [Aquarium](https://www.aquarium.bio), a lab operating system that automates
and tracks experiment execution using human-in-the-loop automation. I have built out a fully-featured Python
interface for this system ([Trident](www.github.com/klavinslab/trident)). Using these tools, I have recently
deployed machine-learning to automate *S. cerevisiae* strain construction and are currently using the 
software ([Terrarium](www.github.com/jvrana/Terrarium)) to engineer new cell behaviors in yeast using CRISPR 
dCas9 gene circuits.

I am currently finishing up these two projects before my anticipated graduate in 2019/2020 and am looking
for jobs at intersection of software engineering and synthetic biology.

## Education

`2014-2020`
__Ph.D, University of Washington-Seattle (expected 2019/2020)__

Department of Bioengineering

Advisor: Eric Klavins

Dissertation: Automating the design and construction of engineered S. cerevisiae strains using end-to-end computer-aided design, planning, and manufacturing.

`2007-2010`
__BS (Honors), University of Wisconsin-Madison__
- Department of Chemistry (Honors in the Major)
- Department of Philosophy
- _Graduation with Distinction_
- _Dean's List (2007-2011)_

`2009-2010`
__Certificate in Computer Science, University of Wisconsin-Madison__

## Technical Skills



### Computation

Programming Languages: Python (strong), Ruby (strong), JavaScript, Java, C/C++

Web Development: Ruby on Rails, React, Jekyll, HTML, CSS, Bootstrap

Software tools: Git, GitHub, BASH/UNIX commands

Modeling and data analysis: TensorFlow, NumPy, SciPy, graph neural networks, dynamical modeling, ODE simulation/modeling

### Wetlab

Yeast: cell culture, transformations, genomic integrations, CRISPR multiplex integration

Mammalian: cell culture, plasmid transfections, lentivirus production, microscopy

Molecular biology: gibson assembly, golden gate, HT library cloning

Assay: flow cytometery, cell sorting, illumina NGS, single-cell RNA Seq

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
submission, fast data mining, and LIMS browsing.

### Mini Projects

[BenchlingAPI](https://github.com/klavinslab/benchling-api) The unofficial Python API for Benchling.

[jdna](https://jvrana.github.io/jdna/index.html) A Python DNA sequence editor that represents sequences as a linked
list. It includes basic molecular reaction simulations and a viewer class.

[pyblast-bio](https://github.com/jvrana/pyblast) Python wrapper for installing and using NCBI's BLAST algorithms.

[keats](https://github.com/jvrana/keats) Keats is an Python build, installation, and workflow manager.

## Experience

`2018-present`
[**Researcher for DARPA Synergistic Design and Discovery (SD2)**](https://www.darpa.mil/program/synergistic-discovery-and-design)
UW-Seattle
Cloud computing. Automation tools. End-to-end design, planning, and manufacturing tools for biology. TACC infrastructure.


`2014-present`
**Graduate Researcher**, Lab of Eric Klavins, UW-Seattle<br>
Transcriptional logic. Dynamic genetic circuits. Biophysical modeling.

`2018-present`
**Software lead**, OLA Simple, Seattle, Washington
Lead for automation software for innovative point of care lab diagnostics. Developed
code (Ruby/Ruby-on-Rails/Docker) the provides inventory tracking and highly reproducible protocol instruction 
for clinical diagnostic assay to detect drug-resistance in HIV patients. Successfully implemented
the diagnostic kit and software in Nairobi, Kenya to simulate low-resource settings.
51/52 of researchers were able to successfully complete diagnostic assay
using the software, many having never touched a pipette before.

`2017-2018`
**Amazon Catalyst Fellow** UW-Seattle<br>
Development of digitally guided protocols and workflows in which users are able to design custom mammalian cell lines,
develop experimental workflows to assay them, view and analyze data, and execute experiments, all from the comfort of
a coffee shop. Developed automation workflows for mammalian cell synthetic biology, including
culturing, transfections, & lentiviral production and transfections.

`2016-2017`
**Workflow Developer** UW BIOFAB, University of Washington-Seattle<br>


`2011-2014`
**Research Assistant**<br> University of Colorado-Denver<br>
Lab of Chandra Tucker. Optogenetics. Protein clustering. Yeast and mammalian synthetic biology.

`2008-2011`
**Research Assistant** University of Wisconsin-Madison<br>
Lab of David Schwartz. Optical and genomic mapping.


## [Publications](https://scholar.google.com/citations?user=X5KqrDIAAAAJ&hl=en)

<!-- A list is also available [online](https://scholar.google.com/citations?user=X5KqrDIAAAAJ&hl=en) -->

### Journals

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


