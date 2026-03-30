# GBCML1 — Web Scraping with Python

A Python web scraping project built as part of the AI/ML Dev program at George Brown College. 
Scrapes and processes a technical article on neural networks using Requests and BeautifulSoup, 
with results documented in both a script and Jupyter Notebook.

---

## What this project does

- Fetches a web-archived Medium article using the `requests` library
- Parses and extracts the full article text with `BeautifulSoup4`
- Documents the full workflow in a Jupyter Notebook for reproducibility
- Outputs the scraped content to a text file for downstream use

---

## Source

**Article:** [Papa, what is a neural network?](https://web.archive.org/web/20191126074327/https://medium.com/@subashgandyer/papa-what-is-a-neural-network-c5e5cc427c7)  
**Author:** Subash Gandyer  
**Accessed via:** Wayback Machine (Internet Archive)

---

## Files

| File | Description |
|------|-------------|
| `Task1_Python_script_akb.py` | Standalone Python scraping script |
| `Task1_Python_script_akb.ipynb` | Jupyter Notebook version with commentary |
| `papa-what-is-a-neural-network-c5e5cc427c7.txt` | Scraped article output |

---

## How to run
```bash
# Install dependencies
pip install requests beautifulsoup4

# Run the script
python Task1_Python_script_akb.py
```

---

## What I learned

- How to send HTTP requests and handle responses in Python
- Parsing HTML structure with BeautifulSoup selectors
- Structuring a data pipeline from fetch → parse → output
- Documenting technical work in Jupyter Notebooks

---

## Tech stack

`Python` `BeautifulSoup4` `Requests` `Jupyter Notebook`
