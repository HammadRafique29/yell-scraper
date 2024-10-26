

# Yell Scraper

Yell Scraper is a Python tool for scraping business data from [Yell.com](https://www.yell.com). With this scraper, you can extract a wide range of business information based on location or keyword searches. This data can help you analyze local businesses, build contact lists, or gather insights about business categories and locations.

---

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Extracted Data](#extracted-data)
- [Configuration](#configuration)
- [Example Output](#example-output)
- [Screenshots & Video Demos](#screenshots--video-demos)
- [License](#license)

---

## Features

- Scrape data from Yell.com based on search queries and location filters.
- Extract information including business names, addresses, phone numbers, websites, reviews, ratings, and categories.
- Save the extracted data into a CSV file for further analysis.
- Customizable parameters for targeting specific locations or keywords.
- Retry logic for handling network issues or timeouts.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/yell-scraper.git
cd yell-scraper
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

---

## Usage

1. **Specify Search Parameters**  
   Adjust the search keywords, locations, and other options in the script (or configuration file if applicable).

2. **Run the Script**  
   Start the scraping process:

   ```bash
   python yell_scraper.py --location "London" --input "Restaurants"
   ```

   This will extract the data from Yell based on the specified location and query.

3. **Output**  
   The scraped data will be saved as a CSV file in the project directory.

---

## Extracted Data

The Yell Scraper collects the following data for each business listing:

- **Business Name**: The name of the business.
- **Address**: Street address, city, and postal code.
- **Phone Number**: Contact phone number.
- **Business Emails**: Company Email Address.
- **Website URL**: Direct link to the business's website (if available).
- **Categories**: Business categories listed on Yell.com.
- **Operating Hours**: Business operating hours (if available).

---

## Configuration

Adjust the following parameters in the `config.py` file:

- `LOCATION`: Default location to search.
- `QUERY`: Keywords for the business search.
- `CSV_OUTPUT_PATH`: Path to save the extracted CSV file.

Alternatively, you can specify these parameters directly via command-line arguments when running the script.

---

## Example Output

Below is an example of the output data format saved in the CSV file:

| Business Name | Address | Phones        | Company Email          | Website URL            | Reviews | Categories   | Operating Hours     |
|---------------|---------|--------------|------------------------|--------------|---------|--------------|---------------------|
| Pizza Place   | London  | 123-456-7890 | queries@pizzaplace.com | https://pizzaplace.com | 25      | Restaurants  | Mon-Sun 9am-9pm    |

---

## Screenshots & Video Demos

### Screenshots

![Screenshot from 2024-10-13 18-30-27](https://github.com/user-attachments/assets/35e903e2-e4ac-42c6-8abe-d7ed0758525a)

![Screenshot from 2024-10-13 18-30-38](https://github.com/user-attachments/assets/0f4fce28-7dfe-4051-9bc1-a795c4ff62e8)


### Video Demos

[Screencast from 2024-10-10 20-23-00.webm](https://github.com/user-attachments/assets/929ceb37-e210-4efa-9cda-d83be4baa793)


---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

Feel free to modify any sections or add any additional information! Let me know if you need further customization.
