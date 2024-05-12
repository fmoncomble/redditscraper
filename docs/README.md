![redditscraper_banner](https://github.com/fmoncomble/redditscraper/assets/59739627/41697339-9b63-48e2-a2ab-e9d0c39baeb1)

[(Version française)](https://fmoncomble.github.io/redditscraper/README_fr.html)

An extension for extracting and downloading Reddit posts for text mining and analysis.  
  
### Cite this program
If you use this extension for your research, please reference it as follows:  
  
Moncomble, F. (2024). *RedditScraper* (Version 0.2) [JavaScript]. Arras, France: Université d'Artois. Available at: https://fmoncomble.github.io/redditscraper/

## Installation
### Firefox
[![Firefox add-on](https://github.com/fmoncomble/Figaro_extractor/assets/59739627/e4df008e-1aac-46be-a216-e6304a65ba97)](https://github.com/fmoncomble/redditscraper/releases/latest/download/redditscraper.xpi)  
### Chrome/Edge
[![available-chrome-web-store4321](https://github.com/fmoncomble/redditscraper/assets/59739627/dad5ba48-c049-4b76-8d37-cd1a01ba4107)](https://chromewebstore.google.com/detail/redditscraper/pleejhomflbkocjhlpipghkgmoafpnok)
    
Remember to pin the add-on to the toolbar.
 
## Instructions for use
- Click the add-on's icon in the toolbar.
- On first using the add-on, follow the authentication procedure to authorize the app on Reddit. *All credentials are stored locally on your computer, **not** on a remote server.*
- Build your search query with at least one keyword, and click `Search`.
- Choose your preferred output format:
    - `XML/XTZ` for an XML file to import into [TXM](https://txm.gitpages.huma-num.fr/textometrie/en/index.html) using the `XML/TEI-Zero` module
      - When initiating the import process, open the "Textual planes" section and type `ref` in the field labelled "Out of text to edit"
    - `TXT` for plain text
    - `CSV`
    - `XLSX` (Excel spreadsheet)
    - `JSON`
- (Optional) Enter the maximum number of posts to collect.
- You can stop the process at any time by clicking `Abort`.
- Click `Download` to collect the output or `Reset` to start afresh.

## Known limitations
The Reddit search API only returns a selection of results.
