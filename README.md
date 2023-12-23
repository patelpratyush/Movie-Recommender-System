# Movie Recommender System

This project is a simple Movie Recommender System built using Streamlit, Python, and machine learning techniques. The system recommends movies based on user input and utilizes a pre-trained model to provide personalized suggestions.

## Usage

To use this Movie Recommender System, follow these steps:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/patelpratyush/movie-recommender.git
    ```

2. Navigate to the project directory:

    ```bash
    cd movie-recommender
    ```

3. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

5. Open your web browser and go to [http://localhost:8501](http://localhost:8501) to interact with the Movie Recommender System.

## How to Use

1. Select a movie from the dropdown menu.
2. Click the "Recommend" button to receive personalized movie recommendations.
3. Explore the recommended movies and their posters.

## Project Structure

- `app.py`: The main Streamlit application file.
- `movies_dict.pkl`: Pickle file containing movie data.
- `similarity.pkl`: Pickle file containing similarity scores between movies.
- `requirements.txt`: List of Python dependencies for easy installation.

Feel free to explore and customize the code to suit your needs. Enjoy discovering new movies!
