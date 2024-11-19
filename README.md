# OpenSourceModelsHuggingFace
A couple of open source models found in  that cn be found in Hugging face platform
- Used the hugging space transformers library to perform variouus NLP taks
# Project 1: Creating an NLP Chatbot using transformers library from hugging space🤗
## Demo
![https://1drv.ms/i/c/f27c9b8dda2a7203/EVV3ek6IJWRMnEH2GkItTh0BhhtUzSye2k_3GoUfIqZv4A?e=Ofexao]

## Methodology 👩‍💻
1. Install the transformers library using !pip install transformers, enables you to load open source models from hugging space🤗.
2. Import pipeline inorder to create a conversational pipeline.
3. Choose the suitable model for this by actually seraching up for it. Forour case we used the [Facebook model blender box ][https://huggingface.co/facebook/blenderbot-400M-distill]. It's small and performs quite well.
4. Load the model directly as shown in the notebook.

## Usage
1. User input: Inside the loop, input("You: ") is used to get the user's question.
2. Exit condition: The loop checks if the user typed "exit", "quit", or "bye". If so, it breaks out of the loop, ending the conversation.
3. Response generation: If the user didn't want to exit, the code generates the bot's response using the tokenizer and model, just like before.

   ## Acknowledgements
   This courtesy of the DeepLearning.AI Open Source models with hugging space.

   Made with love 💙.
