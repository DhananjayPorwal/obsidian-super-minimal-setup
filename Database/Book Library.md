---
cssClasses: cards, cards-cover, cards-2-3, table-max
tags: database
---
# How I rate the book?

| Rating     | Emoji | Conclusion                      |
| ---------- | ----- | ------------------------------- |
| ⭐         | 🤮    | Not Recommended                 |
| ⭐⭐       | 🤕    | Can read it once                |
| ⭐⭐⭐     | 😀    | Must understand the key concept |
| ⭐⭐⭐⭐   | 🤩    | Must read it twice-thrice       |
| ⭐⭐⭐⭐⭐ | 😍    | Read it at least 5 times        |

```dataview
Table author as Author, ("![|100](" + cover + ")") as Cover, rating,category
From "Book Summaries"
Where contains(status, ["to read","complete"])
```
