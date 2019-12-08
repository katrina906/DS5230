# DS5230 Project ReadMe

This project implements and compares two versions of search result clustering: hierarchical and Lingo algorithm (SVD).  
I use the Reuters financial newswire dataset (inbuilt nltk dataset) and use its topic labels and search term proxies. I cluster the documents "returned" for each "search term" and give those clusters labels.  


Description of files and run order:
1. cleaning: download data and perform basic text processing and cleaning
2. hierarchical: preform hierarchical search result clustering
3. lingo: perform lingo algorithm's search result clustering
4. comparison: compare the results from hierchical and lingo 
