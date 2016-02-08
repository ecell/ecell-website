# What is E-Cell System?

E-Cell System is a software platform for modeling, simulation and analysis of complex, heterogeneous and multi-scale systems like the cell.

# Who is using E-Cell System?

## Featured publications

Please see our extensive [collection of publications](http://ecell.github.io/publications/) that leverage E-Cell System.

For additional E-Cell project news and events, please follow [@ecellproject][https://twitter.com/ecellproject] on Twitter.

## Research using E-Cell system

Many publications are citing [Tomita et al. (1999)](http://bioinformatics.oxfordjournals.org/content/15/1/72.short)
View [Full Listing at Google Scholar](https://scholar.google.co.jp/scholar?cites=12647933210797842846)

# History

## Launching of the E-Cell Project — 1996

In the spring of 1996, students at the Labratory for Bioinformatics at Keio University SFC (Shonan-Fujisawa campus), started a study group devoted to investigating the molecular biology of Mycoplasma genitalium, the orgamism with the smallest known genome. Under the leadership of Prof. Masaru Tomita, we transformed this group into the E-Cell Project by the end of the year, which aims at reconstruction of a whole cell in silico. The initial ambition of the project was to create a simulation model of a hypothetical cell that contains a minimum gene set for survival based on the tiny organism M. genitalium, whose complete 580kb genome sequence had only been determined in the previous year. This led to the successful design and development of the first working version of the E-Cell System by Koichi Takahashi (see History of E-Cell System below).

## Self Sustaining Cell model with 127 genes — 1997

By August and September 1997, the software had been used in a collaborative project between Keio and TIGR (The Institute for Genomic Research), which aimed at in silico reconstruction of a virtual hypothetical cell with 127 genes, based on Mycoplasma genitalium, which was designed to self-sustain by producing energy from glucose with the enzymes created from its genes. In addition to Prof. Tomita and Takahashi, Kenta Hashimoto, Thomas Shimizu, Katsuyuki Yugi, Yuri Matsuzaki, Fumihiko Miyoshi, Kanako Saito, and Sakura Tanida participated in this project, held at a temporary lab in Baltimore, MD, USA. Drs. C. Hutchson and J. C. Ventor of TIGR ultimatly co-authored papers based on the results of this work.

The self-sustaining cell with 127 genes is a hypothetical cell that contains a minimum gene set for survival. We borrowed the genomic construction from Mycoplasma genitalium to build our first virtual cell, designed to conduct what we call “minimum cellular metabolism”. This model takes up glucose from the culture medium using a phosphotransferase system, generates ATP by catabolizing glucose to lactate through glycolysis and fermentation, and exports lactate out of the cell. Enzymes and substrates are spontaneously synthesized and degraded over time to sustain ‘life’. Protein synthesis is implemented by modeling the molecules necessary for transcription and translation, namely RNA polymerase, ribosomal subunits, rRNAs, tRNAs and tRNA ligases. The cell also takes up glycerol and fatty acid, and produces phosphatidyl glycerol for membrane structure using a phospholipid biosynthesis pathway. The model cell is ‘self supporting’, but not capable of proliferating; the cell does not have pathways for DNA replication or the cell cycle.

## Towards modeling real cells — 1998 –

Our next project was to model real cells and to develop a more sophisticated simulation environment for biological simulations. New modeling projects for modeling a human erythrocyte, mitochondrion, E.coli chemotaxis, and gene expression/replication were set up. Over time, the number of projects and members grew to encompass large scale modeling projects, such as E2coli, myocardial cells, neural cells, plant cells, and also mathematical analysis projets for developing methods to estimate parameters and analyzing simulation results. To reach a wider group of scientists and modelers, a Windows version of the software, E-Cell version 2, was ported by Naota Ishikawa and Mitsui Knowledge Industry, while developers at the E-Cell project concentrated on constructing a more versatile simulation environment for cell modeling, E-Cell version 3.

## The Institute for Advanced Biosciences — 2001 –

Significant advances in techniques and the abundance of genome, proteome and metabolome data have had a major impact on development in the field of computational biology. The Institute for Advanced Biosciences, Keio University, was established in April 2001, consisting of several research units, including the Metabolome unit, Bioinformatics unit, and Genome Engineering unit. These research groups focus on advanced systems biology research such as proteomics, transcriptomics, metabolomics, and genome engineering, with a strong coupling with genome informatics, cell modeling, biological simulation, and computational (in silico) biology. Scientists across various different disciplines are currently working together towards the realization of cell simulation and engineering.

## Growing enterprise — present

The year 2006 will be marked as the start of the next stage of evolution towards ‘E-Cell Project Version 2.0’. The E-Cell Project has been experiencing a thorough reorganization into an even more distinct focuses in the areas of technological development under the leadership of the E-Cell Project Steering Committee, which has been newly formed in the year. While the Institute for Advanced Biosciences continues to function as the headquarters of the Project, two more institutions joined the project by 2005; The Molecular Sciences Institute, Berkeley, USA, and Mitsubishi Space Software, Co. Ltd, Amagasaki Japan.

## History of E-Cell System

In the October of 1996, Prof. Masaru Tomita recruited several undergraduate and graduate students in his lab to join the E-Cell Project, still in its pre-launching stage, for the development of software that can graphically represent dynamic changes in activities of genes. Those students worked in a competitive way with a variety of computational approaches. On November 15th, Koichi Takahashi, a junior undergraduate at the time, gave a presentation in which he proposed (1) the project to focus on the kinetic dynamics of metabolic pathways and the control of enzyme productions through the expressions of genes, and (2) development of a generic software system based on object-orientation in C++ language. The software was initially named ECL (Electronic Cell Laboratory), and was later given the current name ‘E-Cell System’, or ‘Electronic Cell System’, by Kenta Hashimoto, a senior in the lab. In December 29th, Takahashi made an internal release of an alpha version (version 0.0-pre) of the software to lab members. The first user of E-Cell System, who had been testing the software from the ‘pre-alpha’ days, was Riow Matsushima, a junior at the time. This 3,500-line C++ piece of software had a minimum set of functionalities necessary to model and simulate a system of enzymatic reactions in a fully object-oriented way.

The object-model of this version defined two fundamental classes called primitives, ‘Substance’ and ‘Reactor’ for representations of molecular species and reactions, respectively, and was called the ‘Substance-Reactor’ model. By the end of the March, 1997, this object-model had given another primitive class called ‘System’, to model physical and logical (or functional) compartments in the cell. Hashimoto and Thomas S. Shimizu, a master student, contributed the discussion about this ‘Structured Substance-Reactor’ object model. Hashimoto also created a class of Reactor which calculates a chemical equilibrium. By the summer of 1997, Hashimoto participated in the development of a set of classes for simulation of gene expressions, and Yasuhiro Asakawa, a master student, and Katsuyuki Yugi, a junior in that year, developed a GUI component called ‘GeneMapWindow’ to graphically represent activities and amounts of products (mRNA molecules) of many genes.

The version of the software used in the ‘camp’ in Baltimore to create the Self-Sustaining Cell model (see History of the E-Cell Project above) further developed to become the version ‘1.0beta’ with helps from many contributors. The initial public release of the version happened on March 2nd, 2000, under the E-Cell Beta-testing License. On October 13th, 2000, E-Cell 1 had been accepted by the Bioinformatics.org as an OpenSource project under the terms of GNU General Public License.

Development projects of two other versions of E-Cell System, E-Cell 2 and E-Cell 3, had started in 2000. E-Cell 2, developed by Naota Ishikawa and Mitsui Knowledge Industory, is a Windows port of E-Cell 1 which ran only on Linux operating system. E-Cell 3, initially started its development on Bioinformatics.org and later moved to Sourceforge.net in early 2003, is a complete reconstruction of E-Cell 1. E-Cell 3 can be viewed as an object-oriented computation platform on which any types of simulation algorithms can work together in any combination. In E-Cell 3, the ‘Substance-Reactor’ model of E-Cell 1 has been renamed to ‘Variable-Process’ model for further flexibility in modeling.
