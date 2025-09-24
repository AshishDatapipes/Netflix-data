#  Netflix Data Pipeline on Azure  
**Modular, fault-tolerant orchestration with layered ingestion, transformation, and gold-tier aggregation**

##  Overview  
This project demonstrates a resilient, cloud-native data pipeline built on Azure to ingest, transform, and aggregate Netflix viewing data. It reflects orchestration best practices, modular pipeline logic, and clear documentation—ideal for scalable analytics and real-world troubleshooting.

##  Architecture  
![Architecture Diagram] 
The pipeline follows a bronze-silver-gold architecture:

- **Bronze**: Raw ingestion via parameterized pipelines  
- **Silver**: Cleansed and transformed data using Azure Databricks  
- **Gold**: Aggregated insights ready for reporting and analytics  
- **Metastore**: Managed via Unity Catalog and custom schema registry

## 🔧 Tech Stack  
| Layer          | Tools Used                                                                 |
|----------------|------------------------------------------------------------------------------|
| Ingestion      | Azure Data Factory (UI), Azure Blob Storage, parameterized pipeline configs |
| Transformation | Azure Databricks (PySpark), Delta Lake, modular notebooks                   |
| Orchestration  | Azure Data Factory UI, Azure Databricks workflows, GitHub Actions           |
| Metadata       | Unity Catalog, custom metastore for schema management                       |
| Monitoring     | Default retry settings (disabled after 10 minutes), email alerts optional via Azure Monitor |
| Security       | Entra ID (RBAC integration), secure access policies                         |
| Documentation  | Annotated screenshots, README walkthrough, visual storytelling              |

## 📸 Visual Walkthrough  
Explore the pipeline in action through annotated screenshots:  
- ![Ingestion Flow]  
- ![Transformation Notebook]
- ![Gold Aggregation]

##  Features  
- Modular pipeline logic with reusable components  
- Parameterized ingestion for dynamic dataset handling  
- Visual documentation for transparency and collaboration  
- RBAC integration via Entra ID for secure access control  
- Optional email alerts via Azure Monitor

## Use Cases  
- Scalable analytics for media platforms  
- Fault-tolerant architecture for enterprise data lakes  
- Technical storytelling for portfolio and interviews

## 🎯 Career Pivot Context  
I’m a distributed data engineer passionate about building reliable, modular data pipelines. This project is part of my job search journey—showcasing what I can do with Azure, orchestration tools, and real-world datasets. I believe in clear documentation, fault-tolerant design, and making complex systems easy to understand. If you're hiring or collaborating, I’d love to connect.
