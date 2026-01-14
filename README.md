# Medico: Specialized Medicine Guidance & Blood Bank Assistance

**Medico** is a specialized digital healthcare platform designed to provide comprehensive medicine guidance and blood bank assistance. [cite_start]It leverages machine learning to offer personalized health insights and streamlines the process of finding blood donors and banks[cite: 1915, 1931].

## 🚀 Features

### 1. AI-Powered Medicine Guidance
* [cite_start]**Symptom Analysis:** Users can input symptoms (e.g., headache, fever) to receive a predicted disease diagnosis using a Random Forest algorithm[cite: 1932, 2039].
* [cite_start]**Drug Recommendations:** Based on the predicted condition, the system suggests suitable medications with dosage and safety precautions[cite: 1917, 2134].
* [cite_start]**Doctor Recommendations:** Suggests specialized doctors for the diagnosed condition with links to book appointments[cite: 2135].

### 2. Blood Bank Assistance
* [cite_start]**Real-Time Availability:** A dashboard displaying current stock levels for all blood groups (A+, B+, O-, etc.)[cite: 1934, 1946].
* [cite_start]**Nearby Blood Banks:** Locates nearby blood banks using Google Maps integration[cite: 2159].
* [cite_start]**Donor Connection:** Features to "Request Blood" in emergencies or "Donate Blood" to schedule an appointment[cite: 2152, 2153].
* **Compatibility Chart:** A visual guide on blood donation compatibility (Who can donate to whom).

### 3. Personal Health Dashboard
* [cite_start]**Health Risk Analysis:** Assesses cardiovascular and metabolic health risks[cite: 2055].
* [cite_start]**Profile Management:** Stores user health profiles for personalized insights[cite: 2058].

## 🛠️ Tech Stack

* [cite_start]**Frontend:** HTML, CSS, JavaScript, Tailwind CSS[cite: 2041].
* [cite_start]**Backend:** Python (Flask)[cite: 2038].
* [cite_start]**Machine Learning:** Scikit-learn (Random Forest Classifier), Pandas[cite: 2039].
* [cite_start]**Database:** SQLite[cite: 2040].
* [cite_start]**Tools:** VS Code, Git, GitHub[cite: 2043].

## 📸 Screenshots

### Landing Page & Dashboard
![Landing Page](screenshots/main_landing_page.png)
*The main dashboard offering quick access to health profiles and services.*

### Medicine Recommendation System
![Symptom Input](screenshots/entering_symptoms.png)
*Users enter symptoms to get immediate health insights.*

![Disease Prediction](screenshots/display_disease.png)
*The system predicts the disease and suggests medications.*

### Blood Bank Assistance
![Blood Bank Dashboard](screenshots/bloodbank_dashboard.png)
*Real-time tracking of blood availability across different groups.*

![Nearby Blood Banks](screenshots/blood_nearby_hospital.png)
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
* [cite_start]**Disease Symptoms:** Mapping symptoms to specific diseases[cite: 2095].
* [cite_start]**Drugs:** Recommended medications for various conditions[cite: 2097].
* [cite_start]**Doctors:** Specialist information for referrals[cite: 2098].

## 👥 Contributors

* [cite_start]**Dhanush B K** - [GitHub Profile](https://github.com/dbk2002)[cite: 1845].
* [cite_start]**Kusum Pakira**[cite: 1847].
* [cite_start]**Purushotham V Mitti**[cite: 1849].

---
*Developed at K.S. [cite_start]Institute of Technology, Bengaluru (Dept. of Computer Science & Design)[cite: 1858, 1859].*
