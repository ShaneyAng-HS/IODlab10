# IODlab10

Link to app is: https://iodlab10-sentiment-analysis.streamlit.app/


---

## 🔄 Pipeline Logic / Flow

```mermaid
flowchart TD
    A[Load Data from SQLite] --> B[Data Cleaning\n(missing values, outliers, types)]
    B --> C[Feature Engineering\n(duration, encoding, scaling)]
    C --> D[Train/Test Split]
    D --> E[Model Training\n(Baseline + Tuned)]
    E --> F[Evaluation + Model Selection]
    F --> G[Save Best Model & Metrics]
```

---
