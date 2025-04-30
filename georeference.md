### Project scope 

We are going to georeference and augment one of the largest host-parasite dataset in existence. This is the London Natural History Museum's host-parasite database, which contains around 250,000 interactions between host species and helminth parasites. 




### Logistics 

+ Discord for quick communication (https://discord.gg/Hyw6s38p)

+ GitHub organization and data access (https://github.com/LNHMhelminth)

+ Salary and entering hours

+ Code of conduct

+ Opportunities for undergraduate research 

+ CodeFests 







### Data 

Data are divided into 231 'chunks', each around 1000 interactions (some weird ones only have like 10), organized so that we're not reproducing efforts for citations. So one citation may provide anywhere between 1 and 2000+ georeferences for interactions. 

Data are structured where each row is an interaction between a host species and a helminth species. There are a bunch of rows of data, where you will be responsible for inserting data on latitude and longitude. Only include numbers here, so you may have to convert from degrees minutes seconds format to decimal degrees. 

**convert dms to decimal**: https://www.fcc.gov/media/radio/dms-decimal

DMS format will look like this: 49° 56' 49", which corresponds to 49 degrees, 56 minutes, and 49 seconds. Conversion can be done at the website above (or any number of other online converters). 

Do not edit the entries that are already filled in. Instead, you'll be inputting data into the columns at the end with NA values currently. These columns are:

`latitude`: in decimal degrees
`longitude`: in decimal degrees
`prevalence`: prevalence of infection (fraction of host individuals sampled with that parasite)
`intensity`: intensity of infection (mean number of parasite individuals per infected host)
`notes`: any notes that you think are relevant 











### Guidelines and workflow 

+ Find a citation and search the original paper or book (get a pdf copy if possible). For textbooks, check with the U of SC library. If they don't have it, see if you can get an interlibrary loan. 

+ If not, look at lib-gen ((https://libgen.is)). For scientific articles that the university does not have access to, use sci-hub (https://sci-hub.se)

+ More details on this terrible-quality recording of part of the training (https://youtu.be/AAP3QWS0_dw)







### A worked example 

> Valtonen, E.T. & Helle, E., 1988 "Host-parasite relationships between two seal populations and
two species of Covynosoma (Acanthocephala) in Finland". https://zslpublications.onlinelibrary.wiley.com/doi/abs/10.1111/j.1469-7998.1988.tb04729.x












