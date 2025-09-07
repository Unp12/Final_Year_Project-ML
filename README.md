# Final_Year_Project-ML

# A Two-Fold Machine Learning Approach to Prevent and Detect IoT Botnet Attacks

This project proposes and implements a two-fold machine learning approach to effectively prevent and detect botnet attacks on IoT devices. The system analyzes network traffic data to identify and classify malicious activities, providing a robust defense mechanism for interconnected devices.

## 🌟 Key Features

-   **Botnet Detection:** Utilizes machine learning models to detect botnet traffic.
-   **Prediction and Classification:** Classifies network traffic as either benign or malicious.
-   **Data Analysis:** Performs correlation analysis on network parameters to identify key features for detection.
-   **User-Friendly Interface:** Provides a web-based dashboard for viewing detection results, user profiles, and training data.
-   **User Management:** Supports user registration, login, and profile management.
-   **Dynamic Visualization:** Displays model accuracy and detection ratios using graphical representations like bar charts.

## 🛠️ Technologies & Libraries

This project is built using a combination of Python for the backend and data science, and web technologies for the frontend interface.

### Backend & Machine Learning
-   **Python:** The core programming language for the project logic.
-   **Django:** A high-level Python web framework used to build the server-side application.
-   **Scikit-learn:** A machine learning library for implementing classification models.
-   **NumPy:** A fundamental package for numerical computations in Python.
-   **Pandas:** A library for data manipulation and analysis.
-   **Matplotlib & Seaborn:** Used for data visualization, particularly for the correlation matrix and accuracy plots.
-   **MySQL:** The relational database used to store and manage user data and other project-related information.

### Frontend
-   **HTML:** The standard markup language for the web pages.
-   **CSS:** For styling the user interface.
  

## 📊 Project Workflow

1.  **Data Preprocessing:** Network traffic data is loaded and cleaned.
2.  **Correlation Analysis:** A correlation matrix is generated to understand the relationships between different features like `Sender_Port`, `Target_Port`, and `Duration`. 3.  **Model Training:** A machine learning model (e.g., SVM as shown in the screenshots) is trained on a labeled dataset to learn patterns associated with botnet attacks.
4.  **Prediction:** The trained model is used to predict whether new, unseen network traffic is malicious.
5.  **User Interface:** A web dashboard is used to present the results, allowing users to interact with the system and view predictions in real-time.

## 🚀 Getting Started

### Prerequisites
-   Python 3.x
-   MySQL Server
-   pip (Python package installer)

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Unp12/Task_Mangement_Dashboard.git](https://github.com/Unp12/Task_Mangement_Dashboard.git)
    cd Task_Mangement_Dashboard
    ```

2.  **Install Python dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    (Note: You might need to create a `requirements.txt` file by running `pip freeze > requirements.txt` if one doesn't exist).

3.  **Database Setup:**
    -   Create a new database in your MySQL server.
    -   Update the database connection settings in the Django settings file.

4.  **Run Migrations:**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5.  **Run the Django server:**
    ```bash
    python manage.py runserver
    ```
    The application will be available at `http://127.0.0.1:8000`.

## 📸 Screenshots

 Register Page <img width="1920" height="1080" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/9e7759ba-250c-4048-bd5b-38a00f751897" />

 Login Page 
 <img width="1920" height="988" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/8ced0dfe-4681-4246-b774-9ba8fd0ad016" />

Botnet Detection Detail <img width="1920" height="1000" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/dd75ed2e-b8a3-4103-9d3f-4d91038af56e" />

<img width="1920" height="1021" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/915420b8-7978-442f-99f8-458fb6ab2e7c" />


User Profile View <img width="1920" height="929" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/57fd52e7-34eb-456c-bd27-c2a9b20b9e33" />


## 🎓 Final Year Project

This project was developed as a final year submission to demonstrate a practical application of machine learning in cybersecurity, specifically targeting the growing threat of IoT botnets.

---

### Author

-   Ullam Naga Poojith - Team Leader
-   ullamnagapoojith222@gmail.com
-   www.linkedin.com/in/nagapoojith-ullam-b215b6243  inkedIn Profile
