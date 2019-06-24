# [Data Week 2019](http://www.bristol.ac.uk/golding/get-involved/data-week-2019/)
###### University of Bristol :: Jean Golding Institute


| Date | ref | Session | Language | Course |
| --- | --- | --- | --- | --- |
| 20/5/19 | OD | [Asking & answering questions with Open Data](http://www.bristol.ac.uk/golding/events/2019/asking-and-answering-questions-with-open-data.html) | SPARQL | --- |
| 21/5/19 | IP | [Intermediate Python](http://www.bristol.ac.uk/golding/events/2019/intermediate-python.html) | Python | [link](http://chryswoods.com/intermediate_python/README.html) |
| 21/5/19 | UCD | [Explore UK Crime Data with Pandas & GeoPandas](http://www.bristol.ac.uk/golding/events/2019/explore-uk-crime-data-with-pandas-and-geopandas.html) [IBM] | Python | [link](https://github.com/IBMDeveloperUK/geopandas-workshop) |
| 22/5/19 | IDA | [Introduction to data analysis in Python](http://www.bristol.ac.uk/golding/events/2019/introduction-to-data-analysis-in-python.html) | Python | [link](https://nbviewer.jupyter.org/github/milliams/data_analysis_python/blob/master/Introduction.ipynb) |
| *22/5/19* | --- | *A Walk through the Python Visualization Forest -- CANCELLED* | *Python* | --- |
| 23/5/19 | ADA | [Applied data analysis in Python](http://www.bristol.ac.uk/golding/events/2019/applied-data-analysis-in-python.html) | Python | [link](https://milliams.gitlab.io/applied_data_analysis/) |
| 24/5/19 | TIDY | [Tour of the Tidyverse](http://www.bristol.ac.uk/golding/events/2019/tour-of-the-tidyverse-.html) [MangoSolutions] | R | PowerPoint |






| ref | Directory or file (in root) | Explanation |
| --- | --- | --- |
| OD | --- |  |
| IP | --- |  |
| UCD | 2018-1-metropolitan-street.zip |  |
| UCD | 2018-2-metropolitan-street.zip |  |
| UCD | 2018-metropolitan-stop-and-search.zip |  |
| UCD | boundaries.zip |  |
| UCD ? | cetml1659on.dat |  |
| UCD ? | city_pop.txt |  |
| UCD | london_inner_pois.zip |  |
| IDA | IDA_1-Getting-started.ipynb |  |
| IDA | IDA_2-Intro-to-Pandas.ipynb |  |
| IDA | IDA_3-my-notation-question.ipynb |  |
| ADA | ADA_1-Fitting.ipynb |  |
| ADA | ADA_2-Correlation.ipynb |  |
| ADA | ADA_3-Clustering.ipynb |  |
| TIDY | A Tour of the Tidyverse.pptx |  |
| TIDY | SummerOlympicsFunding.csv |  |
| TIDY | tidyverse_workshop.R | received after |
| TIDY | TourTidyverse_1.R |  |
| TIDY | tourtidyverse_exercises.R | received after |
| TIDY | uni_results.csv |  |
| --- | README.md | This document |


---

### OD :: Asking & answering questions with Open Data

[https://query.wikidata.org/](https://query.wikidata.org/)

* [Query1](https://query.wikidata.org/#%23defaultView%3AMap%0ASELECT%20%3Fperson%20%3FpersonLabel%20%3Fcoordinates%20%3Fimage%20WHERE%20%7B%0A%3Fperson%20wdt%3AP69%20wd%3AQ459506%20.%20%23%20person%20educated%20at%20UoBristol%0A%3Fperson%20wdt%3AP106%20wd%3AQ33999%20.%20%23%20person%20is%20an%20actor%0AOPTIONAL%20%7B%3Fperson%20wdt%3AP18%20%3Fimage%20%7D%20.%0A%3Fperson%20wdt%3AP19%20%3Fbirthplace%20.%0A%3Fbirthplace%20wdt%3AP625%20%3Fcoordinates%0ASERVICE%20wikibase%3Alabel%20%7B%20bd%3AserviceParam%20wikibase%3Alanguage%20%22%5BAUTO_LANGUAGE%5D%2Cen%22.%20%7D%0A%7D) : 
* [Query2](https://query.wikidata.org/#%23defaultView%3AMap%0ASELECT%20%3Fperson%20%3FpersonLabel%20%3Fcoords%20%3Fimage%20WHERE%20%7B%0A%3Fperson%20wdt%3AP166%20wd%3AQ37922%20%20.%0A%3Fperson%20wdt%3AP19%20%3Fbirthplace%20%20.%0A%3Fbirthplace%20wdt%3AP625%20%3Fcoords%20%20.%0AOPTIONAL%20%7B%3Fperson%20wdt%3AP18%20%3Fimage%7D%20%20.%0ASERVICE%20wikibase%3Alabel%20%7B%20bd%3AserviceParam%20wikibase%3Alanguage%20%22%5BAUTO_LANGUAGE%5D%2Cen%22.%20%7D%0A%7D) :
* [Query3](https://query.wikidata.org/#SELECT%20%3Forg%20%3ForgLabel%20%3Flink%20WHERE%20%7B%0A%3Forg%20wdt%3AP5305%20%3Flink%20%20.%20%23%20has%20SPARQL_endpoint%0ASERVICE%20wikibase%3Alabel%20%7B%20bd%3AserviceParam%20wikibase%3Alanguage%20%22%5BAUTO_LANGUAGE%5D%2Cen%22.%20%7D%0A%7D%20ORDER%20BY%20%3ForgLabel) :

[Found a [link](https://medium.com/@sahansera/dockerizing-sparql-and-pandas-with-python-e20ffb1b617d) for using SPARQL with Pandas. BUT Anaconda doesn't contain `SPARQLWrapper`, never mind `sparql-dataframe`]


### IP :: Intermediate Python


### UCD :: Explore UK Crime Data with Pandas & GeoPandas
[`pandas`; `geopandas`]

* '20190521_JGI_notebook' is not linked (at the moment), to avoid sharing the 'project token' with readers


### IDA :: Introduction to data analysis in Python
[`pandas`; `matplotlib`]


### --- :: A Walk through the Python Visualization Forest


### ADA :: Applied data analysis in Python
[`scipy`; `scikit-learn`]


### TIDY :: Tour of the Tidyverse
[`tidyverse`]
