# school-shooting-data
School shooting collected from multiple sources 

## datasets

### pah_wikp_combo
Munge of the dataset underlying the Pah/Amaral/Hagan research ([https://news.northwestern.edu/stories/2017/01/shootings-us-schools-link-unemployment]) on school shootings with the Wikipedia article ([https://en.wikipedia.org/wiki/School_shootings_in_the_United_States]) from 1990 to present.

Fields:
* Date: date of incident
* City: location of incident
* State: location of incident
* Area Type: urban or suburban (only in Pah dataset)
* School: C = college, HS = high school, MS = middle school, ES = elementary school, - = unknown
* Fatalities: # killed
* Wounded: # wounded (only in Wikipedia dataset)
* Dupe: whether this incident appears in both datasets. Note: only the "Pah" version of the incident is marked.
* Source: Pah or Wikp 
* Desc: text description of incident (only in Wikipedia dataset)


### cps_01_formatted
Census numbers on elementary school, high school and college populations through 2016. (2017 and 2018 are extrapolated.)  From dataset downloaded from the US Census bureau.
Legend:
* N = Nursery School
* K = Kindergarten
* E = Elementary School
* H = High School
* C = College
