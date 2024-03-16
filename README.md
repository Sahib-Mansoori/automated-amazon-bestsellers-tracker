# automated-amazon-bestsellers-tracker
Aims to implement an automated solution to keep a track of top 30 products in 10 different categories every day on Amazon and send the curated information to a target daily. This automated process ensures regular updates on trending products without any manual intervention.


# Project Description:

This project involves implementing a Python script with Selenium WebDriver to navigate in each category and fetch the details of the top best-selling and trending products on Amazon every day. It involves tracking various information like price, product ranking, star ratings, and number of ratings alongside link and image of each product. This data then automatically exported to a telegram channel in order to analyse further for market trends, best deals, or product performance tracking.

# Technical Details:
- Language and library: Python and Selenium WebDriver

- Methodology: Automation, Web scraping, and API invoking

- AWS Services: AWS Lambda and AWS CloudWatch

- Integration: Telegram API for sending data to a telegram channel

- Script Execution: The Python script is deployed on AWS Lambda invoked at a desired time, daily triggered by another AWS service called AWS CloudWatch

# Results Achieved:

    - Helps keep a track of best deals and trends on the e-commerce website.
    - Reduce the manual effort to help me focus on other tasks like analysis or product performance track on the platform.
    - Telegram API integration provides the convenience of accessing the data directly to the channel automatically on daily basis.

# Challenges and Solutions:
- Challenges: It became difficult to implement a script that executes on daily basis from local machines in terms of resources and human error.

- Solution: AWS Lambda, a server-less computing solution seemed an optimal choice to execute the scheduled automation script without the need of local machine or resources.

# Conclusion and Future Steps:
This project successfully demonstrates the implementation of Python automation for fetching and delivering the information about Amazon’s top 30 products from each of the 10 defined category with Selenium implemented on AWS Lambda and by integrating Telegram API. The execution and ability to fetch regular updates make it a practical solution to track and analyse the market trend and products.
## Feature improvement may include:

    - Improve the error handling mechanism for a robust performance.
    - Implementation of price comparison between different products.
    - Send the results to other target instead of Telegram to perform various other functions on the data as required.

