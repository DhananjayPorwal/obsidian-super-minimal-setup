---
cssclasses:
  - cards
  - cards-cover
  - cards-2-3
  - table-max
tags:
  - database
  - movies
  - series
  - movies/series
---

```dataview
table without id
	("![](" + poster + ")") as Poster,
	file.link as Title,
	year as Year, director as Director,
	"⭐ " + scoreImdb as "⭐ IMDB"	
from "Movies"
where contains(status, "Complete")
```


