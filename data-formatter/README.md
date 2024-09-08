## Data Formatter

* Converts a table in messy format into a specific, defined output (works best with JSON or YAML). Table may be copied from the front end of a website, it will usually identify the right columns for you. It struggles with merged cells or total rows/columns.
* It may be important to specify the elements you want as this may be interpreted differently for different entries e.g. if you copy data for political parties and one party has co-leaders vs single leaders this may make the names not match.
* In principle, this should work for CSV output however I have found that LLMs are quite poor at generating CSV files and JSON is more reliable.
* Very large tables might only be partially included, in this case, typing “continue” will make it finish, redoing the row it ended on. They will need to be manually merged together.
* You may have some rows or columns that you don’t need e.g. totals or percentages that you can work out later - include these in the relevant lists.
* This usually works out rows and columns for itself even if the table is printed in one line but it is best to check it.
* This can be used in the same chat by copying and pasting a new table without comment.
* This works well with fast models like Claude 3 Haiku. As long as it copies the text accurately, use the fastest/cheapest one available.
