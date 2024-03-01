Machine Learning for Internet Traffic Analysis
Welcome to the Machine Learning for Internet Traffic Analysis project repository! This project explores various aspects of machine learning applied to a Big Data framework, 
specifically focusing on classification and clustering techniques to measure and analyze Internet traffic. By leveraging PySpark and its machine learning library (pyspark.ml),
we aim to gain insights into network TCP connections and user behavior on the Internet.

Data Overview
The analysis utilizes a Tstat log file (log_tcp_complete_classes.txt), where each line represents a TCP connection. 
The log includes connection identifiers (client and server IP addresses and ports) and features such as packet count, bytes uploaded and downloaded, etc.

Analysis Approach
The project integrates classification and clustering tasks within the same files:

Classification of Internet Services and Clustering of User Behavior:
For each network TCP connection, identify and classify the service (e.g., Google, Amazon) generating the traffic.
Cluster users based on their behavior on the Internet.
Utilize PySpark's machine learning capabilities to train classification models and apply clustering techniques.
Employ Decision Tree and Random Forest models for classification tasks.
Utilize k-means and Gaussian Mixture Model (GMM) implementations for clustering.
Repository Structure
├── data/
│   └── log_tcp_complete_classes.txt   # Tstat log file containing TCP connection data
├── Python.ipynb                       # Jupyter notebook containing code for both classification and clustering tasks
├── PDF.pdf                            # PDF version of the Jupyter notebook
├── Python.py                          # Executable Python script containing code for both classification and clustering tasks
├── LICENSE                            # License information for the project
└── README.md                          # Detailed project overview, setup instructions, and usage guidelines

Getting Started
To replicate the analysis or explore the provided code and notebooks, follow these steps:

1. Clone this repository to your local machine.
2. Open the Python.ipynb notebook or Python.py script to access the code for both classification and clustering tasks.
3. Run the provided code to analyze the Internet traffic data.
4. Ensure that you have PySpark installed in your environment to execute the code.

Contribution Guidelines
Contributions to this project are welcome! If you have any ideas for improvements, additional analyses, or bug fixes, feel free to open an issue or submit a pull request.
