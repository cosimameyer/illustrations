# Illustrations

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/deed.de)

This folder contains illustrations that I generated to explain concepts in #stats, #rstats, and/or #python. 

If you find it useful, that's great! I created the illustrations to make (more or less) complex topics more understandable and you're more than welcome to use it by CC-BY license. Please attribute it by citing "Illustration by @cosima_meyer".

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## General art

### What I enjoy doing: Creativity, code, and puzzles

<img src="https://github.com/cosimameyer/illustrations/blob/main/misc/creativity_and_code.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/misc/creativity_and_code.png" width="500" height="500" />

<details><summary>ALT</summary>Image showing two people holding two puzzle pieces to the sky (on one piece it says ”Creativity“, on the other ”Code“)) with a subtitle below the two persons saying ”What I enjoy doing ♥️“</details>

### R and Python 💛💙

<img src="https://github.com/cosimameyer/illustrations/blob/main/misc/pythonistr.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/misc/pythonistr.png" width="400" height="500" />

<details><summary>ALT</summary>Image showing a blue R with a pirate's hat and eye patch with a snake (Python) around R's leg</details>

### Hello Mastodon 

<img src="https://github.com/cosimameyer/illustrations/blob/main/misc/hello_mastodon.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/misc/hello_mastodon.png" width="400" height="500" />

<details><summary>ALT</summary>A blue mastodon/elephant holding up a sign with "hello" in hand-writing written on it</details>


### R

<img src="https://github.com/cosimameyer/illustrations/blob/main/misc/pirate_r.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/misc/pirate_r.png" width="400" height="500" />

<details><summary>ALT</summary>Image showing a blue R with a pirate's hat and eye patch</details>


## Writing functions in R


### CheatSheet

<img src="https://github.com/cosimameyer/illustrations/blob/main/writing-functions-r/CS_Functions.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/writing-functions-r/CS_Functions.png" width="700" height="500" />

<details><summary>ALT</summary>Image showing how a general function in R looks like (a function has arguments, a function statement, and usually a return function). Good practices when writing functions are: 
Use meaningful names for your functions. It’s good to use verbs for functions.
Make your function short and simple - each function should do one thing at a time
Use an explicit return statement
Writing assertions, warnings and stops is helpful</details>

## Debugging in R

### CheatSheet

<img src="https://github.com/cosimameyer/illustrations/blob/main/debugging-r/CS_Debugging.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/debugging-r/CS_Debugging.png" width="700" height="500" />

<details><summary>ALT</summary>Image showing a mole as a comparison for the debugging process (a mole digs in using debug(), stops when there is a browser(), and leaves the tunnel when calling undebug(). It also shows how the flow package works and that you get a visual overview of the "flow" of your package.</details>

## Writing a package in R

### CheatSheet

<img src="https://github.com/cosimameyer/illustrations/blob/main/writing-packages-r/CS_Package.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/writing-packages-r/CS_Package.png" width="700" height="500" />

<details><summary>ALT</summary>A summary reiterating the basic structure in package development (DESCRIPTION, NAMESPACE, R/, man/, and tests/) as well as helpful packages (devtools, use this, roxygen2, testthat, xpectr, cover, goodpractice, inteRgrate).</details>

## Shiny 

### UI and Server

<img src="https://github.com/cosimameyer/illustrations/blob/main/shiny/Shiny_UI.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/shiny/Shiny_UI.png" width="700" height="500" />

<details><summary>ALT</summary>An image showing a pseudo UI
ui <- fluidPage(
titltePanel("Your Title"),
sidebarLayout(sidebarPanel(... Some content...), 
mainPanel(...place-your-plot...))</details>

<img src="https://github.com/cosimameyer/illustrations/blob/main/shiny/Shiny_Server.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/shiny/Shiny_Server.png" width="700" height="500" />

<details><summary>ALT</summary>An image showing a pseudo server
server <- function(input, output{output$first_plot <- renderPlot({...create-your-plot....})}</details>

### Visualization of reactivity (based on the excellent description by Garett Grolemund)

<img src="https://github.com/cosimameyer/illustrations/blob/main/shiny/Shiny_flow.gif" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/shiny/Shiny_flow.gif" width="500" height="500" />

<details><summary>ALT</summary>GIF showing a pigeon carrier flying to the server to update a visualization when it is relevant</details>


### CheatSheet

<img src="https://github.com/cosimameyer/illustrations/blob/main/shiny/CS_Shiny.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/shiny/CS_Shiny.png" width="700" height="500" />

<details><summary>ALT</summary>A visual summary of ShinyApps

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
server <- function(input, output{output$first_plot <- renderPlot({...create-your-plot....})}</details>

## Git(Hub)

### Workflow
<img src="https://github.com/cosimameyer/illustrations/blob/main/git/Git_workflow.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/git/Git_workflow.png" width="700" height="500" />

<details><summary>ALT</summary>Image showing a git workflow from the working directory to the remote repo. 
Working directory → Staging area → local repo → remote repo and also common git commands (git add code.R, git commit -m "Update", git push, git pull, git checkout, git merge)</details>

### Branches
<img src="https://github.com/cosimameyer/illustrations/blob/main/git/branches2.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/git/branches2.png" width="700" height="500" />

<details><summary>ALT</summary>GIF showing how a feature branch evolves from a main branch and is then guided back (merged) into the main branch</details>

### GitHub and RStudio
<img src="https://github.com/cosimameyer/illustrations/blob/main/git/git_rstudio.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/git/git_rstudio.png" width="700" height="500" />

<details><summary>ALT</summary>Visualization showing a typical workflow when using GitHub in RStudio with a new project: 1) Create a new repository on GitHub, 2) Open . Rproj in RStudio, 3) Connect with GitHub - and now it’s time to pull, commit and push :)</details>

