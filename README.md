# AmharicDataRepo
AmharicDataRepo is a comprehensive repository containing datasets for pre-training and evaluating Natural Language Processing (NLP) models on Amharic text. 

DESCRIPTION OF THE DATASET FOR PRE-TRAINING

The following table represents a collection of sources compiled to gather Amharic monolingual data, essential for pre-training language models. This compilation focuses on various domains, primarily news, with the inclusion of religious texts to provide a diverse linguistic dataset. Each source is identified by its type of content and the methods used for data extraction, such as sitemaps and the Wayback Machine, to ensure a comprehensive coverage of Amharic language content.


| Source                  | Domain     | Number of Articles | Number of Sentences                |
|-------------------------|------------|--------------------|------------------------------------|
| Zehabesha               | News       | 8,834              | Sitemap                            |
| DW                      | News       | 68,160             | Sitemap & Wayback Machine          |
| VOA                     | News       | 178,961            | Sitemap & Wayback Machine          |
| ESAT                    | News       | 11,263             | Sitemap                            |
| Fana                    | News       | 46,935             | Sitemap                            |
| Ethiopian Reporter      | News       | 23,051             | Sitemap                            |
| Amhara Media            | News       | 125                | Sitemap                            |
| Debteraw                | News       | 538                | Sitemap                            |
| Walta Information Center| News       | 32,550             | Sitemap                            |
| EBC                     | News       | 33,842             | Wayback Machine                    |
| BBC                     | News       | 27,198             | Sitemap & Wayback Machine          |
| ENA                     | News       | 10,466             | Sitemap                            |
| Addis Admas News        | News       | 76,688             | Wayback Machine                    |
| Cyber Ethiopia          | News       | 30,984             | Wayback Machine                    |
| Ethiopia Nege           | News       | 27,049             | Wayback Machine                    |
| Ethiopian Gazetta       | News       | 7,039              | Wayback Machine                    |
| Jehovah’s Witnesses(JW) | Religious  | 17,038             | Sitemap                            |
| Bible                   | Religious  | -                  | Opus                               |
| Goolgule                | News       |4,685               | Sitemap                            |
| Soccerethiopia          | News       |13,815              | Sitemap                            |
| geez.org                | Religious  | -                  | github                             |
| geez.org                | Literature, History, Education, Children books| -                    | github                            |


Folder Structure
The data for the Amharic monolingual dataset is organized within the data folder, structured to facilitate easy access and management of various text sources. Below is the detailed structure of the data organization:

data/
├── news.txt                            # Contains text files from news sources
├── bibel.txt                           # Contains text files from the Bible
├── jw.txt                              # Contains text files from JW publications
├── wikipedia.txt                       # Contains extracted text files from Wikipedia
├── additional_data.txt                 # Contains extracted text files from googlue and soccerethiopia news websites
├── geezorg_religious.txt               # Contains extracted text files from geez.org religious content
└── geezorg_nonreligious.txt            # Contains text files extracted from geez.org news domain


NOTE
PREPROCESSING STEP 
 -- for cleaning and filtering step please visit (https://github.com/Tsedi2/web_crawl.git) github page.