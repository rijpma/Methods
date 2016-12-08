# Methods of historical research

## General introduction

The purpose of this course is to familiarize students of the Research MA programme History with computational techniques to analyse structured and unstructured data. More and more historians are using large sets of digital data as well as a growing variety of digital techniques to extract information from this data. Scholars are discussing the disruptive nature of these increasingly common practices for historical scholarship under the header of Digital Humanities and Digital History. It is not only timely to become acquianted with a number of widely used techniques and skills, but also to learn how to use them for the study of history in a critical and conscientious way. A last goal of this course is to provide students with sufficient information to form their own opinion of the extent to which digital resources and tools change the heuristics of historical enquiry.

This course is split up in two parts to acquaint students with tools for the analysis of, respectively, unstructured (textual) and structured (numerical) historical data. Students are trained in the offered analytical tools in a ‘hands on’ setting, in which they work on their own research projects. During the first part of this course, students will work in groups on a comparative study of two (or more) texts or corpora. The research projects are meant to compare the methods of conventional comparative research with the functionalities that computational techniques from corpuslinguistics and unsupervised clustering (topic modeling) offer. Students will have to reflect in their research projects on the opportunities, but also the risks and pitfalls of digital tools for this type of historical study. More generally, they will evaluate and discuss the strengths and weaknesses of a selection of books, articles, and working papers that employ digital humanities methods with these tools.

### Grading
The grade will consist of four parts:

1. Participation in the first half of the course, including the assignments (10%).
2. The paper for the first half of the course (40%).
3. Participation in the second half of the course, including the assignments (10%),
4. The paper for the second half of the course (40%).

To pass the course you must get at least a 5 for both the papers. If the final grade of the course is between a 4 and a 5.5, you may repair the paper for which you got the lowest grade. Points will be subtracted from the grade if you hand in a paper late.

## Part 1: Unstructured data

### Week 1: Introduction
Introduction to the course & starting up research projects

#### Readings week 1
* Tim Hitchcock, 'Confronting the Digital. Or: How Academic History Writing Lost the Plot', _Cultural and Social History_ 10 (2013), pp. 9-23.
* Bob Nicholson, 'The Digital Turn', _Media History_ 19 (2013), pp. 59-73.
* Joris van Eijnatten, Toine Pieters, Jaap Verheul, ‘Big data for global history: The transformative promise of digital humanities’, _BMGN-LHCR_ 128 (2013) 55-77.

### Week 2
Corpuslinguistics & the use of AntConc for the study of history

