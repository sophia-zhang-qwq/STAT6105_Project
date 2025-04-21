Scraping&Analysis Code of the YouTube Recommendation System.

STAT6105 Project, joint-work with Tianlei Zhu and Seth Matthew Louis. 

- Data: Google form data.
- Code: Based on google-drive data mounting, this code provides a user-friendly-interface for YouTube API-calls and data processing of video metadata. 
	4 modules:
	1. scrape: search youtube video for a given keywords(eg “duck song”) and record the first few recommended video (up to max # that the user specifies)
	2. fetch: under a mode(personal/private/both), process the raw-raw data to obtain the raw data, extracts the video metadata(can be category, title, id…) through API-calls, and converts each video link to a category.
	3. analyze: visualize the top categories of the raw data. 
	4. example: tutorial of a toy example.
- Results: generated imgs and report.
