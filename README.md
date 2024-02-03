# AI Smoke Detection IoT Project

## Overview

This project utilizes machine learning techniques, specifically the Random Forest Classifier, to detect the presence of smoke in an IoT environment. The dataset used for training and testing is `smokedetectioniot.csv`. The goal is to create an intelligent system capable of accurately identifying smoke and raising alarms in IoT settings.

## Table of Contents

- [Dataset](#dataset)
- [Random Forest Classifier](#random-forest-classifier)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Dataset

The dataset (`smokedetectioniot.csv`) contains information collected from IoT devices in a controlled environment. It includes features related to temperature, humidity, gas levels, and smoke presence. The dataset is split into training and testing sets for model development and evaluation.

## Random Forest Classifier

The Random Forest Classifier is employed for its ability to handle complex datasets and provide robust predictions. The model is trained using the training dataset and evaluated on the testing dataset to ensure its effectiveness in smoke detection.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ai-smoke-detection-iot.git
   ```

2. Change directory:

   ```bash
   cd ai-smoke-detection-iot
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Ensure the dataset (`smokedetectioniot.csv`) is available in the project directory.

2. Run the Jupyter Notebook (`smoke_detection.ipynb`) to train the Random Forest Classifier and evaluate its performance.

## Results

Summarize the results obtained from the Random Forest Classifier. Include metrics such as accuracy, precision, recall, and F1 score. Provide insights into the model's performance and any notable findings from the analysis.

## Contributing

Contributions are welcome! If you find issues, want to propose improvements, or add new features, please open an issue or submit a pull request following our [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE). See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thank the creators of the dataset for providing valuable data.
- Acknowledge any libraries or frameworks used in the project.
