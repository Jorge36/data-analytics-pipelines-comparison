# Evaluating and Comparing Single-Machine Analytics Tools and Distributed Big-Data Frameworks

## Overview



This repository contains documentation and experimental materials for my Master’s thesis in Data Analytics. As the research progresses, it will be extended with additional resources such as Jupyter notebooks, experimental results, and performance analyses.
The research evaluates and compares traditional single-machine analytics tools with distributed big-data frameworks, providing practical insights and guidelines for selecting the appropriate analytics stack based on data characteristics and deployment environments.



The study focuses on performance, scalability, and cost-efficiency across file formats, dataset sizes, local and cloud-based environments.

---

## Research Objectives

The primary objectives of this research are:

- To evaluate the performance, scalability, and cost-efficiency of traditional analytics tools (Pandas, Pandas SQL, Scikit-learn) versus distributed big-data frameworks (Hadoop, Spark, Spark SQL, Spark MLlib) across data sizes, file formats, configurations and deployment environments (local and cloud)
- To compare traditional and distributed data analytics stacks and analyse their respective advantages and disadvantages in both local and cloud environments
- To derive evidence-based guidelines for determining when traditional single-machine analytics tools should be used and when distributed big-data frameworks become the more appropriate choice  

---

## Research Design and Methodology

This study adopts a **quantitative, experimental research approach**, where performance metrics are collected from controlled computational experiments.

The evaluation spans the full analytics pipeline, from data ingestion to model training, using the following configurations:

### Single-Machine Analytics Pipeline
- Pandas for data loading and manipulation
- Pandas SQL for query execution
- Scikit-learn for model training

### Distributed Analytics Pipeline
- Apache Spark for distributed data processing
- Spark SQL for query execution
- Spark MLlib for model training

Experiments are conducted across varying:
- Data sizes
- File formats (CSV, Parquet and ORC)
- Hardware configurations
- Deployment environments (local and cloud)

Key metrics include execution time, throughput, resource utilisation, scalability, and cost efficiency.

---

## Datasets

The primary dataset used in this research is the **NYC TLC Yellow Trip Record Dataset**, obtained from NYC Open Data.

- The dataset contains neither direct personal identifiers nor sensitive data
- It is publicly available and permitted for academic use
- No attempts are made to re-identify individuals or combine data with external sources

---

## Ethical Considerations

This project is conducted solely for academic purposes and follows institutional ethical guidelines.

- Only de-identified public datasets are used
- GDPR principles are strictly respected
- No sensitive or personal data is collected, processed, or stored at any stage of the research
- Cloud-based experiments are executed in secure environments using encrypted storage, restricted access controls, and secure network configurations
- All cloud resources are terminated immediately after experimentation to minimise financial and environmental impact
- All tools used are open-source and released under permissive licences

---

## Repository Contents

- **research/** – Thesis proposal documents and presentation slides

---

## Technologies Used

- Python, Pandas, Pandas SQL
- Scikit-learn
- Apache Spark, Spark SQL, Spark MLlib
- Hadoop (HDFS)
- Jupyter Notebook
- AWS (for cloud-based experiments)

---

## Status

This thesis is currently **in progress**.  
The repository will be updated as experiments are completed and results are finalised.

---

## Author

**Jorge Alberto Robla López**  
Master of Science in Data Analytics  
CCT College, Dublin

GitHub: https://github.com/Jorge36
