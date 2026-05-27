# Industrial Anomaly Detection
# Description
This system monitors industrial processes in real-time and automatically detects anomalies using Machine Learning. It is built on a modern data stack including Kafka, Spark, and Airflow, with ML models ranging from Isolation Forest to LSTM neural networks. Developed as a portfolio project to consolidate practical skills in MLOps and Big Data.

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Message Broker | Apache Kafka |
| Stream Processing | Apache Spark Structured Streaming |
| Orchestration | Apache Airflow |
| ML Models | Isolation Forest, Autoencoder, LSTM |
| Dashboard | Streamlit |
| Language | Python 3.11 |

## 📁 Project Structure
industrial-anomaly-detection/
├── infrastructure/    # Docker, Kafka, Spark config
├── ingestion/         # Kafka producer/consumer
├── processing/        # Spark Structured Streaming
├── features/          # Feature engineering
├── models/            # Training and evaluation
├── orchestration/     # Airflow DAGs
├── dashboard/         # Streamlit app
├── data/              # Sample data
├── notebooks/         # EDA and experiments
└── tests/             # Unit and integration tests
## 🗺️ Roadmap

- [ ] Phase 1 - Data Infrastructure (Kafka, Spark, Parquet)
- [ ] Phase 2 - Feature Engineering
- [ ] Phase 3 - ML Models
- [ ] Phase 4 - Orchestration & Dashboard
