# ArXiv Knowledge Graph
A knowledge graph based on ArXiv mathematics articles. Built using Neo4j-AuraDB and Cypher language.
This is a good KG to use as an working example in various projects. The data was enhanced using KeyLLM and hdbscan, but it can be improved and refined further. It will be updated and enriched as needed. 
The graph schema:
![raw_entry](./arXiv_KG/imgs/schema_visual.png)

The node attributes are given below:
```
 'Article': ['abstract', 'article_id', 'comments', 'title']
 'Keyword': ['name', 'key_id']
 'Topic': ['cluster', 'description', 'label']
 'Author': ['author_id', 'affiliation', 'first_name', 'last_name']
 'DOI': ['name', 'doi_id']
 'Categories': ['category_id', 'specifications']
 'Report': ['report_id', 'report_no']
 'UpdateDate': ['update_date']
 'Journal': ['name', 'journal_id']
```
