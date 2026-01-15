# 🎓 Aether Institute Data Portal

A powerful **console-based student registration & analytics system** built in Python.  

It combines user-friendly registration with smart program recommendations, cohort management, public enrollment stats, and a full admin analytics dashboard featuring beautiful visualizations.

This program simulates how a real educational institute could register students, manage cohorts and analyze enrollment data using python and data science tools. 

This project includes **two modes**:

1. **Basic Version** - simple registration, program recommendation via rules and analytics

2. **Enhanced Version**: includes a machine learning based recommendation system 

## ✨ Key Features (basic version)

- **Smart registration** with data-driven program recommendations  
  (rule-based + similarity matching on historical student data)
- **Cohort scheduling** with automatic start/end date calculation
- **Public statistics view** — top programs, age distribution, commitment rates (visible to anyone)
- **Secure admin dashboard** with:
- Quick insights & detailed stats
- Three interactive visualizations (saved as PNG files):
    - Program enrollment distribution
    - Age distribution histogram
    - Commitment level by program
    - Export full database to CSV
    - Delete records with confirmation
    - Hashed admin password authentication (with attempt limit)
- Professional console UI with emojis, progress bars & clear formatting

- **Student Features**(both version)
- View available program and their description
- Register for a program with validation(email, age, duplicates)
- Get program recommendation based on:
   - coding experience 
   - commitment level
   - are of interest
- Select from upcoming cohort start dates
- Automatically generated registration ID
- Login in to view personal profile details 

- **Recommendation System** (basic version)
- Rule-based recommendation logic
- Suggests the most suitable program based on:
- Skill level
- Interest area
- Learning commitment

- **Enhanced Version**: ML-based recommendations using a Decision Tree Classifier trained on existing students

- Only triggered when enough data exists (≥5 students)

- Provides personalized program suggestions

ML is optional: Not needed for small datasets; rule-based recommendations are sufficient

## 🛠️ Tech Stack

- Python 3.10+
- pandas — Data manipulation & analysis
- matplotlib & seaborn — High-quality data visualizations
- hashlib — Secure password hashing
- datetime — cohort scheduling and duration tracking
- scikit-learn — decision tree machine learning recommendation (enhanced version)

## 📸 Screenshots

### Main Menu & Registration Flow
![Registration](images/Screenshot%20(registration).png)

### Program Recommendation in Action
![Recommendation](images/Screenshot%20(recommendation).png)

### Public Enrollment Statistics
![Public Statistics](images/Screenshot%20(enrollment%20statistics).png)

### Admin Analytics Dashboard
![Admin Dashboard](images/Screenshot%20(admin%20dashboard).png)

### Generated Visualizations

**Program Distribution**  
![Program Popularity](images/Screenshot%20(program%20distribution).png)

**Age Distribution**  
![Age Distribution](images/Screenshot%20(age%20distribution).png)

**Commitment Level by Program**  
![Commitment by Program](images/Screenshot%20(commitment%20level).png)
## 🚀 How to Run

1. Clone the repository
   git clone https://github.com/EmmanuellaSalami/Aether-Student-Registration-Analytics-Portal.git
cd Aether-Student-Registration-Analytics-Portal

2. Install dependencies 
   pip install -r requirements.txt

3. Run the Program 

Notes About Machine Learning

- ML is optional and only useful when the dataset grows large
- With small datasets, rule-based recommendations are sufficient
- ML model trains on:
  - Age
  - Commitment level
  - Produces personalized program recommendations
- to experience the ML recommendation: Register 5+ students first — the system will automatically switch to data-driven suggestions.

What This Project Demonstrates

End-to-end application development (user flows + data persistence)
Building data-driven features using pandas (similarity-based recommendations)
Creating meaningful insights & professional visualizations
Secure authentication & input validation in console apps
Clean, maintainable code structure with good documentation

License

MIT License – free and open-source

Author
Emmanuella Salami
Aspiring Data Scientist and Software Developer
Location: Lagos, Nigeria
LinkedIn: [https://www.linkedin.com/in/emmanuellasalami]
Email: [emmanuellasalami2007@gmail.com]
GitHub: @EmmanuellaSalami


Feel free to fork, star ⭐ or reach out if you'd like to collaborate!
