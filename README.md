# IODlab10

Link to app is: https://iodlab10-sentiment-analysis.streamlit.app/


---

flowchart TD
    A[Load Data from SQLite] --> B[Data Cleaning - missing values, outliers, types]
    B --> C[Feature Engineering - duration, encoding, scaling]
    C --> D[Train/Test Split]
    D --> E[Model Training - Baseline + Tuned]
    E --> F[Evaluation + Model Selection]
    F --> G[Save Best Model & Metrics]
