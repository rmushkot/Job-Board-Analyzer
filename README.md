# Job-Board-Analyzer
A program to search specific keywords on Indeed job postings. \
This uses selenium to open a headless Firefox browser and scans each job posting looking for keywords specified in languages.txt

## Usage
This program is simple CLI to run.
` python3 boardReader.py -t [title] -l [location] ` \
Example: ``` python3 boardReader.py -t "Software Engineer" -l "San Jose CA" ``` will search Indeed.com and examine each job posting. Each job posting will be scanned for the keywords listed in `languages.txt`and a count for each one will be kept. Keywords that do not appear in any job postings will not be included in the results. \
Finally, a simple bar graph will be displayed with the results. 
