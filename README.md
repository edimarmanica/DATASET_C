# DATASET_C

# 1. Motivation
This dataset is a real-world web page collection. We crawled all the pages of the official websites of the city council of the Brazilian State capitals, then we labelled each web page that describes a single council member (entity-pages). We used this dataset to evaluate different methods for entity-page discovery, i.e., methods that find the entity-pages of a particular type in the websites.

# 2. Observation
This dataset has 18 websites with entity-pages about council members. The official websites of the city council of the 26 Brazilian State capitals were analyzed. We excluded four websites because they did not have an entity-page for each council member, three websites because all the entity-pages were internal frames of a single page, and one website because it did not allow crawling its pages.

# 3. Contents of the Dataset
Currently the dataset involves:
a) Entity-type: council member
b) Websites: 18
c) Web pages: ??
d) Entity-pages: 558, each containing a single data record with detailed information of an entity of a particular type

# 4. Websites

descrever os sites, associar o nome da pasta com a homepage e a data de coleta

# 5. Format of the Web pages
Each web page in the dataset is stored as one .html file in the subfolder pages, that are in the folder 

where the first tag encodes the source URL of the page.
Falar que minha URL está no arquivo index.

# 6. Format of Ground-truth Files

# 7. Notes on Ground-truth Labeling

# 8. How to Download

You can access the latest version of this dataset from HERE.

# 9. Reference

We would appreciate it if you cite the following paper when using the dataset:

Edimar Manica, Renata Galante, Carina F. Dorneles: SSUP - A URL-Based Method to Entity-Page Discovery. ICWE 2014: 254-271

# 10. Contact

If you have questions about this dataset, please contact Edimar Manica (edimar.manica@inf.ufrgs.br).


