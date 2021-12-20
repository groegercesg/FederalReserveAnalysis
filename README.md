# FederalReserveAnalysis

Analysis of Federal Reserve Governor Speeches in comparison to Financial Markets.

## File List

- `speechscraping.ipynb` : used for scraping the text of speeches off of the [federalreserve.gov](https://www.federalreserve.gov/) website
- `fed_speeches_1996_2021.csv` : the scraped data, stored as a CSV

## Federal Reserve Speeches

The data is stored in: `fed_speeches_1996_2021.csv`

- Scraped from [federalreserve.gov](https://www.federalreserve.gov/newsevents/speeches.htm) using BS4 from Python.
- The speeches are public ones that have been given by various position holders in the Federal Reserve's Board of Governors. For more information on the Board of Governors, see this wikipedia page: [wiki](https://en.wikipedia.org/wiki/Federal_Reserve_Board_of_Governors)
- The metadata we scape for each speech is:
    - Title of the speech
    - Link to the speech, that we downloaded it from
    - Name and their speakers stated position (occasionally edited for clarity)
    - Details about the event, where the speech was given
    - Year and date of the speech
    - Raw text of the speech
    - Number of words in the speech
    - Location where the speech was given, typically a city or state

## Bank of England

*TBC*

https://www.bankofengland.co.uk/monetary-policy-summary-and-minutes/monetary-policy-summary-and-minutes

https://www.bankofengland.co.uk/news/speeches

https://www.bankofengland.co.uk/sitemap/speeches

## European Central Bank

*TBC*

https://www.ecb.europa.eu/press/key/html/downloads.en.html

https://www.ecb.europa.eu/press/key/shared/data/all_ECB_speeches.csv