[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

# Danish wordlists
## Collection of danish wordlists for cracking danish passwords

Filename  | Lines | Description | Source
------------- | ------------- | ------------- | -------------
dawiki-2021-11-25.txt  |  2600745  |  Words sourced from the danish language Wikipedia  | https://dumps.wikimedia.org/dawiki/20211120/
old_testament.txt   |  21937  |  Words sourced from The Old Testament in Danish  |  https://www.gutenberg.org/cache/epub/2143/pg2143.txt
new_testament.txt  |  9343  |  Words sourced from The New Testament in Danish  |  https://www.gutenberg.org/cache/epub/2143/pg2143.txt
supplementary_city_names.txt  |  6542  |  Collection of 'supplementary city names' sourced from The Danish Agency for Data Supply and Efficiency  |  https://api.dataforsyningen.dk/supplerendebynavne?format=csv
street_names.txt  |  111911  |  Collection of street names sourced from The Danish Agency for Data Supply and Efficiency  |  https://api.dataforsyningen.dk/vejstykker?format=csv
first_names_female_2021.txt  |  80003  |  List of approved female danish first names (2021) sourced from the danish Civil Registration System by Statistics Denmark |  https://www.dst.dk/da/Statistik/emner/borgere/navne
first_names_male_2021.txt  |  62442  |  List of approved male danish first names (2021) sourced from the danish Civil Registration System by Statistics Denmark |  https://www.dst.dk/da/Statistik/emner/borgere/navne
last_names_2021.txt  |  297222  |   List of approved danish last names (2021) sourced from the danish Civil Registration System by Statistics Denmark |  https://www.dst.dk/da/Statistik/emner/borgere/navne
ddo_fullforms.txt  |  632060  |  This wordlist comprises inflected forms of the headwords of The Danish Dictionary. Based on ddo_fullforms_2020-08-26.csv |  https://korpus.dsl.dk/resources/details/ddo-fullforms.html
cvr_companies.txt  |  330421  |  Danish company names scraped from The Central Business Register. As much of the data is all upper case for some reason, it might be useful to convert all lines to lower case with something like `awk '{print tolower($0)}' < cvr_companies.txt > cvr_companies_lower.txt` |  https://datacvr.virk.dk/data/
cit0day_dk.txt  |  168989  |  Compilation of passwords from .dk-domains in the Cit0day leak. Obviously generated passwords have been removed (lazily). Email-addresses as passwords have been removed.  |  List of sites in the leak: https://gist.github.com/gvolluz/dd0df2ba2400c4891f95d05de3dde1da
