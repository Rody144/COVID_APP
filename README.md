
# COVID-19 Classification Application 🦠

This is a Streamlit-based web application that uses a deep learning model to classify chest X-ray images into three categories:
- **Covid**: Indicating a positive Covid-19 case.
- **Normal**: Indicating a healthy individual.
- **Viral Pneumonia**: Indicating pneumonia caused by viruses other than Covid-19.

## Features
- Upload chest X-ray images in `jpg`, `png`, or `jpeg` format.
- Predict the class of the uploaded image using a pre-trained deep learning model.
- User-friendly interface with tabs for navigation:
  - **Home**: Upload and classify images.
  - **About Model**: Learn about the model architecture, training details, and limitations.
  - **Contact**: Get in touch with the developers.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/covid19-classification-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd COVID_APP
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the application:
   ```bash
   streamlit run covid_app.py
   ```
2. Open the application in your browser at `http://localhost:8501`.

## Model Details
- **Architecture**: Convolutional Neural Network (CNN)
- **Dataset**: [Kaggle COVID-19 Image Dataset](https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset)
- **Accuracy**: Achieved 95% accuracy on the validation set.

## Limitations
- The model's performance depends on the quality and diversity of the training data.
- It may not generalize well to images from different sources or with varying image qualities.

## Contact
For any inquiries or support, please reach out:
- **Email**: [raghadehabkafafy@gmail.com](mailto:raghadehabkafafy@gmail.com)
- **LinkedIn**: [raghadehab](https://www.linkedin.com/in/raghad-ehab-5a079b336/)
- **GitHub**: [Rody144](https://github.com/Rody144)

## License
This project is licensed under the MIT License.
i used covid19_model.h5 i have trained it!
```
