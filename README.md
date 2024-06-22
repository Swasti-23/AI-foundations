# CerebralChat: Advanced AI Virtual Chatbot

## Overview
CerebralChat is an advanced AI virtual chatbot designed to enhance user experience and information retrieval through speech commands. It provides real-time updates on weather, news, date, and time, excels in generating both text and speech, and operates seamlessly offline. Unlike traditional solutions, CerebralChat demonstrates a high accuracy rate in comprehending and responding to user queries.

## Features
- **Real-Time Updates**: Provides current weather, news, date, and time.
- **Speech Recognition**: Understands and processes user speech commands.
- **Text and Speech Generation**: Generates both text and spoken responses.
- **Task Automation**: Can perform tasks such as playing music and sending emails.
- **Customizable Dataset**: Uses a tailored dataset developed through a neural network for high accuracy.
- **Offline Functionality**: Operates without the need for an internet connection.
- **User-Friendly GUI**: Integrated into a graphical user interface for intuitive interaction.

## Project Vision
Inspired by advancements in generative AI, we aim to create an intelligent AI chatbot that seamlessly integrates into users’ lives, offering features beyond basic question-answering. This includes real-time weather updates, natural language conversations, efficient email communication, and information retrieval from sources like Wikipedia.

## Techniques and Architecture

### Preprocessing Steps
1. **Text Normalization**: Standardizes text by converting all input patterns and responses to lowercase for uniformity.
2. **Tokenization**: Breaks down text into individual words or subwords for enhanced feature extraction.
3. **Stopword Removal**: Removes commonly occurring stopwords to streamline the dataset.
4. **Lemmatization**: Reduces inflected forms to their base or root form, optimizing the dataset.
5. **Context Handling**: Designed to integrate context features in the future for improved conversational capabilities.

### Brain-Inspired Neural Networks
- **Input Layer**: Receives a bag-of-words representation of the input sentence.
- **Hidden Layer**: Introduces non-linearity and complexity to capture intricate patterns.
- **Output Layer**: Uses the softmax activation function to produce probability scores for each intent.
- **Backpropagation**: Iteratively adjusts the network’s weights for optimal performance.

### Core Functions
1. **Listen Function**: Converts spoken language into text using speech recognition modules.
2. **Speak Function**: Converts textual responses into spoken language using text-to-speech synthesis.
3. **Task Execution**: Translates recognized intent into actionable tasks.

### Related Modules
- **Speech Recognition**: Converts spoken language into text.
- **Text-to-Speech Synthesis**: Converts text into natural-sounding speech.
- **Intent Recognition**: Determines user’s intent to guide response strategy.
- **Task Execution Logic**: Executes specific tasks based on recognized intents.

## Model Architecture
- **Input Layer**: Receives input sentences for understanding user context.
- **Hidden Layer**: Captures complex patterns with eight neurons.
- **Output Layer**: Tailored to specific intents with softmax activation for probability distribution.

### Training
The model is trained using a cross-entropy loss function, ideal for multi-class classification problems like identifying user intents in a conversation.

### Additional Features
1. **Music**: Can play songs upon request.
2. **Information Retrieval**: Retrieves information from Wikipedia.
3. **Web Interaction**: Opens various websites for a seamless browsing experience.
4. **Live News**: Fetches and delivers live news updates.

## Dataset Description and Pre-Processing
The dataset, meticulously crafted from scratch, captures diverse user intents and covers a broad spectrum of conversations, including topics like films, jokes, music recommendations, and more. This exclusive dataset empowers the chatbot with functionalities such as reading news, playing songs, providing date and time information, and conducting Wikipedia searches.

## Result
CerebralChat, an AI-driven chatbot, boasts over 500 conversational skills, providing dynamic and engaging interactions. It offers real-time updates for news and weather, accesses various online platforms, and provides time and date information. The Tkinter-based GUI enhances accessibility and usability across different devices.

<p float="left">
  <img src="https://github.com/Swasti-23/AI-foundations/blob/main/Images/output.jpg?raw=true" width="315" />
  <img src="https://github.com/Swasti-23/AI-foundations/blob/main/Images/inteli-assist.png?raw=true" width="500" /> 
  <img src="https://github.com/Swasti-23/AI-foundations/blob/main/Images/seqdia%20final.png?raw=true"/>
</p>

