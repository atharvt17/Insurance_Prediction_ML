```markdown
# Health Insurance Cost Prediction

This is a web application that predicts health insurance costs based on various factors such as age, sex, BMI, number of children, smoking habits, and region. It utilizes a machine learning model trained on the provided dataset to make accurate predictions.

## How to Use

1. Visit the web application by clicking on the following link: [Health Insurance Cost Prediction](https://healthinsurancepred.streamlit.app/).

2. Once on the web application, you will see a user interface where you can enter the necessary information for the prediction.

3. Fill in the required fields:
   - **Age:** Slide the bar to select your age.
   - **Sex:** Choose your gender from the dropdown menu.
   - **BMI Value:** Enter your Body Mass Index (BMI) value.
   - **Number of Children:** Slide the bar to select the number of children you have.
   - **Smoker:** Select "Yes" if you are a smoker; otherwise, select "No."
   - **Region:** Choose your region from the dropdown menu.

4. After entering the information, click on the "Predict" button.

5. The application will process your input and display the predicted insurance amount based on the provided data.

## Dataset and Model

The web application utilizes the "insurance.csv" dataset, which is located in the "dataset" folder. This dataset contains information about individuals' health insurance costs.

The machine learning model used for the prediction is stored in the "insurance_pred" file, located in the "ML Model" folder. This model has been trained on the provided dataset and is responsible for generating accurate predictions based on the input data.

## Prerequisites

To run this web application locally, you need to have the following dependencies installed:

- joblib==1.2.0
- streamlit==1.23.1
- scikit-learn
- pillow

You can install these dependencies by running the following command:

```bash
pip install -r requirements.txt
```

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to explore the code and modify it according to your needs. If you encounter any issues or have suggestions for improvement, please create an issue on the repository.

```

In the "Dataset and Model" section, make sure to mention the specific file names and their locations in the folders.

Remember to update the "Prerequisites" section with the correct dependency versions and include the `requirements.txt` file if necessary.
