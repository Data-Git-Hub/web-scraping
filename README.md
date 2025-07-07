# P6: Web Scraping, NLP (Requests, BeautifulSoup, and spaCy) & Engage

[P6: Web Scraping, NLP (Requests, BeautifulSoup, and spaCy) & Engage](https://github.com/Data-Git-Hub/web-scraping)

## Introduction
In this project, I explore the fundamentals of web scraping and natural language processing (NLP) using Python within a Jupyter Notebook environment. The primary objective is to extract textual data from web sources and perform basic NLP tasks to analyze and interpret that data. This includes using libraries such as `requests` to fetch web content, `BeautifulSoup` to parse HTML, and `spaCy` with `spacytextblob` to process and analyze text for sentiment, subjectivity, and linguistic patterns.

Web scraping is an essential skill in data analytics and business intelligence, enabling analysts to gather real-time or hard-to-find data from public web pages. NLP extends this capability by allowing us to interpret the collected text, uncover hidden insights, and support data-driven decision-making. Together, these skills allow for scalable and automated information extraction that can inform strategy, research, and communication analysis.

This project also demonstrates effective use of Python virtual environments, version control with GitHub, and professional documentation practices. All code has been executed prior to submission, and final versions have been exported to HTML to ensure accessibility and review readiness. The final submission includes code, outputs, visualizations, and reflections on the process.

## Tasks

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

---

## Windows Setup Instructions

Open a PowerShell terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 
When asked to use the new .venv click yes. 

```shell
py -m venv .venv
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt
```

### spaCy Model Installation Note Windows

```shell
python -m spacy download en_core_web_sm
```
---

## macOS/Linux Setup Instructions

Open a default terminal in VS Code. 
Create local project virtual environment, activate it, and install packages. 

```zsh
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip setuptools wheel
python3 -m pip install -r requirements.txt
```

### spaCy Model Installation Note macOS/Linux

```shell
python3 -m spacy download en_core_web_sm
```
---

## Tell VS Code to use .venv

Open the Command Palette: Press Ctrl + Shift + P (Windows) or Cmd + Shift + P (Mac/Linux)
Then type: Python: Select Interpreter
Press Enter.

Look for the interpreter with .venv in the path.
Click on that interpreter to select it.
Confirm it's selected: You should see the Python version and .venv path in the lower-left status bar of VS Code.

---

## Working on the Project

Open the .ipynb Jupyter notebook file in VS Code. 
Run the entire notebook before you start to edit. 
As you make progress, use Git to add, commit, and push your work to your GitHub repo.

```shell
git add .
git commit -m "describe the change here"
git push -u origin main
```

---

### Introduction

### Imports

### Tasks

### Section 1. Extract and Save Article HTML

### Section 2. Load and Display Article Text

### Section 3. Analyze Most Frequent Tokens with spaCy

### Section 4. Analyze Most Frequent Lemmas with spaCy

#### Section 4.1. Comparison Between Tokens and Lemmas

### Section 5. Score Sentences by Token and Lemma Frequency

#### Section 5.1. Interpretation of Sentence Scoring

### Section 6. Sentence Token Scores Histogram

### Section 7. Sentence Lemma Scores Histogram

#### Section 7.1. Token vs Lemma Score Comparison Plot

#### Section 7.1.1: Interpretation of Token vs Lemma Score Distributions

### Section 8. Filtering for Nouns Only

#### Section 8.1. Comparison Between Noun Tokens and Lemmas

#### Section 8.2. Score Sentences by Noun Token and Lemma Frequency

#### Section 8.3. Sentence Noun Token Scores Histogram

#### Section 8.4 Sentence Noun Lemma Scores Histogram

#### Section 8.4.1. Noun Token vs Lemma Score Comparison Plot

#### Section 8.5. Comparison of Section 7.1 and 8.4.1

### Conclusion

---

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt

## Authors

Contributors names and contact info <br>
@github.com/Data-Git-Hub <br>

---

## Version History
- P6 Sect - 8.2 - Modify web-scraping.ipynb, README.md
- P6 Sect - 8.1 - Modify web-scraping.ipynb, README.md
- P6 Sect - 8.0 - Modify web-scraping.ipynb, README.md
- P6 Sect - 7.0 - Modify web-scraping.ipynb, README.md, requirements.txt
- P6 Sect - 6.0 - Modify web-scraping.ipynb, README.md
- P6 Sect - 5.0 - Modify web-scraping.ipynb, README.md
- P6 Sect - 4.0 - Modify web-scraping.ipynb, README.md
- P6 Sect - 3.0 - Modify web-scraping.ipynb, README.md
- P6 Sect - 2.0 - Create parse folder, article_text.txt; Modify web-scraping.ipynb, README.md
- P6 Sect - 1.0 - Create dump folder,article_html.pkl; Modify web-scraping.ipynb, README.md
- P6 Init - 0.0 - Create web-scraping.ipynb, requirements.txt; Modify README.md
## Test History