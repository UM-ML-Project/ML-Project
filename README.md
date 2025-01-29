📊 **Income Prediction Web Tool**

A web application that predicts whether an individual’s annual income exceeds $50K based on census data.

📝 **Overview:**
The Income Prediction Web Tool is a machine-learning-based application that allows users to:
Predict income category (<=50K or >50K) based on user-provided census attributes.
Upload a CSV file with multiple records for batch prediction.
Select different models (e.g., Decision Tree, Random Forest, K-Nearest Neighbors, and Logistic Regression).
View results directly on the web portal.

📦 **Dataset:**
The dataset is based on the 1994 Census Income Dataset, originally extracted by Barry Becker.
It includes demographic and employment-related attributes such as: Age, Workclass, Education, Occupation, Race, Gender, and more.

⚡ **Features:**
✅ Interactive Web Interface built using Gradio.
✅ Multiple ML Models trained for prediction.
✅ Batch Processing for CSV file uploads.
✅ Deployed on Hugging Face Spaces.

🚀 **How to Use:**
Visit the Web Tool: Hugging Face Deployment
Enter Data Manually: Provide comma-separated values based on the required format.
Upload a CSV: Click on "Upload CSV File" to process multiple entries at once.
Select Model: Choose between different machine-learning models.
Submit & Get Predictions: Click the "Submit" button to generate results.

🛠️ **Installation (Local Setup)**
You can run this tool locally by following these steps:
1️⃣ Clone the Repository
git clone https://github.com/your-username/income-prediction.git
cd income-prediction
2️⃣ Install Dependencies
Ensure you have Python 3.7+ installed, then run:
pip install -r requirements.txt
3️⃣ Run the Web App
python app.py
The application will be available at http://127.0.0.1:7860.

📁 **File Structure:**
📂 income-prediction
├── 📄 app.py                       # Main application script
├── 📄 income-prediction.py          # ML model processing script
├── 📄 models.pkl                     # Trained ML models
├── 📄 logistic_regression_model.pkl  # Custom logistic regression model
├── 📄 README.md                      # Project documentation
├── 📄 requirements.txt              # Required dependencies
└── 📂 data/                         # Sample dataset (if applicable)

🤖 **Machine Learning Models:**
The following models were trained and integrated:
✅Decision Tree
✅Random Forest
✅K-Nearest Neighbors
✅Logistic Regression (Implemented from first principles)

🏗️ **Future Enhancements:**
📈 Improve model accuracy with additional feature engineering.
🌍 Deploy on cloud services for wider accessibility.
🎨 Enhance UI/UX for better user experience.

📜 **License:**
This project is open-source and available under the University of Malta License.

💡 **Acknowledgments:**
Data Source: UCI Machine Learning Repository
Thanks to Barry Becker for extracting the dataset.
🔗 Live Demo: Click here to try it; https://huggingface.co/spaces/UM-ML-Project/Income-prediction

👥 **Contributors:**
This project was developed as part of our ML coursework at the University of Malta by the following students:

Ikenna Sampson Onyenu	    ikenna.onyenu.23@um.edu.mt, 
Nicholas Falzon	          nicholas.falzon.21@um.edu.mt, 
Louis Liu renzhi	          renzhi.liu.24@um.edu.mt, and
Giuseppe Farrugia	        giuseppe.farrugia.14@um.edu.mt

Feel free to contact us if you have any questions or feedback! 🚀
