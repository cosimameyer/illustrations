# Illustrations

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/deed.de)

This folder contains illustrations that I generated to explain concepts in #stats, #rstats, and/or #python. 

I'm very happy if you find these resources useful. I created the illustrations to make (more or less) complex topics more understandable and you're more than welcome to use them by CC-BY license. Please attribute it by citing "Illustration by @cosima_meyer".

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

## Amazing Women

The following illustrations are part of a larger project ("Amazing Women in Tech") in which I aim to make women more visible in the world of programming, statistics, and STEM in general. The illustrations are shared along with a short portrait on social media such as [LinkedIn](https://www.linkedin.com/feed/hashtag/?keywords=makingwomenmorevisible) and Mastodon.

|  |  |
| --- | --- |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/ada_lovelace_small.png" width="400" /> | **Ada Lovelace** <br><br>✨ was a mathematician and the first computer programmer<br>✨ worked on early versions of a calculator (with Charles Babbage)<br>✨ imagined the machine following patterns and not only calculating numbers but also forming letters - the basic version of computer programming was described in the 1840s!<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Ada_Lovelace) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/alison_hill_small.png" width="400" /> | **Alison Presmanes Hill** <br><br>✨ is a Director of Product at Anaconda, Inc., having previously worked at Voltron Data, Posit PBC, and IBM<br>✨ holds a PhD in Psychology from Vanderbilt University<br>✨ is an avid #OSS contributor (from website themes to #rstats packages to #data 🐧)<br>✨ is a strong advocate for promoting gender diversity in the #rstats community<br><br>🔗 [and much more](https://www.apreshill.com/) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/allison_horst_small.png" width="400" /> | **Allison Horst** <br><br>✨ is a Developing Marketing Manager at Observable<br>✨ holds a PhD in Environmental Science and was 10+ years a teaching faculty member at UC Santa Barbara<br>✨ is best known for her beautiful #Rtistry making data science and stats easily accessible<br>✨ is an avid contributor to #OSS - for instance the {palmerpenguins} package 🐧<br><br>🔗 [and much more](https://allisonhorst.github.io/) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/anita_borg_small.png" width="400" /> | **Anita Borg** <br><br>✨ was a computer scientist who started Systers and AnitaB.org to support women in tech<br>✨ founded the Grace Hopper Celebration of Women in Computing<br>✨ researched operating systems and memory at Digital Equipment Corporation<br>✨ was honored in the Women in Technology International Hall of Fame<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Anita_Borg) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/annie_easley_small.png" width="400" /> | **Annie Easley** <br><br>✨ was a pioneering computer scientist, mathematician, and rocket scientist at NASA, contributing to the development of software for the Centaur rocket program<br>✨ broke barriers as one of the first African-American women in her field, inspiring countless others<br>✨ used her expertise to develop energy conversion systems, including alternative power technologies<br>✨ advocated for diversity in STEM and supported others through educational outreach<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Annie_Easley) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/catherine_nelson_small.png" width="400" /> | **Catherine Nelson** <br><br>✨ is a freelance data scientist and writer who worked previously as a Principal Data Scientist at SAP Concur<br>✨ holds a PhD in geophysics from Durham University and a Master of Science in Earth Sciences from University of Oxford<br>✨ authored several hands-on books for data scientists to improve their daily workflows ([Software Engineering for Data Scientists](https://www.oreilly.com/library/view/software-engineering-for/9781098136192/) and [Building Machine Learning Pipelines](https://www.oreilly.com/library/view/building-machine-learning/9781492053187/)) <br><br>🔗 [and much more](https://datacircles.org/blog/meet-a-data-scientist-dr-catherine-nelson) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/crystal_ramjattan_small.png" width="400" /> | **Crystal Ramjattan** <br><br>✨  is a seasoned data leader with experience in leading data-driven transformations for startups and F500 companies<br>✨ has a proven track record of architecting and implementing data strategies<br>✨ founded a causal AI platform that helped companies detect and measure critical business changes, now supporting other startups<br>✨ has mentored over 30 women in technology, empowering them to navigate their careers and achieve their dreams in data 💫<br><br>🔗 [and much more](https://www.linkedin.com/in/cramjattan) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/daliana_liu_small.png" width="400" /> | **Daliana Liu** <br><br>✨ is the founder and coach of Data Science & ML Career Accelerator and has previously worked as a data scientist at Amazon<br>✨ hosts the podcast 'The Data Scientist Show' 🎙️ (https://www.youtube.com/c/thedatascientistshow)<br>✨ supports others in the field of #datascience with career insights, interviews, and her own personal journey<br><br>🔗 [and much more](https://substack.com/@dalianaliu) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/daniela_rus_small.png" width="400" /> | **Daniela Rus** <br><br>✨ is a roboticist and computer scientist, director and professor at the MIT<br>✨ pioneers in robotics and focuses her work on how a new generation of smart machines can help humans<br>✨ has co-authored the book 'The Heart and the Chip: Our Bright Future With Robots' (with Gregory Mone), which gives you a better understanding of how humans and robots can coexist<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Daniela_L._Rus) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/daniela_witten_small.png" width="400" /> | **Daniela Witten** <br><br>✨ is a biostatistician and Professor at the University of Washington<br>✨ focuses her research on [high-dimensional statistical learning](https://bit.ly/4bgvERU)<br>✨ co-authored the seminal book 'An Introduction to Statistical Learning' (both with #rstats and #python)<br>✨ has won multiple awards for her work<br><br>🔗 [and much more](https://en.m.wikipedia.org/wiki/Daniela_Witten) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/dorothy_vaughan_small.png" width="400" /> | **Dorothy Vaughan** <br><br>✨ was a mathematician and human computer at NASA<br>✨ was head of the National Advisory Committee for Aeronautics (NACA)<br>✨ many of you may also know her story from the book/movie 'Hidden Figures' which tells the story of her life<br>✨ was a role model as NASA’s first African-American manager<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Dorothy_Vaughan) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/chelsea_finn_small.png" width="400" /> | **Chelsea Finn** <br><br>✨ is an Assistant Professor at Stanford University and was part of Google Brain<br>✨ pioneers in the field of [deep robotic learning](https://nyti.ms/4dgoZsF)<br> ✨ has won multiple awards for her work<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Chelsea_Finn)|
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/ellie_king_small.png" width="400" /> | **Ellie King**<br><br>✨ is co-founder of Equal IT where they support organizations to recruit inclusive teams globally<br>✨ hosts the #EqualInspired podcast where she invites speakers to share empowering stories, career journeys, lessons learnt and advice to inspire others - have a listen here: https://linktr.ee/equalinspired 🎙️<br>✨ is a frequent speaker at conferences and meetups, amplifying the voices of women and non-dominant groups<br><br>🔗 [and much more](https://www.youtube.com/watch?v=mJqVYCD3T1o) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/frauke_kreuter_small.png" width="400" /> | **Frauke Kreuter** <br><br>✨ is a sociologist and statistician and holds Professorships at the University of Munich and the University of Maryland<br>✨ co-authored the seminal book 'Data Analysis Using Stata'<br>✨ also co-hosts the German podcast #digdeep that discusses developments in digitalization<br>✨ has won multiple awards for her work<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Frauke_Kreuter) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/gabriela_de_queiroz_small.png" width="400" /> | **Gabriela de Queiroz** <br><br>✨is the Director of AI at Microsoft and previously worked in AI strategy and innovation at IBM<br>✨ is a strong advocate for diversity in the field, having founded #RLadies and #AI Inclusive<br>✨ has won several awards for her work (including being named one of the 100 Brilliant Women in AI Ethics™ in 2023)<br><br>🔗 [and much more](https://en.m.wikipedia.org/wiki/R-Ladies#Gabriela_de_Queiroz) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/grace_hopper_small.png" width="400" /> | **Grace Hopper** <br><br>✨ was a computer scientist, mathematician, and US Navy rear admiral<br>✨ helped to develop a compiler that led to #COBOL, a widely used programming language<br>✨ was the first to refer to a computer problem as a 'bug' and to speak of 'debugging' a computer 🐞 (https://bit.ly/3V2mamK)<br>✨ broke more barriers by receiving the National Medal of Technology in 1991 (as the first female individual recipient; https://bit.ly/4bD7kdy)<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Grace_Hopper) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/hanan_salam_small.png" width="400" /> | **Hanan Salam** <br><br>✨ is Assistant Professor and Director of SMART Lab at New York University Abu Dhabi<br>✨ focuses her research on Artificial Social Intelligence - a form of intelligence that requires a machine to make sense of social cues when interacting with humans (https://bit.ly/3Seo82H)<br>✨ founded Women in AI in 2017 (together with Moojan Asghari and Caroline Lair) - a global non-profit organization focussing on creating #inclusiveAI for our common future<br><br>🔗 [and much more](https://medium.com/womeninai/a-story-of-resilience-passion-and-focus-hanan-salam-wai-co-founders-ai-journey-79bcbb1b1446)  |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/hedy_lamarr_small.png" width="400" /> | **Hedy Lamarr** <br><br>✨ was a Hollywood actress, inventor, and the 'Mother of Wi-Fi'<br>✨ came up with an improved stoplight and a tablet that dissolves in water and tastes like Coca-Cola<br>✨ together with George Antheil, also invented a new communication system that involves ‘frequency hopping’ and is now the basis for #WiFi, #Bluetooth, and #GPS<br>✨ received many awards for her work<br>🔗 [and much more](https://www.womenshistory.org/education-resources/biographies/hedy-lamarr) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/ida_rhodes_small.png" width="400" /> | **Ida Rhodes** <br><br>✨ was a pioneer in computer science (co-designed the C-10 programming language for the universal automatic computer I)<br>✨ developed an often-used algorithm for a Jewish calendar<br>✨ was referred to as the UNIVAC I Pioneer at the AFIPS National Computer Conference in Chicago<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Ida_Rhodes) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/international_womens_day_small.png" width="400" /> | **International Women's Day** <br><br>🔗 [... learn more about it](https://en.wikipedia.org/wiki/International_Women%27s_Day)  |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/jacqueline_nolis_small.png" width="400" /> | **Jacqueline Nolis** <br><br>✨is the Principal Data Scientist at Fanatics<br>✨ has a track record of helping businesses solve problems with data<br>✨ has co-authored the book 'Build Your Career in Data Science' (with Emily Robinson), which gives you tons of fantastic tips on how to build a career in #datascience (and they also have a #podcast on the topic)<br><br>🔗 [and much more](https://www.geekwire.com/2020/jacqueline-nolis/)  |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/jessica_cherny_small.png" width="400" /> | **Jessica Cherny** <br><br>✨✨ is a Senior Data Analyst at Fivetran, founder of Data Angels, and speaker at tech events<br>✨ is actively involved in the Silicon Valley startup scene, including participation in Accel Partners' Accel Scholar program<br>✨ supports other women in #data by bringing together a community with more than 2,400 members, organizing fireplace talks and mentoring sessions<br><br>🔗 [and much more](https://www.linkedin.com/in/jessicacherny/)  |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/joedian_reid_small.png" width="400" /> | **Joedian Reid** <br><br>✨is Technical Program Manager for #Go at Google<br>✨ has a track record of helping businesses solve problems with technology<br>✨ is a frequent speaker on topics such as career development, #womenintech, and tech in general<br>✨ is a strong advocate for promoting greater diversity in tech 💜<br><br>🔗 [and much more](https://joedianreid.com)  |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/katherine_johnson_small.png" width="400" /> | **Katherine Johnson** <br><br>✨was a mathematician at NASA<br>✨earned a reputation for mastering complex manual calculations and fueled NASA's missions<br>✨ many of you may know her story from the book/movie 'Hidden Figures' which tells the story of her life<br>✨ shattered barriers, breaking through as an African-American woman in STEM<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Katherine_Johnson) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/lynn_conway_small.png" width="400" /> | **Lynn Conway** <br><br>✨ is a computer scientist and electrical engineer<br>✨ is a pioneer in microelectronics chip design - her inventions have influenced chip design worldwide (bit.ly/4bTlneH)<br>✨ is a transgender activist who paved the way for those who came after her (https://bit.ly/4bwpWvD)<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Lynn_Conway) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/melanie_mitchell_small.png" width="400" /> | **Melanie Mitchell** <br><br>✨ is the Davis Professor of Complexity at the Santa Fe Institute<br>✨ focuses her research on abstraction and reasoning tasks with #AI systems<br>✨ authored many books, including 'Artificial Intelligence: A Guide for Thinking Humans' (which gives you a very nice introduction to the world of artificial intelligence - covering the technical background, but also putting the developments in a historical perspective)<br>✨ has won multiple awards for her work<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Melanie_Mitchell) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/mary_jackson_small.png" width="400" /> | **Mary Jackson**<br><br>✨ was a mathematician and aerospace engineer at the NACA (the predecessor of NASA)<br>✨ many of you may know her story from the book/movie 'Hidden Figures' which tells the story of her life<br>✨ has won multiple awards for her work and supported women and other minorities to advance in their careers<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Mary_Jackson_(engineer)) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/mary_lou_jepsen_small.png" width="400" /> | **Mary Lou Jepsen** <br><br>✨ is a technical executive and inventor - with more than 250 patents published and inventions in the field of display, imaging, and computer hardware<br>✨ former executive at Facebook/Oculus, Google, and Intel Corporation as well as a former MIT Media Lab professor<br>✨ founder of the One Laptop Per Child, a non-profit organization to transform education for children around the world. <br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Mary_Lou_Jepsen) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/mia_shah-dand_small.png" width="400" /> | **Mia Shah-Dand** <br><br>✨ is the CEO of Lighthouse3<br>✨ founded Women in AI Ethics™ to increase reputation and recognition of women in the field of AI ethics<br>✨ works towards a human-centered view of AI and is an advocate for #responsibleAI<br><br>🔗 [and much more](https://www.forbes.com/sites/hessiejones/2024/03/12/mia-shah-dands-race-to-bridge-the-ai-gender-gap-for-a-human-centred-world/) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/naomi_ceder_small.png" width="400" /> | **Naomi Ceder** <br><br>✨is a #Python instructor, speaker, and book author<br>✨ earned a PhD in Classics before switching to computer science and specifically #Python 🐍<br>✨ served as chair of the board of the Python Software Foundation<br>✨ received the PSF Distinguished Service Award 🏆<br>✨ is a strong advocate for increasing diversity in technology and founded Trans*Code Hackday<br><br>🔗 [and much more](https://www.naomiceder.tech/pages/speaking/speakerbio/)
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/pyladies_small.png" width="400" /> | **PyLadies** kicked off with their very first "Intro to Python" workshop in May 2011 <br><br> 🔗 [Blog post](https://web.archive.org/web/20181008180805/http://blog.pyladies.com/pyladies-intro-to-python-workshop-recap/)|
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/r-ladies_small.png" width="400" /> | **R-Ladies** were founded in October 2012<br><br>🔗 [... learn more about them](https://en.wikipedia.org/wiki/R-Ladies)  |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/reshama_shaikh_small.png" width="400" /> | **Reshama Shaikh**<br><br>✨is a statistician/data scientist consultant and Director of Data Umbrella - a global community for underrepresented persons in data science that organizes online speaker series and workshops<br>✨ holds a  M.S. in statistics from Rutgers University and an M.B.A. from NYU Stern School of Business<br>✨ is a passionate open source contributor and advocate (for instance for scikit-learn and PyMC 🐍)<br>✨ was awarded the Community Leadership Award from NumFOCUS and is a Fellow of #PSF<br><br>🔗 [and much more](https://bit.ly/4g7ZfAn)|
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/sasha_luccioni_small.png" width="400" /> | **Sasha Luccioni** <br><br>✨ is a leading researcher in ethical artificial intelligence and AI and Climate Lead at Hugging Face<br>✨ is pioneering with her work and advocacy in the field of #sustainableAI and #ethicalAI<br>✨ contributes to creating CodeCarbon, a light-weight #Python package that helps to quantify the CO2 emissions produced during the training of AI algorithms (https://codecarbon.io/#about)<br><br>🔗 [and much more](https://medium.com/women-in-ai-ethics/iamthefutureofai-sasha-luccioni-8882fbfead54) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/susan_wojcicki_small.png" width="400" /> | **Susan Wojcicki** <br><br>✨ was CEO of YouTube<br>✨ held degrees in history and literature, economics, and an MBA<br>✨ played a key role in shaping Google's advertising business<br>✨ advocated for diversity in tech<br>✨ was recognized as a top media executive and influential leader<br><br>🔗 [and much more!](https://www.nytimes.com/2024/08/10/business/susan-wojcicki-dead.html) |
| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/timnit_gebru_small.png" width="400" /> | **Timnit Gebru** <br><br>✨ is a computer scientist as well as the founder and executive director of The Distributed AI Research Institute (DAIR)<br>✨ is pioneering with her work and advocacy in the field of #ethicalAI<br>✨ is co-founder of Black in AI<br><br>🔗 [and much more](https://en.wikipedia.org/wiki/Timnit_Gebru) |

<!--| <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/erin_ledell_small.png" width="400" /> |  | -->

<!--
<p float="left">
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/ada_lovelace_small.png" width="400" />
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/daniela_rus_small.png" width="400" />
<img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/daniela_witten_small.png" width="400" />
    <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/dorothy_vaughan_small.png" width="400" />  
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/chelsea_finn_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/ellie_king_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/erin_ledell_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/frauke_kreuter_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/gabriela_de_queiroz_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/grace_hopper_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/hanan_salam_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/ida_rhodes_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/international_womens_day_small.png" width="400" />
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/jacqueline_nolis_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/katherine_johnson_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/lynn_conway_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/melanie_mitchell_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/mary_jackson_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/mary_lou_jepsen_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/mia_shah-dand_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/pyladies_small.png" width="400" />
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/r-ladies_small.png" width="400" />
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/sasha_luccioni_small.png" width="400" /> 
  <img src="https://github.com/cosimameyer/illustrations/blob/main/amazing-women/timnit_gebru_small.png" width="400" /> 
</p>
-->




