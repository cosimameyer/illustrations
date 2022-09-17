# Illustrations

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/deed.de)

This folder contains illustrations that I generated to explain concepts in #stats, #rstats, and/or #python. 

If you find it useful, that's great! I created the illustrations to make (more or less) complex topics more understandable and you're more than welcome to use it by CC-BY license. Please attribute it by citing "Illustration by @cosima_meyer".

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## What I enjoy doing: Creativity, code, and puzzles

<img src="https://github.com/cosimameyer/illustrations/blob/main/creativity_and_code.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/creativity_and_code.png" width="500" height="500" />

**ALT:**

## Writing functions in R


### CheatSheet

<img src="https://github.com/cosimameyer/illustrations/blob/main/CS_Functions.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/CS_Functions.png" width="700" height="500" />

**ALT:**

## Debugging in R

### CheatSheet

<img src="https://github.com/cosimameyer/illustrations/blob/main/CS_Debugging.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/CS_Debugging.png" width="700" height="500" />

**ALT:**

## Writing a package in R

### CheatSheet

<img src="https://github.com/cosimameyer/illustrations/blob/main/CS_Package.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/CS_Package.png" width="700" height="500" />

**ALT:**

## Shiny 

### UI and Server

<img src="https://github.com/cosimameyer/illustrations/blob/main/Shiny_UI.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/Shiny_UI.png" width="700" height="500" />

**ALT:**

<img src="https://github.com/cosimameyer/illustrations/blob/main/Shiny_Server.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/Shiny_Server.png" width="700" height="500" />

**ALT:**

### Visualization of reactivity (based on the excellent description by Garett Grolemund)

<img src="https://github.com/cosimameyer/illustrations/blob/main/Shiny_flow.gif" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/Shiny_flow.gif" width="500" height="500" />

**ALT:** GIF showing a pigeon carrier flying to the server to update a visualization when it is relevant

### CheatSheet

<img src="https://github.com/cosimameyer/illustrations/blob/main/CS_Shiny.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/CS_Shiny.png" width="700" height="500" />

**ALT:** A visual summary of ShinyApps

left side: 
User interface (body) that defines the outer appearance of the app 
An image showing a pseudo UI
ui <- fluidPage(
titltePanel("Your Title"),
sidebarLayout(sidebarPanel(... Some content...), 
mainPanel(...place-your-plot...))

right side: 
server (brain) where all the calculation happens
An image showing a pseudo server
server <- function(input, output{output$first_plot <- renderPlot({...create-your-plot....})}

## Git(Hub)

### Workflow
<img src="https://github.com/cosimameyer/illustrations/blob/main/Git_workflow.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/Git_workflow.png" width="700" height="500" />

**ALT:**

### GitHub and RStudio
<img src="https://github.com/cosimameyer/illustrations/blob/main/Git_R.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/Git_R.png" width="700" height="500" />

**ALT:**

### CheatSheet

<img src="https://github.com/cosimameyer/illustrations/blob/main/CS_GitHub.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/CS_GitHub.png" width="700" height="500" />

**ALT:**

## NLP

### Terms and concepts
<img src="https://github.com/cosimameyer/illustrations/blob/main/CS_Terms.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/CS_Terms.png" width="500" height="700" />

**ALT:** Image showing a visual overview of terms and concepts explaining a corpus, tokens, tokenization, DFM, stemming, and lemmatization. The verbalized version is in the text below:
Corpus: When you have your text data ready, you have your corpus. It’s a collection of documents. 
Tokens: Define each word in a text (but it could also be a sentence, paragraph, or character).
Tokenization: When you hear the word tokenization, it means that you are splitting up the sentences into single words (tokens) and turning them into a bag of words. You can take this quite literally - a bag of words does not really take the order of the words into account. There are ways to account for the order using n-grams (so for instance a bigram would leave the sentence "Rory lives in a world of books" as "Rory lives", "lives in", "in a", "a world", "world of", "of books") but it’s limited.
Document-feature matrix (DFM): To generate the DFM you first split the text into its single terms (tokens), then count how frequently each token occurs in each document.
Stemming: With stemming, you are getting the stem of the word.
Lemmatization: With lemmatization, it’s slightly different. Instead of "stud" (which is the stem of the study terms), you end up with a meaningful stem - "study"

### BERT 
<img src="https://github.com/cosimameyer/illustrations/blob/main/BERT_BoW.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/BERT_BoW.png" width="700" height="500" />

**ALT:** Image showing two different workflows (Bag of words and BERT). The main difference is that with BERT you build upon a pre-trained model and tokenizer while with BOW you often have to train a model from scratch.

<img src="https://github.com/cosimameyer/illustrations/blob/main/Train_BERT.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/Train_BERT.png" width="700" height="500" />

**ALT:** Image showing three important components to know when training a BERT model.
First, with BERT, you identify the order of the input. You give the model information about different embedding layers (the tokens (BERT uses special tokens ([CLS] and [SEP]) to make sense of the sentence), the positional embedding (where each token is placed in the sentence), and the segment embedding (which gives you more info about the sentences to which the tokens belong).
And then there is the training:
The first half of the training involves masking the words (Mask ML). During the training period, you mask one word at a time and the model learns, which word usually follows.
During the second half, you train the model to predict the next sentence. This way, the model learns which sentences usually follow each other.


