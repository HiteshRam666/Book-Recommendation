# 📚 Book Recommendation System

Welcome to the Book Recommendation System! This project uses machine learning techniques to recommend books based on user preferences.

## 📁 Project Structure

- **book_recommendation.ipynb**: The main Jupyter notebook containing the code for loading the dataset, preprocessing, model building, and generating recommendations.

## 🔧 Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/book-recommendation-system.git
    cd book-recommendation-system
    ```
    
## 🚀 Usage

1. Open the Jupyter notebook:
    ```bash
    jupyter notebook Book_Recommendation.ipynb
    ```

2. Run all the cells to load the data, preprocess it, and generate book recommendations.

## 📊 Data
Click here to download data - https://statso.io/book-recommendations-case-study/

The dataset used in this project contains the following columns:
- `bookID`: Unique identifier for each book
- `title`: The title of the book
- `authors`: The authors of the book
- `average_rating`: The average rating of the book

## 🛠️ Methodology

1. **Data Loading**: Load the dataset using Pandas.
2. **Preprocessing**: Clean and preprocess the data for analysis.
3. **Vectorization**: Use TF-IDF vectorizer to convert text data into numerical data.
4. **Similarity Calculation**: Calculate the cosine similarity between book descriptions.
5. **Recommendation**: Recommend books based on similarity scores.

## 📈 Results

The system recommends books with similar content based on the book title input by the user.

## 🤝 Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any improvements.
