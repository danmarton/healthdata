# Health Data Browser

Visual analytics tool for medical research teams

* To download large data sets by building a virtual data warehouse 

* From public health data repositories worldwide

* With an editable list of sources

* Acessed through standard web service protocols.

SourceForge site: http://healthdata.sourceforge.io

## Data Pump (ETL)
The data bus will be built upon international (de facto) standards, connected to public open data marts listed on a tab of the config page with Add & Remove buttons - okay, maybe an Edit as well. Yo! The biggest nerd of the research team would use our software to build a big fancy query that would start downloading a huge amount of data when they press the big red Launch button. This would probably take a while, but afterwards the rest of the team would be able to come into the sandbox to play with the data as well.

* Upstream: mine data from brainf*ck legacy systems to modern warehouses. None of our business, honey!
* Midstream: implement powerful data modeling standards to prevent the driver from kicking our ass off the data bus.
* Downstream: download data from warehouses into visual analytics thingy. This is what we are gonna do!!!

## Data Lake
We will have a data lake where XML files will be downloaded & parsed. After parsing a file, the resident nerd could patch the newfound data structures into their central model - see below!!

## Visual Analytics Thingy

This would rely on our knowledge of the following data models, they will be explained thoroughly in the documentation of our product that will include video lectures presented by ME!!! A fact table is a quickly running list of logical [predicates](https://en.wikipedia.org/wiki/Predicate_(mathematical_logic)) made of the primary keys of slowly changing tables information called dimensions, that's the bottom line.

* Star: Facts + Dimensions
* Snowflake: Facts + Dimensions re-normalized
* Galaxy: more than one fact table, with dimensions as bridges between them!

## User Base
Now these will probably be a bunch of over-educated medical graduates with lots of free time BUT all the less money available to realize their dreams of helping mankind overcome diseases, yo! They are looking for their place in the medical world, just like me in the IT world. These kids will be our beta testers or something, I want to include at least some of them into the development process. The product would have relatively few features, but with a ton of documentation to help them understand each!!!

## Cloud Atlas
* Virtual machine image to rely on cloud-based infrastructure
* Installation scripts to rely on cloud-based OS
* Google Drive integration to rely on... Google Drive, I guess?? Probably, yeah.

## Stack
I want a best of breed stack made of open source components, period. I won't mess around with a super integrated shiny big corporate juggernaut with a billion dollar TCO, honey, that ain't my style!!!

* OS: Ubuntu
* Text editor: Gedit
* Database: PostgreSQL
* Languages: Python, Java, C# (Mono)
* Front-end: Django
* Back-end: Apache
* Version control: Git
