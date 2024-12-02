
# Movie Recommendation System

A machine learning-based movie recommendation system that suggests movies to users based on their preferences or a selected movie. This project leverages natural language processing techniques and similarity measures to provide relevant recommendations.

## Features

- **Data Processing**: Handles and preprocesses movie datasets for feature extraction.
- **TF-IDF Vectorization**: Converts textual data into numerical format for similarity calculations.
- **Cosine Similarity**: Computes similarities between movies based on metadata such as genres, keywords, and descriptions.
- **Interactive Recommendation**: Allows users to select a movie and receive suggestions for similar movies.

## Dataset

The dataset used (`movies.csv`) contains information about:
- Movie titles
- Genres
- Overviews
- Cast and crew
- Release dates, budgets, and more.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - `numpy` and `pandas` for data manipulation
  - `sklearn` for machine learning tasks
  - `difflib` for string matching

## Getting Started

### Prerequisites
- Python 3.x
- Libraries listed in `requirements.txt`

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/movie-recommendation-system.git
   cd movie-recommendation-system
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook to explore and test the recommendation system.

### Usage

- Load the dataset by running the cells in the notebook.
- Use the interactive section to input a movie title and receive recommendations.

## Example

If you select **Avatar**, the system might recommend movies like:
- Pirates of the Caribbean: At World's End
- Spectre
- The Dark Knight Rises

## Contributing

Contributions are welcome! Feel free to submit issues or pull requests.
