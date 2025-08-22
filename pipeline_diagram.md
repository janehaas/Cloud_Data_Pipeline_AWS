flowchart LR
    A[Lab Instrument Data] --> B[S3 Data Lake]
    B --> C[AWS Lambda ETL]
    C --> D[DynamoDB (Processed Data)]
    D --> E[Analytics Layer]
    E --> F[Tableau / Power BI Dashboard]
