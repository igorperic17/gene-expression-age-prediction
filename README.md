# Age Prediction Model based on Gene Expression Data

This repository contains the code and resources for building an age prediction model using gene expression data derived from The Cancer Genome Atlas (TCGA) database. The model primarily utilizes XGBoost, a powerful machine learning algorithm, to predict the age of individuals based on their gene expression profiles.

## Dataset

The dataset used in this project is constructed from The Cancer Genome Atlas (TCGA) database. It consists of gene expression data from various cancer types and includes age information for each sample. The dataset is preprocessed and formatted to be compatible with the age prediction model.

## Setup Instructions

Follow these steps to set up and run the age prediction model on your local machine:

1. **Clone the Repository**: Begin by cloning this repository to your local machine using the following command:

git clone https://github.com/your-username/age-prediction-gene-expression.git

2. **Install Dependencies**: Navigate to the project directory and install the required dependencies using the following command:

pip install -r requirements.txt

3. **Download the Dataset**: Obtain the gene expression dataset from The Cancer Genome Atlas (TCGA) database and save it in the `data` directory.

4. **Preprocessing**: Preprocess the gene expression dataset to extract relevant features and prepare the data for model training. The preprocessing steps and code are provided in the `preprocessing.ipynb` notebook.

5. **Training the Model**: Run the `train_model.ipynb` notebook to train the age prediction model using XGBoost. Adjust the hyperparameters and experiment with different configurations to optimize model performance.

6. **Model Evaluation**: Evaluate the trained model's performance using appropriate evaluation metrics and visualizations. The `evaluation.ipynb` notebook contains the necessary code for model evaluation.

7. **Predicting Age**: Use the trained model to predict the age of new samples or test data. The `prediction.ipynb` notebook demonstrates how to make age predictions using the trained model.

## Contributing

Contributions to this project are welcome. Feel free to open issues for bug reports or feature requests. If you'd like to contribute code, please fork the repository and create a pull request with your proposed changes.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

We would like to acknowledge The Cancer Genome Atlas (TCGA) project for providing the gene expression data used in this project. We are grateful to the open-source community for the tools and libraries that facilitated this research.

## Contact

For any questions or inquiries, please contact Igor Peric at [igorperic@live.com](mailto:igorperic@live.com).

Enjoy exploring the age prediction model based on gene expression data!
