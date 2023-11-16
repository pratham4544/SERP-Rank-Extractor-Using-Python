# Google SERP Rank Checker

This Python script uses Selenium to automate the process of checking the search engine results page (SERP) rank of a given website for specific keywords. In this example, it checks the rank of "www.shiksha.com" for the keyword "iims pune" and a list of other keywords related to educational institutions.

## Prerequisites

Make sure you have the Selenium library installed before running the script. You can install it using the following command:

```bash
pip install selenium
```

## Usage

1. Replace the 'chromedriver.exe' path with the actual path to your WebDriver executable.
2. Set the URL of the web page you want to check in the `driver.get()` method.
3. Adjust the XPaths in the script to match the actual locators of the elements on the web page.

## Script Overview

1. The script opens a web page using the Selenium WebDriver.
2. It inputs a URL into a text box and submits the form to get the SERP results.
3. It then searches for a specific keyword on the results page and extracts the rank information.
4. The script repeats the process for a list of keywords and stores the results in two lists: `keywords` and `ranks`.
5. Finally, the script prints the results and creates a Pandas DataFrame for further analysis.

## Example Keywords

The script is configured to check the SERP rank for the following keywords:

- JNU admission 2024
- LPU Cutoff 2023
- Jadavpur University Cutoff 2023
- Jamia Millia Islamia Cutoff 2023
- Hyderabad University Cutoff 2023
- IIM Jammu Cutoff
- IIM Shillon Cutoff

## Output

The script outputs the ranks and corresponding keywords, as well as saves the results in a CSV file named `rank1.csv`.

## Note

Ensure that you have the appropriate WebDriver executable for your browser and operating system. Adjust the paths and locators in the script based on the structure of the web page you are interacting with.

Feel free to customize the script according to your specific requirements.
