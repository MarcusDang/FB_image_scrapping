

# Facebook Image Scraper

This is a Python program that allows you to scrape images from Facebook by accessing specific pages, groups, or hashtags. It uses web scraping techniques to extract the image links and download the images to a specified folder on your local machine. 

The program is developed based on the tutorial and code repository of MariyaSha available on [YouTube](https://www.youtube.com/watch?v=SsXcyoevkV0) and [GitHub](https://github.com/MariyaSha/WebscrapingFacebook/blob/main/FB_Scraper.ipynb). The program also requires skills in web scraping, data engineering, and Python development.

## Process

The following steps outline the process of this program:

- Access Facebook using the ChromeDriver
- Log in to Facebook using hardcoded credentials (username and password)
- Access specific links or groups using the GET method
- Scroll down to load information on dynamic interfaces (such as Facebook)
- Extract the links of images by finding the tag name "a" for link and getting the "href" attribute, then filter only href related to photos
- Access the particular links to view the source picture (not thumbnail with compressed quality)
- Extract the link of the source picture by finding the tag "img" and getting the "src" attribute
- Create a target folder with the OS package
- Download images by specific links scraped already

Note: The process may take some time to scroll down the page and extract the links of the images.

## Discussion for improvement

There are some possible improvements that can be made to this program, including:

- Scrap images via hashtag or log in specific groups
- Using a sample page-loading process to access and extract post content and comments
    - [https://nocodewebscraping.com/facebook-scraper/](https://nocodewebscraping.com/facebook-scraper/)
- Using Facebook's API to request data (not studied yet)
    - [https://developers.facebook.com/docs/graph-api/batch-requests](https://developers.facebook.com/docs/graph-api/batch-requests)
    - [https://developers.facebook.com/docs/graph-api/overview/rate-limiting](https://developers.facebook.com/docs/graph-api/overview/rate-limiting)
- Applying the same methods for other pages, such as Instagram, Twitter, or news websites
- Being aware that some websites may have mechanisms to prevent web scraping activities.

## Conclusion

This program provides a straightforward solution to scraping images from Facebook pages, groups, and hashtags. With the possibility of improvement, it can be a useful tool for data collection and analysis.
