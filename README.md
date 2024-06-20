# Crunchbase Scraper: Get Company Data Easily

Are you looking for a way to extract company information from Crunchbase? Our Crunchbase scraper makes it super simple to gather data on organizations.

## What is a Crunchbase Scraper?

A Crunchbase scraper is a tool that pulls details about companies from the Crunchbase website. Instead of manually copying information, the scraper automatically collects and organizes the data for you.

## Why Use Our Crunchbase Scraper?

Our Crunchbase scraper is the best because it's:

- **Reliable**: You get accurate, up-to-date company data every time.
- **Easy**: Just give us a list of Crunchbase company links. We do the rest!
- **Powerful**: Extract a ton of valuable details with one click.

## How to Use the Crunchbase Scraper

Using our Crunchbase scraper tool is a breeze:

1. Visit [Crunchbase Scraper](https://apify.com/scrapefull/crunchbase-scraper) on Apify Store.
2. Paste in the links to the companies you want to scrape
3. Start the scraper
4. Download your structured company data once it's ready in formats like JSON, CSV, Excel, XML, HTML Table, RSS and JSONL.

It's that simple! No coding required. 

If you prefer to integrate via an api, you can use the [Crunchbase Scraper API](https://apify.com/scrapefull/crunchbase-scraper/api/client/nodejs) too.

## Get Started with the Crunchbase Scraper

Don't waste time manually copying Crunchbase profiles. Let our trusted crunchbase scraper tool do the hard work for you. Accurate data, incredible ease of use, and time savings - what more could you ask for?

Sign up today and effortlessly extract all the company intelligence you need from Crunchbase. Try the best Crunchbase scraper now!

## What Data Does It Collect?

| Field Name                                          | Data Structure               | Description                                                                                                                   |
| --------------------------------------------------- | ---------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| **Company Name**                                    | String                       | Company's primary name (extracted from other fields)                                                                          |
| **Company Description**                             | String                       | Brief description of the company and what it does                                                                             |
| **Website**                                         | String (URL)                 | Company's primary website address                                                                                             |
| **Contact Email**                                   | String                       | Company's publicly listed contact email address                                                                               |
| **LinkedIn URL**                                    | String (URL)                 | Link to the company's LinkedIn profile                                                                                        |
| **Twitter URL**                                     | String (URL)                 | Link to the company's Twitter profile                                                                                         |
| **Facebook URL**                                    | String (URL)                 | Link to the company's Facebook page                                                                                           |
| **Company Type**                                    | String                       | Legal structure of the company (e.g., "for_profit", "non_profit")                                                             |
| **Founded Date**                                    | Date                         | Approximate date the company was founded                                                                                      |
| **Founded Date Precision**                          | String                       | Level of precision for the founding date                                                                                      |
| **Operating Status**                                | String                       | Current operational status of the company (e.g., "active", "acquired")                                                        |
| **Company Categories**                              | List of Objects              | Industry categories associated with the company. Each object contains:                                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;Category Name               | String                       | Name of the category (e.g., "Artificial Intelligence (AI)", "Software")                                                       |
| &nbsp;&nbsp;&nbsp;&nbsp;Category Link               | String (URL)                 | Link to a Crunchbase search for that category                                                                                 |
| **Headquarter Regions**                             | List of Objects              | Broad geographic regions where the company's headquarters is located. Each object contains:                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;Region Name                 | String                       | Name of the region (e.g., "West Coast")                                                                                       |
| &nbsp;&nbsp;&nbsp;&nbsp;Region Link                 | String (URL)                 | Link to a Crunchbase search for companies in that region                                                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;Region Type                 | String                       | Type of region (e.g., "group" for broader regions)                                                                            |
| **Headquarter Location**                            | List of Objects              | More specific details about the company's headquarters location. Each object contains:                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;Location Name               | String                       | Name of the city, region, country, or continent                                                                               |
| &nbsp;&nbsp;&nbsp;&nbsp;Location Link               | String (URL)                 | Link to a Crunchbase search for companies in that location                                                                    |
| &nbsp;&nbsp;&nbsp;&nbsp;Location Type               | String                       | Type of location (e.g., "city", "country")                                                                                    |
| **Founders**                                        | List of Objects              | Information about the company's founders. Each object contains:                                                               |
| &nbsp;&nbsp;&nbsp;&nbsp;Founder Name                | String                       | Name of the founder                                                                                                           |
| &nbsp;&nbsp;&nbsp;&nbsp;Founder Link                | String (URL)                 | Link to the founder's Crunchbase profile                                                                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;Founder Image               | String (URL)                 | Link to the founder's image                                                                                                   |
| **Products**                                        | List of Objects              | Products or services offered by the company. Each object contains:                                                            |
| &nbsp;&nbsp;&nbsp;&nbsp;Product Name                | String                       | Name of the product or service                                                                                                |
| &nbsp;&nbsp;&nbsp;&nbsp;Product Description         | String                       | Brief description of the product or service                                                                                   |
| **Number of Investors**                             | Number                       | Total number of investors who have funded the company                                                                         |
| **Investors**                                       | List of Objects              | Details about each investor. Each object contains:                                                                            |
| &nbsp;&nbsp;&nbsp;&nbsp;Lead Investor?              | Boolean (true/false or null) | Indicates if the investor led a particular funding round                                                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;Investment Title            | String                       | Short description of the investment (e.g., "[Investor Name] investment in [Funding Round]")                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;Investment Link             | String (URL)                 | Link to the Crunchbase page with investment details                                                                           |
| &nbsp;&nbsp;&nbsp;&nbsp;Partners Involved           | List of Objects              | Names and links to Crunchbase profiles of individuals from the investment firm involved in the deal                           |
| &nbsp;&nbsp;&nbsp;&nbsp;Funding Round Title         | String                       | Title of the funding round in which the investment was made                                                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;Funding Round Link          | String (URL)                 | Link to the Crunchbase page for that funding round                                                                            |
| &nbsp;&nbsp;&nbsp;&nbsp;Investor Name               | String                       | Name of the investing organization or individual                                                                              |
| &nbsp;&nbsp;&nbsp;&nbsp;Investor Image              | String (URL)                 | Link to the investor's logo or image                                                                                          |
| &nbsp;&nbsp;&nbsp;&nbsp;Investor Link               | String (URL)                 | Link to the Crunchbase profile of the investor                                                                                |
| **Similar Companies**                               | List of Objects              | List of companies deemed similar by Crunchbase. Each object contains:                                                         |
| &nbsp;&nbsp;&nbsp;&nbsp;Company Name                | String                       | Name of the similar organization                                                                                              |
| &nbsp;&nbsp;&nbsp;&nbsp;Company Image               | String (URL)                 | Link to the company's logo                                                                                                    |
| &nbsp;&nbsp;&nbsp;&nbsp;Company Link                | String (URL)                 | Link to the company's Crunchbase profile                                                                                      |
| **Organization Similarity Insight**                 | String                       | Crunchbase's insights into why the listed similar companies are considered related                                            |
| **Total Funding**                                   | Number                       | Total amount of funding raised by the company (in USD)                                                                        |
| **Funding Currency**                                | String                       | Currency in which the total funding is represented                                                                            |
| **Number of Funding Rounds**                        | Number                       | Total number of funding rounds the company has gone through                                                                   |
| **Last Funding Type**                               | String                       | Type of the most recent funding round (e.g., "seed", "series_a")                                                              |
| **Last Funding Date**                               | Date                         | Date when the last funding round was announced                                                                                |
| **Funding Rounds**                                  | List of Objects              | Details about each funding round. Each object contains:                                                                       |
| &nbsp;&nbsp;&nbsp;&nbsp;Round Title                 | String                       | Title of the funding round                                                                                                    |
| &nbsp;&nbsp;&nbsp;&nbsp;Round Link                  | String (URL)                 | Link to the Crunchbase page for the funding round                                                                             |
| &nbsp;&nbsp;&nbsp;&nbsp;Announced Date              | Date                         | Date the funding round was publicly announced                                                                                 |
| &nbsp;&nbsp;&nbsp;&nbsp;Money Raised                | Number                       | Amount of money raised in this round                                                                                          |
| &nbsp;&nbsp;&nbsp;&nbsp;Money Raised Currency       | String                       | Currency of the money raised                                                                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;Number of Investors         | Number                       | Number of investors who participated in this round                                                                            |
| &nbsp;&nbsp;&nbsp;&nbsp;Lead Investors              | List of Objects              | Information about the lead investors in the round                                                                             |
| **Company Timeline**                                | List of Objects              | A chronological list of significant events, including funding rounds, acquisitions, and press mentions. Each object contains: |
| &nbsp;&nbsp;&nbsp;&nbsp;Event Type                  | String                       | Type of event (e.g., "funding_round", "press_reference")                                                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;Author                      | String                       | Author of a press reference or news article                                                                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;URL                         | String (URL)                 | Link to the original source of the event (if available)                                                                       |
| &nbsp;&nbsp;&nbsp;&nbsp;Publisher                   | String                       | Name of the publication or source                                                                                             |
| &nbsp;&nbsp;&nbsp;&nbsp;Thumbnail                   | String (URL)                 | Link to an image related to the event                                                                                         |
| &nbsp;&nbsp;&nbsp;&nbsp;Investment Type             | String                       | Type of investment for funding events                                                                                         |
| &nbsp;&nbsp;&nbsp;&nbsp;Money Raised (USD)          | Number                       | Amount raised for funding events (in USD)                                                                                     |
| &nbsp;&nbsp;&nbsp;&nbsp;Money Raised (Currency)     | String                       | Original currency of the money raised                                                                                         |
| &nbsp;&nbsp;&nbsp;&nbsp;Money Raised (Value)        | Number                       | Amount raised for funding events (in original currency)                                                                       |
| &nbsp;&nbsp;&nbsp;&nbsp;Title                       | String                       | Title of the event or article                                                                                                 |
| &nbsp;&nbsp;&nbsp;&nbsp;Date                        | Date                         | Date of the event                                                                                                             |
| **Global Rank (SEMrush)**                           | Number                       | Website's global ranking according to SEMrush data                                                                            |
| **Monthly Visits (SEMrush)**                        | Number                       | Estimated monthly website visits based on SEMrush data                                                                        |
| **Location Data (SEMrush)**                         | List of Objects              | Breakdown of website traffic by geographic location. Each object in the list contains:                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;Location Rank               | Number                       | Website's ranking within that specific location                                                                               |
| &nbsp;&nbsp;&nbsp;&nbsp;Location                    | String                       | Name of the location (e.g., "United States, North America")                                                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;Visits Percent              | Number                       | Percentage of total website visits coming from this location                                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;Visits MoM Percent          | Number                       | Month-over-month percentage change in visits from this location                                                               |
| &nbsp;&nbsp;&nbsp;&nbsp;Rank MoM Percent            | Number                       | Month-over-month percentage change in the website's rank within this location                                                 |
| **Technologies Used (BuiltWith)**                   | List of Objects              | Technologies identified by BuiltWith as being used on the company's website. Each object contains:                            |
| &nbsp;&nbsp;&nbsp;&nbsp;Technology                  | String                       | Name of the technology (e.g., "nginx", "Cloudflare Hosting")                                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;Category                    | List of Strings              | Categories the technology belongs to (e.g., "web server", "hosting")                                                          |
| &nbsp;&nbsp;&nbsp;&nbsp;Number of Companies Using   | Number                       | Approximate number of companies BuiltWith has identified as using this technology                                             |
| **Current Advisors**                                | List of Objects              | Information about individuals currently advising the company. Each object contains:                                           |
| &nbsp;&nbsp;&nbsp;&nbsp;Advisor Name                | String                       | Name of the advisor                                                                                                           |
| &nbsp;&nbsp;&nbsp;&nbsp;Advisor Image               | String (URL)                 | Link to the advisor's image                                                                                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;Advisor Link                | String (URL)                 | Link to the advisor's Crunchbase profile                                                                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;Job Title                   | String                       | Advisor's role or title within the company                                                                                    |
| &nbsp;&nbsp;&nbsp;&nbsp;Job Link                    | String (URL)                 | Link to the advisor's job profile on Crunchbase                                                                               |
| &nbsp;&nbsp;&nbsp;&nbsp;Job Type                    | String                       | General type of advisory role (e.g., "advisor", "board_member")                                                               |
| &nbsp;&nbsp;&nbsp;&nbsp;Start Date                  | Date                         | Approximate date the advisor started in this role                                                                             |
| &nbsp;&nbsp;&nbsp;&nbsp;Start Date Precision        | String                       | Level of precision for the start date (e.g., "month", "year")                                                                 |
| **Acquisitions**                                    | List of Objects              | List of companies acquired by this company. Each object contains:                                                             |
| &nbsp;&nbsp;&nbsp;&nbsp;Acquired Company Name       | String                       | Name of the acquired company                                                                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;Acquired Company Image      | String (URL)                 | Link to the acquired company's image                                                                                          |
| &nbsp;&nbsp;&nbsp;&nbsp;Acquired Company Link       | String (URL)                 | Link to the acquired company's Crunchbase profile                                                                             |
| &nbsp;&nbsp;&nbsp;&nbsp;Announcement Date           | Date                         | Date the acquisition was publicly announced                                                                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;Announcement Date Precision | String                       | Level of precision for the announcement date                                                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;Acquisition Link            | String (URL)                 | Link to the Crunchbase page for the acquisition                                                                               |
| **Current Employees (Featured)**                    | List of Objects              | Information about key employees. Each object contains:                                                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;Employee Name               | String                       | Name of the employee                                                                                                          |
| &nbsp;&nbsp;&nbsp;&nbsp;Employee Link               | String (URL)                 | Link to the employee's Crunchbase profile                                                                                     |
| &nbsp;&nbsp;&nbsp;&nbsp;Employee Image              | String (URL)                 | Link to the employee's image                                                                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;Job Title                   | String                       | Employee's job title at the company                                                                                           |
| &nbsp;&nbsp;&nbsp;&nbsp;Job Link                    | String (URL)                 | Link to the employee's job on Crunchbase                                                                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;Start Date                  | Date                         | Approximate date the employee started in this role                                                                            |
| &nbsp;&nbsp;&nbsp;&nbsp;Start Date Precision        | String                       | Level of precision for the start date                                                                                         |
| **Number of Sub-Organizations**                     | Number                       | The number of subsidiaries or child organizations the company has                                                             |
| **Sub-Organizations**                               | List of Objects              | Information about the company's sub-organizations. Each object contains:                                                      |
| &nbsp;&nbsp;&nbsp;&nbsp;Ownership Link              | String (URL)                 | Link to the ownership relationship on Crunchbase                                                                              |
| &nbsp;&nbsp;&nbsp;&nbsp;Sub-Organization Name       | String                       | Name of the sub-organization                                                                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;Sub-Organization Link       | String (URL)                 | Link to the sub-organization's Crunchbase profile                                                                             |
| &nbsp;&nbsp;&nbsp;&nbsp;Ownership Type              | String                       | Type of ownership relationship (e.g., "subsidiary")                                                                           |
| **Visits MoM Percent (SEMrush)**                    | Number                       | Month-over-month percentage change in the website's total visits                                                              |
| **Total Apps (Apptopia)**                           | Number                       | Total number of mobile apps associated with the company (according to Apptopia)                                               |
| **Total Downloads (Apptopia)**                      | Number                       | Total downloads of the company's apps (Apptopia data)                                                                         |
| **App Overview (Apptopia)**                         | List of Objects              | Details about each mobile app. Each object contains:                                                                          |
| &nbsp;&nbsp;&nbsp;&nbsp;App Link (Crunchbase)       | String (URL)                 | Link to the app on Crunchbase (if available)                                                                                  |
| &nbsp;&nbsp;&nbsp;&nbsp;App Link (Apptopia)         | String (URL)                 | Link to the app on Apptopia                                                                                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;App Name                    | String                       | Name of the app                                                                                                               |
| &nbsp;&nbsp;&nbsp;&nbsp;App Stores                  | List of Strings              | List of app stores where the app is available (e.g., "google_play", "itunes_connect")                                         |
| &nbsp;&nbsp;&nbsp;&nbsp;Monthly Downloads           | Number                       | Estimated monthly downloads for the app                                                                                       |
| **Downloads MoM Percent (Apptopia)**                | Number                       | Month-over-month percentage change in total app downloads                                                                     |
| **Acquired By**                                     | String                       | Name of the acquiring company (if applicable)                                                                                 |
| **Acquired By Image**                               | String (URL)                 | Link to the acquiring company's image                                                                                         |
| **Acquired By Link**                                | String (URL)                 | Link to the acquiring company's Crunchbase profile                                                                            |
| **Acquisition Date**                                | Date                         | Date the acquisition was announced                                                                                            |
| **Acquisition Date Precision**                      | String                       | Level of precision for the acquisition date                                                                                   |
| **Acquisition Link**                                | String (URL)                 | Link to the acquisition on Crunchbase                                                                                         |
| **Acquisition Price**                               | Number                       | Price of the acquisition (in original currency)                                                                               |
| **Acquisition Price Currency**                      | String                       | Original currency of the acquisition price                                                                                    |
| **Acquisition Price (USD)**                         | Number                       | Acquisition price converted to USD                                                                                            |
| **Patents Granted (IPqwery)**                       | Number                       | Number of patents granted to the company (from IPqwery data)                                                                  |
| **Trademarks Registered (IPqwery)**                 | Number                       | Number of trademarks registered by the company (IPqwery data)                                                                 |
| **Popular Trademark Class (IPqwery)**               | String                       | The most common trademark class for the company's registered trademarks (IPqwery data)                                        |
| **Contacts Summary**                                | List of Objects              | Summary information about contacts associated with the company. Each object contains:                                         |
| &nbsp;&nbsp;&nbsp;&nbsp;Contact Name                | String                       | Name of the contact                                                                                                           |
| &nbsp;&nbsp;&nbsp;&nbsp;Contact LinkedIn            | String (URL)                 | Link to the contact's LinkedIn profile                                                                                        |
| &nbsp;&nbsp;&nbsp;&nbsp;Contact Job Levels          | List of Strings              | Hierarchy levels of the contact's job title                                                                                   |
| &nbsp;&nbsp;&nbsp;&nbsp;Contact Job Titles          | List of Strings              | List of the contact's job titles                                                                                              |
| &nbsp;&nbsp;&nbsp;&nbsp;Contact Departments         | List of Strings              | Company departments the contact is associated with                                                                            |
| **Growth Insight**                                  | String                       | Crunchbase's analysis of potential growth factors for the company                                                             |
| **IT Spend (Aberdeen)**                             | Number                       | Estimated IT spending by the company (from Aberdeen data)                                                                     |
| **IT Spend Currency (Aberdeen)**                    | String                       | Currency of the IT spend data                                                                                                 |
| **IT Spend (USD) (Aberdeen)**                       | Number                       | IT spending converted to USD                                                                                                  |
| **News Headlines**                                  | Number                       | Number of recent news articles about the company                                                                              |
| **Technologies Used (BuiltWith)**                   | Number                       | Total number of technologies identified by BuiltWith for the company's website                                                |
| **Total Funding Value**                             | Number                       | Total amount of funding raised (in the original currency)                                                                     |
| **Total Funding Currency**                          | String                       | Currency of the total funding                                                                                                 |
| **Total Funding (USD)**                             | Number                       | Total funding converted to USD                                                                                                |
| **Number of Funding Rounds**                        | Number                       | Total number of funding rounds                                                                                                |
| **Number of Investors**                             | Number                       | Total number of investors                                                                                                     |
| **Number of Lead Investors**                        | Number                       | Total number of times investors acted as lead investors                                                                       |
| **Number of Acquisitions**                          | Number                       | Number of companies acquired by this company                                                                                  |
| **IPO Status**                                      | String                       | Public offering status (e.g., "private", "public", "delisted")                                                                |
| **Organization Rank**                               | Number                       | Crunchbase's internal ranking for the company                                                                                 |
| **News Insight**                                    | String                       | Summary of key insights from recent news about the company                                                                    |
| **Last Updated (SEMrush)**                          | Date                         | Date when SEMrush data was last updated for this company                                                                      |
| **Legal Name**                                      | String                       | Company's official registered name                                                                                            |
| **Hub Tags**                                        | List of Strings              | Tags or labels assigned to the company by Crunchbase, often indicating its status or potential (e.g., "emerging_unicorn")     |
