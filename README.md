# Course Recommendation System

This project is a course recommendation system built using Python and various machine learning techniques. The system takes a dataset of course descriptions and recommends similar courses based on the content similarity.

## Dataset

The dataset used in this project is the 'Coursera.csv' file, which contains information about various courses offered on the Coursera platform. The dataset includes columns such as 'Course Name', 'Difficulty Level', 'Course Description', and 'Skills'.

## Approach

The recommendation system is based on the following steps:

1. **Data Preprocessing**: The text data in the dataset is cleaned and preprocessed to remove unnecessary characters, convert to lowercase, and perform stemming.

2. **Text Vectorization**: The preprocessed text data is converted into numerical vectors using the CountVectorizer from the scikit-learn library.

3. **Similarity Calculation**: The cosine similarity between the vectorized course descriptions is calculated to measure the similarity between courses.

4. **Recommendation**: Given a course name, the system finds the most similar courses based on the cosine similarity scores and recommends the top-ranked courses.

## Dependencies

The following Python libraries are required to run the project:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- NLTK

## Usage

1. Clone the repository or download the project files.
2. Install the required dependencies by running `pip install -r requirements.txt` (if you have a `requirements.txt` file).
3. Place the 'Coursera.csv' dataset file in the 'Dataset' directory.
4. Run the 'recommendation.ipynb' notebook to preprocess the data, train the recommendation system, and get course recommendations.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).