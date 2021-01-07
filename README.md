# seeknz-scraper
Using Python to scrape Seek NZ based on user's specified search query and location. 
Returns relevant summary data such as salary, keywords, location etc.

Version 1 is practically finished, recommendation features won't be in this version. Version 1 is for mining the data.

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
| 5 | Setup automated proxy from VPN | Not started - version 2 project|
| 6 | Mine job requirements and keywords | DONE |
| 7 | Recommend jobs | Not started - version 2 project |
| 8 | Clean up code - make a version without trials | Not started |
| 9 | Find and fix bugs - use but stop adding features| Not started |

To do 7, I need to build up a keyword library of skills that I feel are relevant to me, or I am interested in. Then use that to rank jobs, or potentially use machine learning from a list of job data that I have applied for. Any case, I can't develop until I get more data.

### Bugs:
| #     | Description   | Status    |
|------------|-------------|-------------|
| 1 | Slight issue in printing URLs - sometimes there is a random digit after the page number. No effect on use - just visual. I think it is due to the inrow printing. Probably a print('') space is the solution somwhere (https://drive.google.com/file/d/1aMOE_RYr_VqukHWltLBFX-tA8UJarHbU/view) | Not fixed |
| 2 | Some duplicate jobs are listed. 26 out of 2500. These are all due to featured jobs (except 1) - i.e the job is page 1 featured, but then mined again on page 5. The jobs don't get added to the CSV table until all pages have been mined so the duplications are missed. One solution is to ignore featured jobs. Another is to also look at the current Record array for a match, as well as CSV. Could also fix in CSV. I think best option would be #2 | Not fixed |
