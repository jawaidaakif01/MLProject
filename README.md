# 📊 Student Exam Performance Prediction

An end-to-End Machine Learning project that predicts student exam scores based on demographics, study habits, and parental education. This project includes a complete pipeline from Data Ingestion to Deployment using Docker.

## 🛠️ Tech Stack
* **Language:** Python 3.10
* **Framework:** Flask
* **Machine Learning:** Scikit-Learn, CatBoost, XGBoost
* **Deployment:** Docker
* **Frontend:** HTML/CSS

## 🐳 How to Run with Docker (Recommended)

If you have Docker installed, you can run the app with just a few commands:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/jawaidaakif01/AWS-CI-CD-Projects.git](https://github.com/jawaidaakif01/AWS-CI-CD-Projects.git)
    ```

2.  **Build the Docker Image**
    ```bash
    docker build -t studentperformance .
    ```

3.  **Run the Container**
    ```bash
    docker run -p 5000:5000 studentperformance
    ```

4.  **Access the App**
    Open your browser and go to: `http://localhost:5000`

## 🐍 How to Run Manually (Without Docker)

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/jawaidaakif01/AWS-CI-CD-Projects.git](https://github.com/jawaidaakif01/AWS-CI-CD-Projects.git)
    ```

2.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the App**
    ```bash
    python app.py
    ```