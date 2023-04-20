
# Advertools ID support

The extension for Advertools SEO crawler allows users to pass a list of nested dictionaries, where each dictionary contains a URL and an ID, to the crawler. The output JSON then includes both the URL and ID for each page crawled.





## Usage

- download the folder and place it in your site-packages
- use it
## Usage/Examples

```python
import advertools as adv

set = [[1234, "http://www.wohnen-fasching.com"], ["555548", "http://www.bidner.at"], ["34452", "http://www.architektehrlich.at"]]

adv.crawl(set, 'test.jl', follow_links=False)
```


## Sample output

![App Screenshot](https://user-images.githubusercontent.com/81706755/233412751-509fb896-a5bd-441b-8f1c-bca27f0f90a5.png)

