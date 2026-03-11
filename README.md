"# project_databricks_bikestore" 

```
│
├── bikestore/
│   ├── resource/                 # Dados de suporte e interface
│   │   ├── origem/               # Arquivos brutos recebidos (CSV, Parquet, JSON)
│   │   └── destino/              # Arquivos exportados para consumo externo
│   │
│   ├── bronze/                   # Dados crus (Raw Layer)
│   │
│   ├── silver/                   # Dados limpos e transformados (Silver Layer)
│   │
│   ├── gold/                     # Dados agregados e prontos para Analytics (Gold Layer)
```