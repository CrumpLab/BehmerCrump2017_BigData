# BehmerCrump2017_BigData
Data sets from Behmer &amp; Crump (2017)

This repository contains the data from:

Behmer, L. P., & Crump, M. J. C. (2017). Crunching big data with finger tips: How typists tune their performance towards the statistics of natural language. In M. N. Jones (Ed.), Big Data in Cognitive Science (pp. 319–341).

Please cite the above if you use this data for new analyses. The manuscript can be downloaded from the human cognition and performance lab website: https://crumplab.github.io/publications/

## Contents

- typindata.txt.zip : full dataset. Datafrom 346 typists. Each typist copied Normal english paragraphs, a paragraph of 5 letter strings conforming to the bigram statistics of natural English, and a paragraph of 5 letter random strings. 
- typingdata_headerinfo.txt : An explanation of the contents of each column in the data set.
- Figure_generator.Rmd : An RMarkdown script, showing an example of loading the data and performing the main analysis from Behmer & Crump (2017)
- Figure_generator.html : The HTML output of the RMarkdown script
- NewFigs : The generated figures
-GutenbergFrequencyTables.RData : A dataset for R containing the letter, bigram, and trigram frequency counts from a large sample of English e-books from project Gutenberg