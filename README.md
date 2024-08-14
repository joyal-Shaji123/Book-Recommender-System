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
   git clone https://github.com/your-username/Book-Recommender-System.git
