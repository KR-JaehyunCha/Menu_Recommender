# Menu_Recommender

## Project Overview
This project aims to develop a machine learning model that suggests recipes based on the ingredients provided by the user. By leveraging a large dataset of over 2 million recipes, the model will analyze ingredient lists and recommend the most relevant recipes.

## Dataset
- **Name**: Recipe Dataset (over 2M) Food  
- **Source**: [Kaggle - Recipe Dataset (over 2M) Food](https://www.kaggle.com/datasets/wilmerarltstrmberg/recipe-dataset-over-2m)  
- **Description**: This dataset contains over 2 million recipes with ingredients, cooking instructions, and other details.

## Project Goals
- Implement a content-based recommendation system using machine learning techniques.  
- Develop a TF-IDF vectorizer to process ingredient lists.  
- Use cosine similarity to recommend recipes based on user-provided ingredients.  
- Output the top 5 recommended recipes.

## Features
- **Ingredient-based search**: Input available ingredients to get relevant recipes.  
- **Simple interface**: Command-line interaction for quick recommendations.  
- **Scalable**: Can handle a large dataset efficiently.

## Technologies Used
- **Python**  
- **Libraries**:  
  - `pandas` – Data manipulation and analysis  
  - `scikit-learn` – Machine learning algorithms  
  - `TfidfVectorizer` – Text processing and vectorization  
  - `cosine_similarity` – Similarity measurement  

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   ```
2. **Install Required Libraries**:
   ```bash
   pip install pandas scikit-learn
   ```
3. **Run the Program**:
   ```bash
   python recommend.py
   ```
4. **Input Ingredients**:
   - Enter ingredients separated by commas (e.g., "eggs, cheese, milk").  
5. **Get Recipe Recommendations**:
   - The program will display the top 5 recipes that match the input ingredients.

## Future Improvements
- Add filtering options based on calories, preparation time, and difficulty.  
- Implement a GUI for better user interaction.  
- Expand the model to suggest ingredient substitutions.

## Contributions
Feel free to contribute by submitting pull requests or opening issues to suggest improvements.

## License
This project is open-source and available under the [MIT License](LICENSE).

