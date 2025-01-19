# ai_engineering_practice
plan for AI engineering practice
```
1. Data Colelctor
- using python
- MongoDB for data storage
- crawler for data collection (linkedin, medium, github, substack...)
-- log in using credentials
-- selenium to crawl a profile
-- beatifulSoup to parse the html
-- clean & normalize the extracted html
-- save to mongodb

-- capture by log tailing mongodb (CDC pattern)(change data capture)
- rabbit mq to be used as a message broker for the data pipeline
- qdrant for a vector db
2. Feature Pipeline
- implemented using Bytewax (Rust streaming engine with a python interface)
- ingestion component (RAG system)
-- clean data, chunk data, embed data, and store at vector db
3. Training Pipeline
4. Inference Pipeline
```