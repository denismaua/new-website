# [Hugo Academic CV Theme](https://github.com/HugoBlox/theme-academic-cv)

[![Screenshot](.github/preview.webp)](https://hugoblox.com/templates/)

The Hugo **Academic CV Template** empowers you to easily create your job-winning online resumé, showcase your academic publications, and create online courses or knowledge bases to grow your audience.

[![Get Started](https://img.shields.io/badge/-Get%20started-ff4655?style=for-the-badge)](https://hugoblox.com/templates/)
[![Discord](https://img.shields.io/discord/722225264733716590?style=for-the-badge)](https://discord.com/channels/722225264733716590/742892432458252370/742895548159492138)  
[![Twitter Follow](https://img.shields.io/twitter/follow/GetResearchDev?label=Follow%20on%20Twitter)](https://twitter.com/GetResearchDev)

# How to create a new publication

1. Add the bibtex entry to assets/bib/publications.bib; use the format First_author_surnameYearAcronym as key (usualy, in lower case); to feature the publication, add a selected = {1} field.
2. Run
```
academic import --bibtex assets/bib/publications.bib content/publication/ --normalize [--featured]
```
from the website base folder.
3. Review and edit the created page entry in content/publication/First_author_surname-Year-Acronym. For example, add related projects, talk slides, link to code, etc.


Alternatively, manually create a publication entry with
```
hugo new content/publication/<my-publication>
```
Note: this will not add the reference to the main publications bibtex file.

The most recent version of academic seems to produce different form of publication types.
If you get an error, revert to the following for backward compatilibity

````
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
``````

# How to deploy

run `./deploy`

# Installation

Follow Wocademy instructions. The CLI command requires instalation, see

https://github.com/wowchemy/hugo-academic-cli/

https://github.com/GetRD/academic-file-converter
