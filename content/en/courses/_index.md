---
header:
  caption: ""
  image: "judith_header.jpg"
title: Courses and teaching resources
type: page
---

# Biostatistic courses at uOttawa {#biostat}

Here is a short description of the course I am teaching at the University of Ottawa. For more details about the course consult the following page [Biostats-uottawa](https://biostats-uottawa.github.io) and the site for each course

### Applied biostatistics with R (BIO 4X58) {#bio4x58}



<div class="row">
  <div class="column" style = "width: 20%;">
<a href="https://biostats-uottawa.github.io/"><img src="bio4x58_logo_hex.png" align="right" alt="" width="150" /></a>
  </div>
  <div class="column"  style = "width: 80%;">

* Offered to both undergraduate and graduate students in english and french
* Prerequisite:
  * an introduction class to statisticis is good to have
  * No (or limited) knowledge of R and no (or limited) knowledge of stats expected.
* BIO4158 english ([Course site](https://biostats-uottawa.github.io/bio4158_course/) / [Course manual](https://biostats-uottawa.github.io/bio4158_manual/))
* BIO4558 french ([Course site](https://biostats-uottawa.github.io/bio4558_cours/) / [Course manual](https://biostats-uottawa.github.io/bio4558_manuel/))

</div>
</div>

### Advanced biostatistics and open science (BIO 8940) {#bio8940}

<div class="row">
  <div class="column" style = "width: 20%;">
 <a href="https://biostats-uottawa.github.io/bio8940_course/"><img src="bio8940_logo_hex.png" align="right" alt="" width="150" /></a>
  </div>
  <div class="column"  style = "width: 80%;">

* Bilingual course for graduate students
* Prerequisite:
  * a functional knowledge of R (loading data, running basic linear models, and making plots)
  * a good understanding of linear models
  * essentially Bio8940 is a great next steps after completing Bio4x58.
* [Course site](https://biostats-uottawa.github.io/bio8940_course/) / [Course manual](https://biostats-uottawa.github.io/bio8940_manual/)

  </div>
</div>




# Statistical consulting {#consult}

<div class="row">
  <div class="column" style = "width: 20%;">
<a href="https://juliengamartin.github.io/contact/"><img src="consult_logo_hex.png" align="right" alt="" width="150" /></a> 

  </div>
  <div class="column"  style = "width: 80%;">

As Part of my service, I provide statistical consulting.
Please just contact me to book an appointment to discuss your stat problems.

Please bring with you (or send me in advance):

* your data
* your R code (should at least load the data into R)
* a clear working hypothesis

Statistical consulting does not mean that you have to add me as a co-author. I just ask that you add me to the **"Acknowledgements"** of your thesis and manuscript/article. Repeated consulting on the same problem and my implication on developing project specific coding/analysis might lead to co-authorship, but this usually all comes naturally and is always discussed openly with the student(s) and PI(s). As yet, I have never requested to become a co-author and I was offered co-authorship for 3 manuscripts over > 50 projects discussed.
  </div>
</div>


# Tutorials {#tut}

## Home made books / tutorials



### Biostatistics using R {#rway}

<div class="row">
  <div class="column" style = "width: 20%;">
  
  <a href="https://biostats-uottawa.github.io/R/"><img src="Rway_logo_hex_en.png" align="right" alt="" width="150"/></a>

  </div>
  <div class="column" style = "width: 80%;">

This is an introduction to statistics with R book with a multilingual approach. The book is covering an introduction to the basic use of R (data loading, wrangling and plotting), as well as programming, use of github and R markdown /Quarto with R Studio and VS code. In terms of statistics, the book is covering linear models, glm, mixed models gams, multivariate analysis and bayesian approach.

The book (still under development) is available in [English](https://biostats-uottawa.github.io/R/en) and [French](https://biostats-uottawa.github.io/R/fr). I will add more languages later this year hopefully with help of volunteers.


</div>

</div>

### Quantitative genetic {#wam_tuto}

<div class="row">
  <div class="column" style = "width: 20%;">
  
  <a href="https://juliengamartin.github.io/wam_tuto/"><img src="wam_logo_hex.png" align="right" alt="" width="150" /></a>

  </div>
  <div class="column"  style = "width: 80%;">

The [book](https://juliengamartin.github.io/wam_tuto/) is tutorial on how to fit an animal model using multiple R packages. This is essentially an updated and extended version of the tutorials from "An ecologist guide to animal model" paper by Wilson et al. (2010).

</div>
</div>

## List of other tutorials I like

- Based on `stan`
  - [SocialAnimal model](https://jordan-scott-martin.github.io/Social-Animal-Models/) by Jordan Scott Martin
  - [Non-linear selection on behavioral reaction norms](https://github.com/Jordan-Scott-Martin/Selection-on-RNs) by Jordan Scott Martin tutorials

* Based on `MCMCglmm`
  - [QGglmm](https://cran.r-project.org/web/packages/QGglmm/vignettes/QGglmmHowTo.pdf) by Pierre de Villemereuil
  - [MCMCglmm](https://devillemereuil.legtux.org/wp-content/uploads/2021/09/tuto_en.pdf) by Pierre de Villemereuil


# Quarto templates {#quarto}

A few quarto templates I developed to facilitate open-science for students at uOttawa

* [bio-uo-proposal](https://github.com/JulienGAMartin/quarto-bio-uo-proposal):  
  quarto extension providing 1 new pdf output format (`bio-uo-proposal-pdf`). I am working on a docx version but tweaking the frontpage is tricky with word document.

* [bio-uo-thesis](https://github.com/JulienGAMartin/quarto-bio-uo-thesis):  
  quarto extension  providing two new output formats for book projects: an html (`bio-uo-thesis-html`) and a pdf (`bio-uo-thesis-pdf`) generating a website (to be hosted on github pages or similar) and a pdf of the thesis adequately formatted for uOttawa (at least biology)

Some extra:

* [quarto-bw-board-revealjs](https://github.com/JulienGAMartin/quarto-bw-board-revealjs):  
  quarto template for revealjs slides for a white- or black-board style with associated `ggplot` theme
