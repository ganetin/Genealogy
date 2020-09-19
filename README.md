# About
Search for indivuals in the public death records provided by the French National Institute of Statistics and Economic Studies (INSEE).

## Context
I took advantage of being confined at home in the spring of 2020 to work on my family tree. Records which are older than 100 years can be access online (for the most part). For privacy/legal reasons younger records can not be access. However the INSEE provides (only) the dates and places of birth and death of people who passed after 1970: [this page] (https://www.insee.fr/fr/information/4190491) (in French). 
As the INSEE csv files contain in total more than 20+ million deaths I wrote a two codes in Python that allows me to format the data the way I find convenient and above all allows me to look for individuals of interest based on their name, years and places of birth or death if available. 
Using public records and the INSEE ones I managed to gathers more than 600 people in my family tree and I got back to as early as the middle of the 17th century (a good aspect of the French bureaucracy!).

## Content
* deces-1970-1979-csv.zip: a zip contained 10 csv, one per year, with data on individuals who passed in the 70s. Obtained from the [INSEE website] (https://www.insee.fr/fr/information/4190491)
* INSEE_formatting.ipynb: a notebook to format the data for INSEE in a way I find convenient. An example is provided for individuals who passed in the 70s but the script can be used for any INSEE input zip file.
* Insee_70s.csv: the output of INSEE_formatting.ipynb, a single csv containing the data of all indiviudals who passed in the 70s.
* Insee_search.ipynb: a notebook which uses Insee.zip generated from all the formatted and zipped decadal csv files to search for individuals of interest.

## License
MIT License

## Author
Dr. Morgane FORTIN, Sept. 2020
