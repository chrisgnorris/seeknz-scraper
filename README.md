# seeknz-scraper
Using Python to scrape Seek NZ based on user's specified search query and location. 


## Version 1
#### Run and configure using:
**main('operations-analyst','Auckland')**

All spaces will need a dash between them. 


### Next steps for development:

| #     | Description   | Status    |
|------------|-------------|-------------|
| 1 | Make it ignore queries it has already done - so it can run daily | DONE |
| 2 | Add in more info (i.e date etc) | DONE |
| 3 | Add in better salary data | DONE |
| 4 | Save to an existing Excel file for better usability - i.e make it append as opposed to overwriting | DONE - Decided this was not needed. Better to query CSV file with Excel |
| 5 | Setup automated proxy from VPN | IN PROGRESS |
| 6 | Mine job requirements and keywords | Not started |
| 7 | Recommend jobs | Not started |



### Bugs:
| #     | Description   | Status    |
|------------|-------------|-------------|
| 1 | Slight issue in printing URLs - sometimes there is a random digit after the page number. No effect on use - just visual. I think it is due to the inrow printing. Probably a print('') space is the solution somwhere (https://drive.google.com/file/d/1aMOE_RYr_VqukHWltLBFX-tA8UJarHbU/view) | Not fixed |

