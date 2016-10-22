# Purpose
A compilation of gazetteers for processing unstructured and semi structured text.

These gazetteers are a work in progress and are subject to ongoing change, addition, deletion improvement.

# Gazetteer Format
The gazetteers are a collection of text files. Each text file represents a class of object, person, thing (generally the classification is quite loose).
Each line in a file represents a type of thing, and synonyms are represented on these lines separated with commas `,`

The format of these text files are designed to be readily ingested by the [Balleen](https://github.com/dstl/baleen) Entity Extraction Text Processor. For more information see the related documentation.

# Sources
The gazetteers are built from a range of sources. See below.

# Builders
We have included the code (usually python notebooks, but some .xls files) which we are using to build and cleanse data to produce these files.

The [Scraper Chrome extention](https://chrome.google.com/webstore/detail/scraper/mbigbapnjcgaffohmbkdlecaccepngjd) is very useful and intuitive.

# Gazetteers
Gazetteers are grouped in folders which indicate their source. The file name preserves part of the original URL. In many cases the licence of the data is inherited from the source. These are described below.

| source | folder | licence | description |
|---|---|---|---|
| Aleph Insights | [./gazetteers/source_aleph](./gazeteers/source_aleph) | [CC BY-SA licence](./licences/by-sa.markdown) | Produced by us, often manually. |
| Wikipedia | [./gazetteers/source_wikipedia](./gazetteers/source_wikipedia) | [CC BY-SA licence](https://en.wikipedia.org/wiki/Wikipedia:Text_of_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License) | Scraped or manually pulled from various wikipedia pages. The file name preserves the page name, so you can trace the source. Last capture - 20 Oct 2016 |

# Licence
Make sure you respect the specific licences relating to the gazetteers which come from specific sources. See the table above.

The [Aleph Insights](www.alephinsights.com) produced gazetteers are provided under the [CC BY-SA licence](./licences/by-sa.markdown).
