# Database-Design-notes

# Storing Data

### Structured vs Unstructured vs Semi-structured
- SQL Tables
- Images, MP3
- JSON, XML, NoSQL

**Structured is easier to anlayse but less flexible and scalable**

## Data Storage Paradigms
### 1. Traditional Databases
- For storing real time relational structured data
- OLTP
### 2. Data Warehouses
- For analyzing archived structured data
- OLAP
- Optimized for read-only queries
- Optimized for anlaytics
- Contains data from multiple sources
- Massively Parallel Processisng is done
- Typically use dimensional modeling and dernormalized schema
- Cloud Data Warehouse Solutions:
    - AWS Redshift
    - GCP BigQuery
    - Azure SQL Data Warehouse
**Data Mart**
- Subset of data warehouses
- Dedicated to a specific topic
### 3. Data Lakes
- For storign data of all structures
- Flexible and Scalable
- For analyzing big data


