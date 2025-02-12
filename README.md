# Qwen2.5 Classifier

This project uses the Qwen2.5-0.5B model for sequence classification on the IMDB dataset.

## Project Structure

- `main.py`: Entry point of the project.
- `classification/train.ipynb`: Jupyter notebook for training and evaluating the model.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `README.md`: Project documentation.

## Setup

1. Clone the repository:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Training the Model

1. Open the Jupyter notebook:
    ```sh
    jupyter notebook classification/train.ipynb
    ```

2. Follow the steps in the notebook to train and evaluate the model.

## Saving the Model

The trained model and tokenizer will be saved in the `qwen2.5-classifier` directory.

## Results

Training outputs, such as checkpoints and logs, will be saved in the `results` directory.

## License

This project is licensed under the MIT License.