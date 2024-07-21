# Project: HomeMatch - Personalized Real Estate Agent

HomeMatch is a property recommendation system that helps users find their ideal home based on their preferences and requirements. The system
uses a combination of language models and vector embeddings to match user-defined criteria with real estate listings. It ranks the listings
based on relevance to the user's preferences and generates personalized descriptions for the top matches.

## Project Structure

- HomeMatch.ipynb: Jupyter notebook containing the code for the project
- Listings.txt: Sample real estate listings for testing the system
- requirements.txt: List of required packages for the project
- chroma_db: Directory where the chroma embeddings will be stored

## Installation

- Create .env file with your OPENAI_API_KEY
- Run `pip install -r requirements.txt`
- Run HomeMatch.ipynb notebook