# Query ChatBot for IIT Bhilai

This query chatbot is specifically designed to answer queries related to IIT Bhilai. The chatbot is built using machine learning and natural language processing techniques, allowing it to understand and respond to user queries about the institute.

## How to Use

### Prerequisites

Make sure you have Python installed on your system. Additionally, install the required dependencies using the following commands in the command prompt or terminal:

```
pip install tensorflow
pip install keras
pip install numpy
pip install nltk
```

### Training the Model

1. Open your command prompt or terminal and navigate to the project folder in this repo.

2. Train the model using the following command:

   ```
   python train.py
   ```

   If the training completes without any errors, the model has been successfully created.

### Running the ChatBot

1. Once the model is trained, run the chatbot application by executing the `query_chatbot.py` file in the command prompt or terminal:

   ```
   python query_chatbot.py
   ```

2. The program will open a GUI window within a few seconds, providing you with an interface to interact with the chatbot.

3. Use the GUI to chat with the bot and ask any queries related to IIT Bhilai. The chatbot will process your questions and respond accordingly.

## Note

- The chatbot's performance is dependent on the training data and the queries it has been exposed to during training.It can only answer basic queries and queries redagring IIT Bhilai's basic facilities and admissions. Updating the data as and when required would improve its performance.
- If you encounter any issues or errors while running the application, make sure all dependencies are installed correctly and the necessary files are present in the project folder.

![Query ChatBot Demo](Screenrecording_chatbot.mp4)

Enjoy interacting with the IIT Bhilai Query ChatBot and feel free to provide feedback to improve its performance!
