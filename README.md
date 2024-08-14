# Book Recommender System

## Description

The Book Recommender System is a web application designed to suggest books based on user preferences. The project involves both popularity-based and collaborative-based filtering techniques to recommend books. 

### Features

- **Popularity-Based Recommendation**: On the homepage, the system displays the top 50 books based on user ratings. Only ratings from top users (those who rated more than 200 books) are considered, ensuring that recommendations are based on high-quality user input.
- **Collaborative-Based Filtering**: On the recommendation page, users can enter a book name to receive top 5 recommended books. This feature uses collaborative filtering to suggest books similar to the entered book.

### Technologies Used

- **Backend**: Flask API
- **Frontend**: HTML, Bootstrap
- **Data Processing**: Python, Pandas, Numpy, Scikit-learn
- **Development Environments**: Jupyter Notebook, PyCharm

## Installation

1. Clone the repository:
   ```bash
   [git clone https://github.com/joyal-Shaji123/Book-Recommender-System.git

2. Navigate to the project directory:
   cd Book-Recommender-System

3. Create and activate a virtual environment:
   python -m venv venv
   source venv/bin/activate

4. Run the application:
   python app.py

5. Open a browser and go to http://127.0.0.1:5000 to view the application.

Usage
Homepage: View the top 50 books based on ratings from users who have rated more than 200 books.
Recommend Page: Enter a book name to receive recommendations for the top 5 similar books based on collaborative filtering.

Contributing
Fork the repository
Create a new branch (git checkout -b feature-branch)
Make your changes
Commit your changes (git commit -am 'Add new feature')
Push to the branch (git push origin feature-branch)
Create a new Pull Request

Acknowledgments
Bootstrap for the front-end framework.
Flask for the backend framework.
Pandas for data manipulation.
Scikit-learn for machine learning algorithms.
