# Artificial Intelligence: Using Transformers via code in Python Language
The goal is use Transformer via code in Python Language

- Tranformer is a type of neural network architecture that transforms or changes an input sequence into an output sequence. They do this by learning the context and tracking the relationships between the components of the sequence.
- https://en.wikipedia.org/wiki/Attention_Is_All_You_Need

- It’s a general architecture of a neural network introduced in 2017 by the paper "Attention is All You Need." It acts as the "skeleton" that defines how data is processed in multiple stages. The core idea of the Transformer is the attention mechanism, which helps focus more on the important parts of the input (e.g., words in a sentence). The Transformer can be used for various tasks, such as language translation, text generation, or classification.

- In summary: The Transformer is a versatile tool for working with sequential data, like text.

### Use tools:

- Hugging Face: https://huggingface.co/
- Language Python: https://www.python.org/
- Page: https://pt.wikipedia.org/wiki/Microsoft_Office
- Library Python:
   * transformers  beautifulsoup4 requests
   * openai

### Important Point:

- In my case, I used ``` Google Colab ``` how platform to write the script. But, you can use anyone of the preference.

### Showing:

1 - First, istall library: transformers  beautifulsoup4 requests and openai
![image](https://github.com/user-attachments/assets/aff7dfa0-0ef5-45f9-a750-82a252e8ae02)

![image](https://github.com/user-attachments/assets/0856a765-c46b-404d-91ac-4d4b59ecb80e)

2 - After, declaring libraries:
![image](https://github.com/user-attachments/assets/34508df2-c71d-49ed-b977-3f1c63415f32)
   1) Library to request document from Web
   2) Operate with Berts Models 

3 - Function to prepare our Dataset:
![image](https://github.com/user-attachments/assets/9c672210-ffbc-4b82-8064-bf4ce6a5d968)
Only need pass URL, where join in the visible text separete for space.

## Using the Pure Transformer
# 1 - Q & R (Question and Answer)

Ideal use this tools in situation that I need to take out doubt in chatbox.

![image](https://github.com/user-attachments/assets/cd37839f-1248-4966-a69d-80c844b7dca8)

Remembering that Dataset is about Windows history, so the question need about it.
![image](https://github.com/user-attachments/assets/55875ed2-1832-4bce-82e8-a28e53dc4235)

In case above, it was used standard model, but case you want use specific model so, add parameter according to below:
![image](https://github.com/user-attachments/assets/dcc0937a-853f-469a-b691-f700db310ace)

And where pick up models:
![image](https://github.com/user-attachments/assets/da67db63-ba67-4f76-9d04-097431eb927c)

# 2 - Summarize

Ideal use this tools in situation that I need summary big text in small text. 

![image](https://github.com/user-attachments/assets/8e2891f3-947a-4c9f-adf0-7c6f4b6e37cc)
Reinforcing, summary create here, is with base on the dataset created with data: https://pt.wikipedia.org/wiki/Microsoft_Office

![image](https://github.com/user-attachments/assets/f3755e2f-5dbe-4d5d-bb6f-49584c768ae3)

Summary followed the parameters include in the code.
![image](https://github.com/user-attachments/assets/d3c83640-57be-47e6-8f0c-d6ca1427e983)

# 3 - Sentiment Analysis 

Ideal use this tools in opinions, reviews situations, because it rate in "Positive", "Neutral", "Negative"

Example below, we evaluate the sentence directly: "Microsoft is a fantastic company, which contains wonderful products that make our daily lives easier."
![image](https://github.com/user-attachments/assets/7795e44c-e7d6-46f2-a080-8c4b276fe967)

Result:
![image](https://github.com/user-attachments/assets/d4f04024-461f-4e83-b29f-0ed4978e97e3)


## Useful links:
- https://github.com/WanderBernardo/ArtificialIntelligence_HuggingFace
- https://github.com/WanderBernardo/ArtificialIntelligence_UsingBERT


