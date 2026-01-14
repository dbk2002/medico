# Medico: Specialized Medicine Guidance & Blood Bank Assistance

**Medico** is a specialized digital healthcare platform designed to provide comprehensive medicine guidance and blood bank assistance. It leverages machine learning to offer personalized health insights and streamlines the process of finding blood donors and banks.

![Logo](static/images/new_medico.png)

## 🚀 Features

### 1. AI-Powered Medicine Guidance
* **Symptom Analysis**: Users can input symptoms (e.g., headache, fever) to receive a predicted disease diagnosis using a Random Forest algorithm.
* **Drug Recommendations**: Based on the predicted condition, the system suggests suitable medications with dosage and safety precautions.
* **Doctor Recommendations**: Suggests specialized doctors for the diagnosed condition with links to book appointments.

### 2. Blood Bank Assistance
* **Real-Time Availability**: A dashboard displaying current stock levels for all blood groups (A+, B+, O-, etc.).
* **Nearby Blood Banks**: Locates nearby blood banks using Google Maps integration.
* **Donor Connection**: Features to "Request Blood" in emergencies or "Donate Blood" to schedule an appointment.
* **Compatibility Chart**: A visual guide on blood donation compatibility (Who can donate to whom).

### 3. Personal Health Dashboard
* **Health Risk Analysis**: Assesses cardiovascular and metabolic health risks.
* **Profile Management**: Stores user health profiles for personalized insights.

## 🛠️ Tech Stack

* **Frontend**: HTML, CSS, JavaScript, Tailwind CSS.
* **Backend**: Python (Flask).
* **Machine Learning**: Scikit-learn (Random Forest Classifier), Pandas.
* **Database**: SQLite.
* **Tools**: VS Code, Git, GitHub.

## 📸 Screenshots

### Landing Page & Dashboard
![Landing Page](screenshots/main%20landing%20page.png)
*The main dashboard offering quick access to health profiles and services.*

### Medicine Recommendation System
![Symptom Input](screenshots/entering%20symptoms.png)
*Users enter symptoms to get immediate health insights.*

![Disease Prediction](screenshots/display%20disease.png)
*The system predicts the disease and suggests medications.*

![Recommended Doctor](screenshots/practo%20link.png)
*The system suggests specialized doctors and provides direct links to book appointments via Practo.*

### Blood Bank Assistance
![Blood Bank Dashboard](screenshots/bloodbank%20dashboard.png)
*Real-time tracking of blood availability across different groups.*

![Nearby Blood Banks](screenshots/blood%20nearby%20hospital.png)
*Locator for nearby blood banks and donation centers.*

## ⚙️ Installation & Setup

1.  **Clone the Repository**
    ```bash
    git clone [https://github.com/yourusername/medico.git](https://github.com/yourusername/medico.git)
    cd medico
    ```

2.  **Create a Virtual Environment**
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3.  **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Application**
    ```bash
    python app.py
    ```

5.  **Access the App**
    Open your browser and go to `http://127.0.0.1:5000`

## 📊 Dataset Information

The model is trained on custom datasets covering:
* **Disease Symptoms**: Mapping symptoms to specific diseases.
* **Drugs**: Recommended medications for various conditions.
* **Doctors**: Specialist information for referrals.

## 👥 Contributors

* **Dhanush B K**
* **Kusum Pakira**
* **Purushotham V Mitti**

---
*Developed at K.S. Institute of Technology, Bengaluru (Dept. of Computer Science & Design).*
