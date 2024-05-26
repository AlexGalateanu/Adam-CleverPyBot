# Adam CleverPyBot

Welcome to the repository for Adam CleverPyBot, an intelligent chatbot built with Python, TensorFlow, and Natural Language Processing (NLP) techniques. This chatbot uses a machine learning model to understand and respond to user queries in a natural and intuitive manner.

## Features

- Natural Language Understanding: Utilizes NLTK for tokenization and lemmatization to preprocess user input.
- Dynamic Responses: Capable of generating context-appropriate responses from a predefined set of intents and their associated patterns.
- Customizable Intents: Easy to modify and add new intents through JSON configuration, allowing for expanded conversational capabilities.
- Neural Network Model: Employs a neural network built using TensorFlow to predict the intent of user queries.
- Real-Time Interaction: Designed to handle real-time querying from users.

## Technologies Used

- Python: Programming language used for the entire project.
- TensorFlow: For building and training the neural network model.
- NLTK (Natural Language Toolkit): Used for text processing and tokenization.
- NumPy: Essential for handling data arrays during processing and model training.

## Setup and Installation

To get started with Adam CleverPyBot, follow these installation steps:

1. Clone the repository:


   git clone https://github.com/AlexGalateanu/Adam-CleverPyBot.git



2. Navigate to the project directory:


   cd Adam-CleverPyBot



3. Install necessary packages:

   Ensure you have Python installed, then run:


   pip install nltk tensorflow numpy



   You may need to install additional NLTK resources with:


   import nltk
   nltk.download(“punkt”)
   nltk.download(“wordncet”)



## Usage

After setting up the project, you can start the chatbot in a command line interface:

1. Run the Python script:


   python chatbot.py



2. Interact with the chatbot through the command line prompt. Enter 0 to quit the chat session.

## Training the Model

The model can be retrained on new data or to refine its responses. The training data is stored in intents.json, where new intents and patterns can be added.

1. Modify intents.json as required.
2. Re-run the training section in the script to update the model.

## Contributing

Contributions to improve Adam CleverPyBot are welcome. Please feel free to fork the repository, make changes, and submit a pull request with your updates.

## License

This project is licensed under the MIT License - see the LICENSE.md file for details.

## Contact

Gălățeanu Alexandru - alexgalateanu2003@gmail.com

Project Link: https://github.com/AlexGalateanu/Adam-CleverPyBot

—

Enjoy interacting with Adam CleverPyBot, a glimpse into the potential of machine-learning driven conversational agents!
