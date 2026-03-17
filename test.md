graph TD
    A[Start ETL] --> B{Check Env}
    B -- Dev --> C[Load Sample Data]
    B -- Prd --> D[Load Full Data]
    C --> E[Transform]
    D --> E[Transform]
    E --> F[End]
