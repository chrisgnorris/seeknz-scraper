# seeknz-scraper
Using Python to scrape Seek NZ based on user preferences


## Version 1
#### Run and configure using:
main('operations-analyst','Auckland') 

All spaces will need a dash between them. 


#### Next steps for development:
1. Make it ignore queries it has already done - so it can run daily (DONE)
2. Add in more info (i.e date etc) (DONE)
3. Add in better salary data (DONE)
4. Save to an existing Excel file for better usability - i.e make it append as opposed to overwriting (maybe move to Pycharm) (REMOVE - QUERY CSV WITH SHAREPOINT INSTEAD)
5. Mine job requirements and keywords
6. Recommend jobs

#### Bugs
1. Slight issue in printing URLs - sometimes there is a random digit after the page number. No effect on use - just visual. I think it is due to the inrow printing. 
   Probably a print('') space is the solution somwhere
