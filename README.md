# Movie Recommender System

This repository contains the code for a movie recommender system that utilizes cosine similarity to provide personalized movie recommendations based on user preferences.

## Overview

The movie recommender system suggests movies to users based on their viewing history and preferences. By using cosine similarity, the system identifies movies that are similar to those the user has enjoyed.

## Cosine Similarity

Cosine similarity is a metric that measures the cosine of the angle between two non-zero vectors. It is used to determine how similar two items are, regardless of their size. In this project, it helps in identifying similar movies based on their features.

**Formula:**
\[ 
\text{cosine\_similarity} = \frac{A \cdot B}{\|A\| \|B\|} 
\]

where \(A\) and \(B\) are the vectors representing the movies.

## Features

- User preference analysis
- Similarity calculation using cosine similarity
- Scalable to handle large datasets

## Getting Started

### Prerequisites

- Python 3.6+
- Required libraries: `numpy`, `pandas`, `scikit-learn`

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/movie-recommender-system.git
    cd movie-recommender-system
    ```

2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Prepare your dataset of movies and user preferences.
2. Run the main script to generate recommendations:
    ```bash
    python recommend.py
    ```

## Examples

### Output

![Movie Recommendations Output](movie_recomm1.PNG)
![Movie Recommendations Output](movie_recomm2.PNG)

## Contributing

Contributions are welcome! Please submit a Pull Request for any improvements or suggestions.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
