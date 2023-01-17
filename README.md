# PySearch

```python
from pysearch import GoogleSearch, BingSearch
from pprint import pprint

with GoogleSearch() as search:
    search.query = "klavye"
    search.page = 2
    all_links = search.links
    
# search = pysearch.BingSearch("mouse",3)
# pprint(search.links)


# with pysearch.BingSearch() as search:
#     search.query = "klavye"
#     search.page = 3
#     pprint(search.links)
```
