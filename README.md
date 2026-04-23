# project-green-vision
This is a machine learning project, help us to identify the type of tree based on different physical and environmental features  e.g., elevation, soil type, distance from hydrology, sunlight density etc. This project can be used to integrate with the wildfire risk prediction, Biodiversity and Wildlife Management, and Environmental monitoring.

# Objectives
1. Build an end to end machine learning pipeline.
2. Deploy the model using REST API.
3. Monitor the model performance.
4. Enable reproducability environment and dependency management.

# Tech Stack
1. Programming Language: Python
2. Framework: FastAPI
3. Machine Learning: Scikit-learn, XGBoost
4. Data Processing: Pandas, NumPy
5. Model Monitoring: Evidently
6. API Server: Uvicorn
7. Database: MongoDB
8. Cloud Integration: AWS (Boto3)
9. Environment Management: Conda / Virtual Environment

# Installation and Setup
1. Clone the repository:
   git clone https://github.com/kaifahmad2000/project-green-vision.git
   cd project-green-vision
2. Create environment:
   conda create -n green_env python=3.8 -y
   conda activate green_env
3. Install Dependencies:
   pip install -r requirements.txt

# Running the application
- Start FASTAPI server:
  uvicorn app:app --reload
- Access API:
  Swagger UI: http://127.0.0.1:8000/docs
  ReDoc: http://127.0.0.1:8000/redoc

# Features
1. End-to-end ML pipeline.
2. REST API for predictions.
3. Model performance tracking.
4. Data drift detection.
5. Cloud integration support.

# Model Monitoring
This project uses Evidently to:
1. Detect data drift.
2. Track model performance.
3. Generate monitoring reports.

# Environment Variables
Create a .env file and configure:
- MONGO_URI=your_mongodb_connection
- AWS_ACCESS_KEY=your_key
- AWS_SECRET_KEY=your_secret

# Future Improvements
1. Add CI/CD pipeline.
2. Deploy on cloud (AWS/GCP/Azure).
3. Add frontend dashboard.
4. Improve model accuracy and scalability.

