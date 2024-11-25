# Book Recommendation System

This project implements a collaborative filtering-based book recommendation system. The system uses user-item interactions (book ratings) to recommend books to users. It employs a similarity matrix to find books that are similar to each other and provides recommendations based on the user’s past ratings.

## Project Structure

- **Data**: The project uses three CSV files as input:
  - `books.csv`: Contains information about books such as title, author, ISBN, etc.
  - `users.csv`: Contains information about users, including user ID and name.
  - `ratings.csv`: Contains the ratings given by users to the books.

- **Main Steps**:
  1. Data Preprocessing
  2. Building a User-Book Matrix
  3. Collaborative Filtering using Cosine Similarity
  4. Evaluating the model using various metrics
  5. Saving the model using pickle

## Requirements

Before running the code, ensure you have the following Python libraries installed:

- pandas
- numpy
- scikit-learn
- matplotlib
- pickle

You can install them using pip:

```bash
pip install pandas numpy scikit-learn matplotlib
