# Hi, I'm Georges 👋

#### **Computer Science Student · Data Engineering**

I am a Computer Science student at École 42 Paris, focusing on Data Engineering through hands-on projects and self-directed learning. I am particularly interested in building reliable data pipelines, designing data architectures, and developing efficient data processing workflows, with a strong focus on data quality, validation, observability, and performance.  

---

## 📂 Featured Projects

### [European Air Quality](https://github.com/gwen-mp4/europe-air-quality)
**Personal project · Work in progress**  
An end-to-end batch ELT pipeline for European air quality data from the European Environment Agency (EEA), with a focus on data quality, metadata integration and reliable data processing.  
<ins>**Scope — Pipeline design, implementation and data visualization**</ins>  
<ins>**Technologies:**</ins>  
Python · uv · AWS S3 · Parquet · DuckDB · dbt · Evidence · GitHub Actions

- Python-based ingestion of EEA Parquet archives into an AWS S3 data lake
- Medallion architecture (bronze, silver, gold) implemented with dbt and DuckDB
- Processing of 540M+ hourly measurements on a single machine
- Data quality rules based on EEA validity codes, including sentinel handling and quality flags
- Geospatial station dimension built by integrating measurement data with EEA sampling point metadata
- dbt tests and documentation across staging, intermediate and mart models
- Interactive station map built with Evidence
- CI workflow with GitHub Actions

*Next: Optionally, ingestion of recent unverified data (E2a) with pipeline orchestration.*

### [Cryptocurrency Paper Trading Platform](https://github.com/Frogus-ex/ft_transcendence)  
**Group project · École 42**  
A full-stack paper trading platform based on real-time cryptocurrency
market data from Binance.  
<ins>**My contribution — Data Ingestion & API Server Backend**</ins>  
<ins>**Technologies:**</ins>  
Python · FastAPI · RedisTimeSeries · Celery · PostgreSQL · WebSockets  

- Real-time market data ingestion
- Data validation and transformation
- RedisTimeSeries for market data processing
- Celery background processing
- PostgreSQL data persistence
- FastAPI backend and WebSockets  

---

## 📬 Let's Connect

LinkedIn: **www.linkedin.com/in/georges-xin-wen-10092a361**  
Email: **wengeorgesxin@gmail.com**  
