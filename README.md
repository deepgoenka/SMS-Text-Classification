# SMS Text Classification: Spam vs. Ham

## Overview
This project helps identify and filter out spam text messages from regular SMS messages. It's designed to make managing SMS communication easier.

## Data
We use a dataset of labeled SMS messages, with "Spam" and "Ham" (non-spam) labels. You can find the Training dataset [here](https://cdn.freecodecamp.org/project-data/sms/train-data.tsv) and Testing dataset [here](https://cdn.freecodecamp.org/project-data/sms/valid-data.tsv).

## Installation
To use this project, follow these steps:

1. Clone this repository.
2. Navigate to the project directory.
3. Create a virtual environment (optional but recommended).
4. Activate the virtual environment:
  - On Windows:
    ```
    venv\Scripts\activate
    ```
  - On macOS and Linux:
    ```
    source venv/bin/activate
    ```
5. Install the required packages.

Once set up, you can classify SMS messages with these steps:

1. Prepare your SMS message data.
2. Run the classification script.
3. The script will tell you if each SMS is "Spam" or "Ham".

## Model Training
To train your own model, use the provided Jupyter notebook `SMS_Text_Classification.ipynb`.

## Evaluation
Evaluate the model's performance with the evaluation script.

## Contributing
We welcome contributions! Here's how:
1. Fork the repository.
2. Create a new branch for your changes.
3. Make and commit your changes.
4. Push your changes to your fork.
5. Create a pull request.
