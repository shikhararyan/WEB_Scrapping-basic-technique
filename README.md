
## Code Overview

- The code begins with importing necessary libraries such as pandas, numpy, BeautifulSoup, requests, and csv.
- It then sends a GET request to the specified URL and retrieves the HTML content of the webpage.
- BeautifulSoup is used to parse the HTML content and extract specific information from the webpage, in this case, a table containing individuals' details.
- The relevant data is extracted and stored in a list.
- The extracted data is then processed to separate the name, citizenship, and date of birth information.
- Finally, the processed data is saved into a CSV file for further use.

## Technologies Used

- Python
  - Libraries: pandas, numpy, BeautifulSoup, requests
