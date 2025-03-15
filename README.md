# PipelineCrafter

## Overview
PipelineCrafter is a Kubeflow-based automated pipeline for digit recognition. It streamlines model deployment, evaluation, and scaling. The project initially focuses on digit recognition but will be extended to support any ML model with automated pipeline generation.

## Features
- **Digit Recognition Pipeline**: Uses a trained model to classify handwritten digits.
- **Kubeflow Integration**: Deploys the model in a Kubeflow pipeline for scalability.
- **Automated Pipeline Creation**: Future updates will allow any ML model to be deployed with minimal configuration.
- **Modular Design**: Supports flexible model swapping and pipeline customization.
- **Cloud & On-Prem Deployment**: Runs on Kubernetes clusters in cloud or local environments.

## Installation
### Prerequisites
- Kubernetes Cluster
- Kubeflow Installed ([Kubeflow Setup](https://www.kubeflow.org/docs/started/))
- Python 3.8+
- Pipenv or virtualenv (optional for dependency management)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Kash1shTyagi/PipelineCrafter.git
   cd autoflowml
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Deploy the Kubeflow pipeline:
   ```bash
   python deploy_pipeline.py
   ```

## Usage
- Upload a dataset for digit recognition.
- Run the Kubeflow pipeline to train and evaluate the model.
- Access the model predictions via API or dashboard.
- Modify configuration files to deploy different models.

## Future Enhancements
- **Model-Agnostic Pipelines**: Extend support for any ML model.
- **AutoML Features**: Enable hyperparameter tuning and model selection.
- **Web UI Dashboard**: Provide a user-friendly interface for monitoring pipelines.
- **Integration with Cloud Services**: Enable deployment on AWS, GCP, and Azure.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for discussions.
