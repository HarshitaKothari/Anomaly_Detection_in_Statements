# Anomaly Detection in Statements

This project aims to detect anomalies in a set of statements using a combination of keyword extraction and cosine similarity.

## Table of Contents
- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Description
This project is designed to identify anomalies within a set of statements. The detection process involves:
1. **Keyword Extraction**: Extracting significant keywords from each statement.
2. **Vector Encoding**: Encoding the statements into numerical vectors.
3. **Cosine Similarity Calculation**: Calculating the cosine similarity between statement vectors.
4. **Anomaly Identification**: Identifying pairs of statements with similarities that fall within a specific threshold range, indicating potential anomalies.

The project utilizes natural language processing (NLP) techniques and machine learning models to perform these tasks effectively.

## Installation
To run this project locally, you will need to install the required dependencies. Use the following commands:

1. Clone the repository:
    ```bash
    git clone https://github.com/HarshitaKothari/Anomaly_Detection_in_Statements.git
    cd your-repository
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
To use the anomaly detection system, follow these steps:

1. Ensure you have installed all the required dependencies as mentioned in the [Installation](#installation) section.
2. Open the `Anomaly_Detection.ipynb` notebook in Jupyter Notebook, Jupyter Lab, or Google Colab.
3. Execute the cells in the notebook sequentially to process the statements and detect anomalies.

### Example
Here's an example of how to run the notebook:

1. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Navigate to the directory containing `Anomaly_Detection.ipynb` and open it.
3. Run all the cells in the notebook to see the anomaly detection process in action.

## Results
The output of the anomaly detection process includes:
- The total number of detected anomalies.
- Detailed information about the pairs of statements identified as potential anomalies, including their similarity scores.

Example output:

Potential anomaly detected with similarity 0.35 between:
Statement 1: "The house owned by Shivam will be bought by Jainil on 20th December, 2024"
Statement 2: "The house owned by Shivam is only 150 sqft"

Number of anomalies: 1
Anomaly detection completed successfully!


## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, please open an issue or submit a pull request. Ensure your contributions adhere to the project's coding standards and include appropriate tests.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
