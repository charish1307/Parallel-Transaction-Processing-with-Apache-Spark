# ⚡ Parallel Transaction Processing with Apache Spark

[![Language](https://img.shields.io/badge/Language-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)]()
[![Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)]()
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)]()

## 📌 Project Overview

This project presents a **comparative study** of **Serial vs Parallel computing** methods for transaction processing using **Apache Spark**. The goal is to demonstrate the efficiency gains achieved through distributed computing and parallel processing for large-scale financial transaction datasets.

## 🎯 Objectives

- Compare execution time between serial and parallel transaction processing
- - Implement distributed data processing using Apache Spark (PySpark)
  - - Analyze scalability and performance improvements with parallel computing
    - - Visualize performance benchmarks and speedup ratios
     
      - ## 🛠️ Technologies Used
     
      - | Tool/Library | Purpose |
      - |---|---|
      - | **Apache Spark (PySpark)** | Distributed parallel processing engine |
      - | **Python** | Primary programming language |
      - | **Jupyter Notebook** | Interactive development environment |
      - | **Pandas** | Serial data processing baseline |
      - | **Matplotlib** | Performance visualization |
      - | **time / datetime** | Execution time measurement |
     
      - ## 📊 Dataset
     
      - - **Domain:** Financial transactions
        - - **Size:** Large-scale transaction records
          - - **Attributes:** Transaction ID, Amount, Timestamp, Category, Status
           
            - ## 🔬 Methodology
           
            - 1. **Serial Processing** — Implement transaction processing using standard Python/Pandas
              2. 2. **Parallel Processing** — Implement the same logic using Apache Spark RDDs/DataFrames
                 3. 3. **Benchmarking** — Measure and compare execution times for both approaches
                    4. 4. **Scalability Test** — Test performance across different data sizes
                       5. 5. **Analysis** — Calculate speedup ratio and efficiency metrics
                          6. 6. **Visualization** — Plot performance comparison charts
                            
                             7. ## 📈 Key Results
                            
                             8. - Parallel processing with Spark significantly outperformed serial processing
                                - - Demonstrated near-linear speedup with increasing data volume
                                  - - Spark's lazy evaluation and in-memory processing provided major efficiency gains
                                   
                                    - ## 🚀 How to Run
                                   
                                    - ```bash
                                      # Clone the repository
                                      git clone https://github.com/charish1307/Parallel-Transaction-Processing-with-Apache-Spark.git
                                      cd Parallel-Transaction-Processing-with-Apache-Spark

                                      # Install dependencies
                                      pip install pyspark pandas matplotlib jupyter

                                      # Launch Jupyter Notebook
                                      jupyter notebook
                                      ```

                                      ### Prerequisites
                                      - Java 8 or higher (required for Apache Spark)
                                      - - Python 3.7+
                                        - - Apache Spark 3.x
                                         
                                          - ## 👤 Author
                                         
                                          - **Charish Yadavali** | [GitHub](https://github.com/charish1307) | [LinkedIn](https://www.linkedin.com/in/charishyadavali)
                                         
                                          - ---
                                          *University of Massachusetts Dartmouth — Parallel & Distributed Computing*
