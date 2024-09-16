# Pinterest Image Scraper

## Project Summary
This project is a Python-based Pinterest image scraper designed to automate the extraction of images from Pinterest boards. The goal was to streamline and speed up the process of collecting images for use in presentations and other projects, which can be tedious when done manually. The scraper efficiently collects images and their captions, making the task quicker and less labor-intensive.

## Project Description

### Data Description, Source, and Collection Method

- **Data Description:** The dataset consists of images and their associated metadata (captions) from Pinterest boards. 
- **Source:** Images were collected from my Pinterest board at [Pinterest Board URL](https://www.pinterest.co.uk/tinusor/clothes-that-i-want-to-buy/).
- **Collection Method:** The scraper uses Python with the following steps:
  1. Fetch the webpage HTML using `requests`.
  2. Parse the HTML with `BeautifulSoup` to find image tags.
  3. Extract and organise image URLs.
  4. Download images and save them locally.
  5. Save image URLs and captions to a metadata file.

### Learnings from the Project

- Enhanced skills in web scraping and data extraction.
- Improved error handling and data management techniques.

### Challenges Encountered and Solutions
- **Incomplete Data Extraction:** Fixed by refining URL cleansing and error handling.
- **Metadata Handling:** Improved by ensuring captions are included in the metadata file.

### What Went Well

- Successfully downloaded and saved most images.
- Reduced manual effort and time through automation.

### What I Would Do Differently

- Expand the range of data sources to include additional Pinterest boards or other platforms.
- 
### Ethical Statement

- **Data Sources and Biases:** Data was sourced from publicly accessible Pinterest boards. The dataset represents personal choices and may include biases.
- **Potential Uses:** This project demonstrates practical web scraping for personal use. It’s important to use the data responsibly and follow to copyright and usage rights.

