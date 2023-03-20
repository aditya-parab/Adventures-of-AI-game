# Adventures of AI - A GPT Powered Storytelling Experience
ECS 289G Project

University of California Davis

## Introduction
Our storytelling system employs a GPT-2 instance to generate the initial portion of an adventure story based on a dataset-provided prompt. To ensure narrative coherence and dramatic progression, the generated story segment is assigned a drama score derived from the sentiment analysis of the current scene. The drama score then informs the generation of suitable input options that affect plot intensity and narrative drive. Subsequently, a human player selects one of these input options, and the chosen input, along with the story history, is fed back into the GPT-2 instance to further develop the narrative. Through iterative cycles of AI-generated content and human input, our system facilitates the co-creation of engaging, customized stories that cater to individual preferences while maintaining a consistent narrative structure.

## Methodology
<img src="https://user-images.githubusercontent.com/67012098/226222269-0c19d42b-cdc6-4c50-82ce-c552bc0e7028.png" width="70%" height="70%">

## Technology Used
* GPT-2 : to generate text
* NLTK : language processing into sentences
* TextBlob : to generate sentiment score of a text
* Hugging Face transformers: to generate user choice from text
* BLEU, Perplexity : to assign a score evaluating the quality of text

## Results
![Results graph](https://user-images.githubusercontent.com/67012098/226225352-ef92d681-682a-419a-909a-b221cbe6cf07.png)

Graphical representation of sentiment  score value progression

## Running the code
Clone the repo using "git clone https://github.com/aditya-parab/Adventures-of-AI-game.git".

Run the "ecs-289g.ipynb" python notebook. Remember to add/change the initial prompt in **cell number 4** before running the code.

Going throught the code, you will be able to edit and use multiple different GPT-2 models. The code is self-explanatory.
