# DATA512HW1
Professionalism &amp; Reproducibility Assignment

Author: Ashwin Naresh

In this assignment, we use the Wikipedia Pageviews API to collect monthly page view data. In section 1, we collect mobile, desktop, and cumulative data and store this in 3 unique json object files. In section 2, we use these json object files to perform some simple data visualizations (details found in the notebook).

## License and Terms of Use
Wikimedia Foundation: https://foundation.wikimedia.org/wiki/Policy:Terms_of_Use

Sample API Code: https://creativecommons.org/licenses/by/4.0/

The sample code license allows us to freely modify and use the code, porvided we acknowledge the license and cite it as we have done here. We also adhere to the Wikimedia terms of use by following all media laws with the information gathered and no not violate copyright in any way. The datasets and images created in thsi project also follow the terms of use by protecting private data and not being used for profit. This project acknowledges both licenses.

## API Documentation
Pageview API: https://doc.wikimedia.org/generated-data-platform/aqs/analytics-api/reference/page-views.html

Python Documentation: https://docs.python.org/3/

## Output Files

### JSON Files
rare-disease_monthly_cumulative_201507-202409.json

rare-disease_monthly_desktop_201507-202409.json

rare-disease_monthly_mobile_201507-202409.json

Format:

{  "article": [    {   "project": "",  "article": "",            "granularity": "",            "timestamp": "",            "agent": "",            "views": ""          },         ...      ], ...}

The JSON files are dictionaries with a outkey for each article. Each key maps to an array of JSON objects which hold the monthly pageview data. Each file corresponds to a particular access type (mobile, desktop, cumulative).

### JPG Files
visualization1.jpg

visualization2.jpg

visualization3.jpg

Each of the visualizations created in Step 2 are saved as separate jpg files.

# Using the Code
The code for this project is found in hw1.ipybn (main code) and wp_article_views_example.ipynb. The code also references the rare-disease_cleaned.AUG.2024.csv file as input.

To replicate this project, run the code blocks in the same order that they are provided. Note: The code in Step 1 takes a while to run, but the output of these steps (the json files) is already created and available for use in Step 2. Therefore, Step 1 can be skipped.
