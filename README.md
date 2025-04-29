# Book-Recommender-System
This is a machine learning-based Book Recommendation System built with Python and Flask, providing personalized book suggestions based on popularity and similarity. The system uses pre-trained models and a clean web interface to recommend books to users effectively.

🚀 Features
🔥 Popular Books Page
Displays a curated list of the most popular books based on rating counts and averages.

🤝 User-Based Recommendations
Recommends books similar to the ones users search for, based on a similarity matrix.

🧠 Pre-trained Models
popular.pkl: Pre-processed popular books data
pt.pkl: Pivot table of user-book ratings
similarity_scores.pkl: Cosine similarity matrix for recommendations

🌐 Web Interface (Flask)
Simple UI using HTML templates to display search results and recommendations.

📁 Project Structure
perl
Copy
Edit
book-recommender-system/
│
├── app.py                        # Main Flask application
├── book-recommender-system.ipynb # Jupyter notebook for data processing
├── popular.pkl                   # Pickle file of popular books
├── pt.pkl                        # Pivot table for ratings
├── similarity_scores.pkl         # Similarity matrix
├── templates/
│   ├── home.html                 # Homepage
│   └── recommend.html            # Recommendations page
├── requirements.txt              # Python dependencies
└── Procfile                      # For deployment (e.g., Heroku)
⚙️ How to Run
Install requirements:
bash
Copy
Edit
pip install -r requirements.txt
Run the app:
bash
Copy
Edit
python app.py
Open in browser:
Visit http://127.0.0.1:5000

✅ Example
Enter a book name like "The Hobbit" and get similar recommendations such as:
The Lord of the Rings
Eragon
Harry Potter Series
