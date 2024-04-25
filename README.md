# MyGPT
Mistral-7B-Instruct-v0.2-GPTQ

Model Description:
Mistral-7B-Instruct-v0.2-GPTQ is a fine-tuned language model based on the GPT architecture. It has been trained on an undisclosed dataset and tuned for instructional tasks. The model aims to generate coherent and contextually relevant responses to prompts or queries.

Intended Uses & Limitations:
This model is designed for instructional purposes, suitable for generating text in response to prompts, questions, or queries. It can be utilized in educational contexts, chatbots, or other applications requiring natural language understanding and generation. However, it's important to note that while the model strives to produce accurate and informative responses, it may occasionally generate inaccurate or nonsensical outputs, especially when prompted with ambiguous or out-of-domain input.

Training Procedure & Hyperparameters:
The model was trained using PyTorch framework with the PEFT library for efficient training. The training hyperparameters include a learning rate of 0.0002, batch size of 16 (with gradient accumulation), and a total of 10 epochs. The Adam optimizer with specific beta values and epsilon was employed, along with a linear learning rate scheduler. Additionally, native Automatic Mixed Precision (AMP) training was utilized for improved efficiency.

Training Results:
During training, the model achieved a final loss of 1.9196 on the evaluation set. Training progress was monitored with both training and validation losses reported at various epochs and steps.

Framework Versions:
The model was implemented using the following framework versions:

    PEFT 0.10.0
    Transformers 4.40.0
    PyTorch 2.1.0 with CUDA 12.1 support
    Datasets 2.19.0
    Tokenizers 0.19.1

Dataset:
The model was fine-tuned on data sourced from shawhin/shawgpt-youtube-comments, a dataset presumably consisting of YouTube comments. The specific details regarding the dataset, such as its size, diversity, and preprocessing steps, are not disclosed.

Video Link:

Video 1:
[Screencast from 25-04-24 12:31:57 PM IST.webm](https://github.com/akaisky07/MyGPT/assets/104855741/9ee15d7b-1001-4a63-9e6b-c530c9581721)

Video 2:
[Screencast from 28-01-24 12:40:25 PM IST.webm](https://github.com/akaisky07/MyGPT/assets/104855741/58ca387b-6ee7-4c29-9d89-639649ebfede)
