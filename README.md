# Medicine-recommendation-system
An AI-based Medicine Recommendation System built with Flask and Machine Learning (SVC) that predicts diseases from user-input symptoms and provides personalized medication, diet, workout, and precaution suggestions.
Features: 1 Predicts diseases using a Support Vector Classifier (SVC) model.
          2. Recommends medications, diets, precautions, and workouts for each disease.
         3.Built with Flask for an interactive web interface.
         4.Integrated multiple datasets for comprehensive health insights.
         5. Real-time predictions within seconds.

🧩 Tech Stack:1 Python 3.x
              2.Flask
              3.scikit-learn
              4.NumPy, Pandas
              5.HTML, CSS, Jinja2 Templates
              6.Pickle (for model loading)

📁 Project Structure
medicine-recommendation-system/
│
├── datasets/
│   ├── symptoms_df.csv
│   ├── precautions_df.csv
│   ├── workout_df.csv
│   ├── description.csv
│   ├── medications.csv
│   └── diets.csv
│
├── models/
│   └── svc.pkl
│
├── templates/
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   ├── developer.html
│   └── blog.html
│
├── static/          # CSS, JS, and images (optional)
│
├── app.py           # Main Flask application file
└── README.md