### GitHub and VS Code
<img src="https://github.com/cosimameyer/illustrations/blob/main/git/git_vscode.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/git/git_vscode.png" width="700" height="500" />

<details><summary>ALT</summary>Visualization showing a typical workflow when using GitHub in VS Code with a new project: 1) Create a new repository on GitHub, 2) Clone repository in your VS Code, 3) Connect with GitHub - and now it’s time to pull, commit and push :)</details>


### CheatSheet

<img src="https://github.com/cosimameyer/illustrations/blob/main/git/CS_GitHub.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/git/CS_GitHub.png" width="700" height="500" />

<details><summary>ALT</summary>Visual summary of how to GitHub in and with RStudio
left side: Image showing a git workflow from the working directory to the remote repo. 
Working directory → Staging area → local repo → remote repo and also common git commands (git add code.R, git commit -m "Update", git push, git pull, git checkout, git merge)
right side: Visualization showing a typical workflow when using GitHub in RStudio with a new project: 1) Create a new repository on GitHub, 2) Open .Rproj in RStudio, 3) Connect with GitHub - and now it's time to pull, commit and push :)</details>
  
## NLP

### Terms and concepts
<img src="https://github.com/cosimameyer/illustrations/blob/main/nlp/CS_Terms_purple.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/nlp/CS_Terms_purple.png" width="500" height="700" />

<details><summary>ALT</summary>Image showing a visual overview of terms and concepts explaining a corpus, tokens, tokenization, DFM, stemming, and lemmatization. The verbalized version is in the text below:
Corpus: When you have your text data ready, you have your corpus. It’s a collection of documents. 
Tokens: Define each word in a text (but it could also be a sentence, paragraph, or character).
Tokenization: When you hear the word tokenization, it means that you are splitting up the sentences into single words (tokens) and turning them into a bag of words. You can take this quite literally - a bag of words does not really take the order of the words into account. There are ways to account for the order using n-grams (so for instance a bigram would leave the sentence "Rory lives in a world of books" as "Rory lives", "lives in", "in a", "a world", "world of", "of books") but it’s limited.
Document-feature matrix (DFM): To generate the DFM you first split the text into its single terms (tokens), then count how frequently each token occurs in each document.
Stemming: With stemming, you are getting the stem of the word.
Lemmatization: With lemmatization, it’s slightly different. Instead of "stud" (which is the stem of the study terms), you end up with a meaningful stem - "study"</details>

### BERT 
<img src="https://github.com/cosimameyer/illustrations/blob/main/nlp/BERT_BoW_purple.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/nlp/BERT_BoW_purple.png" width="700" height="500" />

<details><summary>ALT</summary>Image showing two different workflows (Bag of words and BERT). The main difference is that with BERT you build upon a pre-trained model and tokenizer while with BOW you often have to train a model from scratch.</details>

<img src="https://github.com/cosimameyer/illustrations/blob/main/nlp/Train_BERT_purple.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/nlp/Train_BERT_purple.png" width="700" height="500" />
  
<details><summary>ALT</summary>Image showing three important components to know when training a BERT model.
First, with BERT, you identify the order of the input. You give the model information about different embedding layers (the tokens (BERT uses special tokens ([CLS] and [SEP]) to make sense of the sentence), the positional embedding (where each token is placed in the sentence), and the segment embedding (which gives you more info about the sentences to which the tokens belong).
And then there is the training:
The first half of the training involves masking the words (Mask ML). During the training period, you mask one word at a time and the model learns, which word usually follows.
During the second half, you train the model to predict the next sentence. This way, the model learns which sentences usually follow each other.</details>

These visualizations are also available in *blue*: 

<p float="left">
  <img src="https://github.com/cosimameyer/illustrations/blob/main/nlp/BERT_Embedding_blue.png" width="200" />
  <img src="https://github.com/cosimameyer/illustrations/blob/main/nlp/BERT_training_blue.png" width="200" />
  <img src="https://github.com/cosimameyer/illustrations/blob/main/nlp/BERT_BoW_blue.png" width="200" /> 
</p>

## Explainable AI/ML

<img src="https://github.com/cosimameyer/illustrations/blob/main/explainable-machine-learning/explainable_ai.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/explainable-machine-learning/explainable_ai.png" width="700" height="500" />

<details><summary>ALT</summary>
The visualization of six different model agnostic approaches to explain machine learning models post-hoc such as

- **Feature importance**: Feature importance is based on the idea of permutation where you shuffle the values of a feature. If this change increases the model error, the feature is perceived to be important.
- **Shapley value**: Shapley values are based on a game theoretical approach that calculates the average of *all* marginal contributions to *all* possible outcomes.
- **LIME**: LIME plots tell you locally around a data point what the most important feature is. While they may look similar to SHAP, they are only an approximation (calculated on a small set of features and do not provide a guarantee of accuracy and consistency.
- **ICE**: ICE plots show the individual conditional expectation where all other features are kept the same and the effects for one feature are calculated.
- **Partial dependence**: Partial dependency plots visualize the *average* output of the model for each target feature value for the entire dataset.
- **Breakdown plot**: Breakdown plots show the contribution of every variable to the final prediction.</details>

<img src="https://github.com/cosimameyer/illustrations/blob/main/explainable-machine-learning/integrated_gradients.png" data-canonical-src="https://github.com/cosimameyer/illustrations/blob/main/explainable-machine-learning/integrated_gradients.png" width="700" height="500" />
  
<details><summary>ALT</summary>
The visualization shows the logic of integrated gradients. You start with your baseline which does not have any effect on the model classification and continue stepwise using linear interpolation to get to the original input. On the way, you calculate the model's prediction, compare it to the baseline, and derive the integrated gradients for each input feature by summing up the results of these calculations.
</details>


