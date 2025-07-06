# Traffic Collision Analysis

This project focuses on analyzing traffic collision data in Queens, New York. Integrating various data sources, and applying big data processing techniques to derive insights. The primary goal is to preprocess, merge, and analyze collision, weather, and traffic data to identify patterns and potential contributing factors to traffic incidents.

## Project Structure

This repository contains several Jupyter notebooks and a dataset, each serving a specific purpose in the data analysis pipeline:

*   `dataset.csv`: The primary dataset containing raw collision information.
*   `preprocessing_collisions_data.ipynb`: Notebook for cleaning and preprocessing the collision dataset.
*   `Weather_Preprocessing.ipynb`: Notebook dedicated to preprocessing weather-related data that will be integrated with the collision data.
*   `preprocessing_traffic_data.ipynb`: Notebook for preprocessing traffic flow data.
*   `Merge_data (2).ipynb`: Notebook for merging the preprocessed collision, weather, and traffic datasets.
*   `Feature_Engineering_+_Merging_(part_2) (1).ipynb`: This notebook likely continues the data merging process and focuses on creating new features from the combined dataset.
*   `Spark_Training.ipynb`: A Jupyter notebook demonstrating the use of Apache Spark for big data processing, likely for scalable data analysis or machine learning tasks.
*   `Paper_p2.pdf`: A research paper or document related to the project, possibly detailing methodologies, findings, or background information.

## Getting Started

To set up and run this project, follow these steps:

### Prerequisites

*   Python 3.x
*   Jupyter Notebook
*   Apache Spark (for `Spark_Training.ipynb`)
*   Required Python libraries (e.g., pandas, numpy, pyspark, etc.)

### Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/AAA2026/Traffic-Collision-Analysis-in-Queens.git
    cd Traffic-Collision-Analysis-in-Queens
    ```

2.  Install the necessary Python packages:

    ```bash
    pip install pandas numpy pyspark jupyter
    ```
    (Note: This is a general list; specific requirements might vary based on the notebooks' actual content.)

### Usage

1.  Start Jupyter Notebook:

    ```bash
    jupyter notebook
    ```

2.  Open the `.ipynb` files in your browser and run the cells sequentially to execute the data preprocessing, merging, feature engineering, and Spark-based analysis steps.
---------------------------------------------------------------------------------------------
Contributions are welcome! Please feel free to open issues or submit pull requests.
For any questions or inquiries, please contact [abdalaalaa17@gmail.com].



