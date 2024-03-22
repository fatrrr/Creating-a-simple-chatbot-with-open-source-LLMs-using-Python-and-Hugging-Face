# Creating a simple chatbot with open-source LLMs using Python and Hugging Face
### Introduction: Under the hood of a chatbot
#### Intro: How does a chatbot work?
A chatbot is a computer program that takes a text input, and returns a corresponding text output.

Chatbots use a special kind of computer program called a transformer, which is like its brain. Inside this brain, there is something called a language model (LLM), which helps the chatbot understand and generate human-like responses. It looks at lots of examples of human conversations it has seen before to help it respond in a way that makes sense.

Transformers and LLMs work together within a chatbot to enable conversation. Here's a simplified explanation of how they interact:

- Input Processing: When you send a message to the chatbot, the transformer helps process your input. It breaks down your message into smaller parts and represents them in a way that the chatbot can understand. Each part is called a token.
- Understanding Context: The transformer passes these tokens to the LLM, which is a language model trained on lots of text data. The LLM has learned patterns and meanings from this data, so it tries to understand the context of your message based on what it has learned.
- Generating Response: Once the LLM understands your message, it generates a response based on its understanding. The transformer then takes this response and converts it into a format that can be easily sent back to you.
- Iterative Conversation: As the conversation continues, this process repeats. The transformer and LLM work together to process each new input message, understand the context, and generate a relevant response.

The key is that the LLM learns from a large amount of text data to understand language patterns and generate meaningful responses. The transformer helps with the technical aspects of processing and representing the input/output data, allowing the LLM to focus on understanding and generating language

Once the chatbot understands your message, it uses the language model to generate a response that it thinks will be helpful or interesting to you. The response is sent back to you, and the process continues as you have a back-and-forth conversation with the chatbot.

#### Intro: Hugging Face
Hugging Face is an organization that focuses on natural language processing (NLP) and AI. They provide a variety of tools, resources, and services to support NLP tasks.

We'll be making use of their Python library transformers , as you'll see soon.

Alright! Now that we know how a chatbot works at a high-level, let's get started with implementing a simple chatbot!
