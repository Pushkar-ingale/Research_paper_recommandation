Research Papers Recommendation and Subject Area Prediction App
This application is developed using Streamlit, TensorFlow, PyTorch, and Sentence Transformers to recommend research papers based on input paper titles and predict subject areas based on abstracts.

Description
This app combines two main functionalities:

Research Papers Recommendation: Given a paper title, the app recommends similar research papers based on pre-trained embeddings and a recommendation model.

Subject Area Prediction: Users can input the abstract of a research paper, and the app predicts the subject areas/categories using a deep learning model trained on abstract data.

How to Run
To run the application locally, follow these steps:

Clone the repository:

git clone <repository_url>
cd Research-Paper-Recommendation-System
Install the required dependencies. You can do this using pip:

pip install -r requirements.txt
Run the Streamlit app:

streamlit run app.py

Once the app is running, you can access it in your web browser at the provided URL.
Usage
Enter a paper title in the provided text input to get recommendations for similar papers.
Enter the abstract of a paper in the text area to predict its subject areas.
Files and Structure
app.py: Main Python script containing the Streamlit application code.
models/: Directory containing saved models and embeddings.
README.md: This file, providing an overview of the project.
requirements.txt: List of dependencies required to run the application.
Credits
This application was developed by Pushkar Ingale.
It utilizes pre-trained models and libraries from TensorFlow, PyTorch, and Sentence Transformers.
