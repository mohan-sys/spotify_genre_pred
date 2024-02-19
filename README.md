# Spotify Song Genre Prediction

Welcome to our project repository for predicting the genre of songs using machine learning techniques! In this project, we aim to develop a model that accurately predicts the genre of a song based on its attributes. This repository contains all the necessary resources, including code, data, and documentation, to reproduce our results and further explore the problem.

## Problem Statement

Your task for this part of the class assignment is to build a model to predict the genre of a song (the broad category to which it belongs such as "rock," "pop," "blues," etc.). The dataset used for this task is drawn from [Kaggle](https://www.kaggle.com/cnic92/spotify-past-decades-songs-50s10s). The dataset has been slightly modified, renaming the first column to "Id" from "Number" and relocating the "top genre" to the final column. Additionally, there are some missing values, and the year is not always coherent due to some re-releases.

## Dataset

The dataset consists of various attributes of songs spanning different decades, including features such as danceability, energy, loudness, and more. Ignoring the "Id" and "top genre" columns, there are 13 other attributes in the dataset that can be used to build the predictive model. Make sure to download the training data from the competition page mentioned above.

## Approach

We treat this problem as a classification task, where the goal is to predict the genre of a song based on its attributes. The performance of the model will be evaluated based on classification accuracy. You are encouraged to explore, understand, and clean the data before building the model. Feel free to use as many or as few attributes as you like, but ensure to spend ample time on data preprocessing and feature engineering.

## Repository Structure

- `data/`: Contains the dataset used for training the model. Make sure to download the data from the provided Kaggle link.
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, model development, and evaluation.
- `src/`: Source code for the machine learning model implementation.
- `requirements.txt`: List of Python dependencies required to run the code.
- `README.md`: Detailed information about the project, including setup instructions, usage guidelines, and other relevant details.

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/spotify-genre-prediction.git
   ```

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the dataset from [Kaggle](https://www.kaggle.com/cnic92/spotify-past-decades-songs-50s10s) and place it in the `data/` directory.

4. Explore the Jupyter notebooks in the `notebooks/` directory to understand the data and the model development process.

5. Train and evaluate your model using the provided code in the `src/` directory.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/improvement`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/improvement`).
6. Create a new Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, suggestions, or feedback, feel free to contact us.

Happy coding! 🎶
