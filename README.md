# sqlite fts5 full search text search demo

I always forget that sqlite has a simple-to-use [extension](https://www.sqlite.org/fts5.html) (that comes with Python's built in version) allows for decent full text search.  

This is a reminder collab notebook [![1.1](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jermwatt/sqliteFST5demo/blob/master/sqlite_text_search_demo.ipynb#scrollTo=990354af) illustrates how to setup this full text search functionality on a small example dataset.  This is the "ASMR YouTube channels" [Kaggle dataset](https://www.kaggle.com/datasets/ulisesmontoyacanales/youtube-asmr-channels) - which some rich text columns detailing various facets of some ASMR YouTube channels (like a channel's `description`)
