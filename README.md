# CRU-resources
R script to enable usage of the aphiaID and higher taxonomic levels of the SMarTar-ID (https://smartar-id.app) labels in ecological analysis

https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0218904 

Includes: 
- RMD file (r script) to fromat Biigle CSV report 
- table of AphiaID for SMarTar-ID (https://smartar-id.app) labels 

Installation 
- 1) Download the repository to your machine 
- 2) Unizip it in a directory of your choice on your machine
- 3) Open the SmartrID reports.Rmd file with Rstudio 
- 4) Follow the instructions on how to import your Biigle reports 
- 5) Run the script cell by cell or knit it 

Once it is finished, you should find in your WD: 

- a Site x species csv table (smartarID labels as rows, images as columns) 

| Label names  | image 1 | image 2 |
| ------------- | ------------- | ------------- |
| worm 1  | 0 | 1 |
| worm 2  | 1  | 0 |

- a Site x species csv table with the aphiaIDs and the higher taxonomic levels (smartarID labels + taxonomy as rows, images as columns)
- a species x site csv table (images as rows, smartarID labels as columns)
- a species with the aphiaIDs and the higher taxonomic levels x site csv table (images as rows, smartarID labels + taxonomy as columns)


