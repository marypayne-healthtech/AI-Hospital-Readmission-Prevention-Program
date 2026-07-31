# AI Data Lifecycle for Hospital Readmission Prediction

## Healthcare AI Data Flow

```mermaid
flowchart LR

A[Healthcare Data Sources]

A --> B[Data Collection]

B --> C[Data Cleaning & Preparation]

C --> D[Feature Engineering]

D --> E[Machine Learning Training]

E --> F[Model Validation]

F --> G[Clinical Deployment]

G --> H[Performance Monitoring]

H --> I[Model Improvement & Retraining]

I --> E
