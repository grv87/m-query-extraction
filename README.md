# m-query-extraction
Extract M queries (Power Query) from xlsx files

Usage:
```
extract_m_queries.py "path\file.xlsx"
```
or, if you don't have `py` in `PATHEXT`, then
```
py -3 extract_m_queries.py "path\file.xlsx"
```

The script keeps directory layout and file names.
Queries are expected to be in `Formulas\Section1.m` file, but no guaranties.
