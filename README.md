# Web Scraping Project – MLK Speech

## Project Overview
This project demonstrates **web scraping using Python** to extract text from the webpage:  
 [Martin Luther King Jr. – “I Have a Dream” Speech](http://www.analytictech.com/mb021/mlk.htm)

The goal was to:
- Scrape the full speech text from the HTML page  
- Clean the raw HTML by removing tags and punctuation  
- Prepare the text for analysis  

---

## Tools & Libraries Used
- **Python**  
- **Requests** → To fetch the webpage  
- **BeautifulSoup (bs4)** → For parsing and extracting HTML content  
- **re (Regular Expressions)** → For text cleaning  
- **Jupyter Notebook** → For implementation  

---

## Project Workflow
1. **Fetch the Webpage**  
   Used `requests.get()` to retrieve the HTML content of the webpage.  

2. **Parse HTML with BeautifulSoup**  
   Extracted `<p>` tags containing the speech text.  

3. **Text Cleaning**  
   - Removed HTML tags  
   - Joined text paragraphs into one string  
   - Removed punctuation using regex  

4. **Final Clean Text**  
   A processed version of the speech, ready for further Natural Language Processing (NLP) or text analysis.  

---

##  Example Output
After cleaning, you get a plain text version of MLK’s famous speech that can be used for:  
- Word frequency analysis  
- Sentiment analysis  
- Keyword extraction  
- Topic modeling  

---