#### Readings week 2
* Franco Moretti, Dominique Pestre, ‘Bankspeak. The language of World Bank Reports’, _New Left Review_ 92 (2015) 75-99.
* Michael Pearce, ‘Investigating the collocational behaviour of man and woman in the BNC using Sketch Engine’, _Corpora_ 3 (2008) 1-29.
* Trevor Owens, [‘Defining data for humanists: text, artifact, information or evidence?’](http://journalofdigitalhumanities.org/1-1/defining-data-for-humanists-by-trevor-owens/), _Journal of Digital Humanities_ 1 (2011)

#### Rescources week 2
[AntConc website](http://www.laurenceanthony.net/software/antconc// "AntConc website")

[AntConc tutorials on Youtube](https://www.youtube.com/user/AntlabJPN/ "AntConc tutorials")

### Week 3
Topic modeling

#### Readings week 3
* John W. Mohr, Petko Bogdanov, ‘Topic models: What they are and why they matter’, _Poetics_ 41 (2013) 545-569
* Cameron Blevins, ['Topic modeling Martha Ballard's diary](http://www.cameronblevins.org/posts/topic-modeling-martha-ballards-diary/), _Cameronblevins.org_, April 1 (2010)
* Introduction of [Mining the Dispatch website](http://dsl.richmond.edu/dispatch/pages/intro)

#### Resources week 3
[Mallet LDA website](http://mallet.cs.umass.edu/index.php)

### Week 4
The future of Digital History & students' presentations

#### Readings week 4
* Jean-Baptiste Michel et al. 'Quantitative Analysis of Culture Using Millions of Digitized Books', _Science_ 331 (2011), pp. 176 -182
* Eitan A. Pechenick et.al., ‘Characterizing the Google Books Corpus: Strong limits to inferences of socio-cultural and linguistic evolution’, _PLOS One_ 10 (2015)
* David Berry, ['Post-Digital Humanities: Computation and Cultural Critique in the Arts and Humanities'](http://er.educause.edu/articles/2014/5/postdigital-humanities-computation-and-cultural-critique-in-the-arts-and-humanities), _Educause_ Review 19-05-2014

## Part 2: Structured data

### Preparations
Make sure to have R installed beforehand. You can use [the standard R installation](https://www.r-project.org), but many find the [R-studio version](https://www.rstudio.com) pleasant to work with. Either way, try to get it up and running before the first tutorial (Wed. 12), so we can address any issues before the first lab session (Fri. 14). Once you're up and running, have a look at the first videos of [Google's R-intro for beginners](http://www.youtube.com/playlist?list=PLOU2XLYxmsIK9qQfztXeybpHvru-TrqAP)

### Week 5
#### Tutorial: the quantitative approach to history.
Using the articles you brought with you, we will use this session to discuss about the pros and cons of quantitative research. The other readings (Cleveland) are in preparation for next week but will not be discussed. 
#### Readings:
* Cleveland, _The elements of graphing data_ (Monterey 1985), pp. 3--101. Book available on course reserve shelf from Monday onwards -- please do not reserve it.

#### Assignment:
* For the first tutorial, everyone is to find an interesting ppaer using quantitative methods and structured data (interesting because of its topic and findings, not necessarily because of the methodology). Please read this article and prepare some discussion points for class. Distribute the article itself to your teacher and fellow students no later than 17.00 on Tuesday.

#### Lab session:
Basics of working with data in R.

### Week 6: Visualising data.
#### Tutorial: visualising data
#### Readings
* Cleveland, pp. 103--227

#### Assignments:
* Choose a dataset from the [datasets section](##Datasets) that you would like to write your paper about. Browse the documentation and explore the dataset. Prepare a short presentation where you discuss the content of the dataset and explain what question you would like to answer with it.
* Find a striking visualisation on the internet or in a journal and distribute it to your teacher and fellow students no later than 17.00 on Tuesday. Prepare a short introduction of the visualisation and explain what you liked about it.

#### Lab session:
* Visualising data

### Week 7:
#### Tutorial: evaluating research
#### Readings:
* https://aeon.co/essays/it-s-time-for-science-to-abandon-the-term-statistically-significant
* http://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0020124
* http://pps.sagepub.com/content/9/6/641.full.pdf+html
* http://rsos.royalsocietypublishing.org/content/1/3/140216

#### Assignment:
* In the tutorials in weeks 5 and 6 there has been ample attention for working in a reproducible way. For this assignment you will have to hand in all the files necessary to reproduce one of the visualisations of the lab session of week 6.

#### Lab session:
* Working with complex and large datasets.
* Summarising data.

### Week 8
#### Hand in paper
The paper for the second half of the course will be a short (2000 words) paper based on a large historical dataset (see the list of datasets below). The main focus should be on the discussion of the dataset, the methodology used to analyse it, and the presentation of the results, rather than the historical question itself. It should contain the following elements:

* An introduction to the historical issue.
* An introduction of the dataset.
* At least two figures or tables based on this dataset.
* Methodological reflection.
* All the files and scripts you used to obtain your results.

## Useful links
* 

## Datasets
* [North Atlantic Population Project](https://www.nappdata.org)
* [iPEHD](https://www.cesifo-group.de/ifoHome/facts/iPEHD-Ifo-Prussian-Economic-History-Database.html)
* [China Multi-Generational Panel Datasets Series](http://www.icpsr.umich.edu/icpsrweb/ICPSR/series/00265)
* [Catasto](http://www.disc.wisc.edu/archive/catasto/index.html)
* [Gould sample on Union soldiers](http://www.nber.org/gould/)
* [Union Army Data](http://uadata.org)
* [Drought atlasses](http://www.ldeo.columbia.edu/news-events/new-drought-atlas-maps-2000-years-climate-europe): [Old World](http://kage.ldeo.columbia.edu/TRL/OWDA/) [New World](http://iridl.ldeo.columbia.edu/SOURCES/.LDEO/.TRL/.NADA2004/.pdsi-atlas.html)
[Asia](http://iridl.ldeo.columbia.edu/SOURCES/.LDEO/.TRL/.MADA/), 
* [Project Tycho](http://www.tycho.pitt.edu/about.php)
* [Trans-Atlantic Slave Trade Database](http://slavevoyages.org/voyage/download)
* [Australian convict databse](https://data.gov.au/dataset/british-convict-transportation-registers)
* Any other dataset you find interesting, provided (i) it is historical, (ii) it is suffiently big and tidy; and (iii) you clear it with the instructors.

[Example of link to file](data/allen_realwage_labourers.csv)
