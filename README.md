# readme

Everything you need to know about UCL DSS workshops!

## About

Welcome to the UCL Data Science Society ✨ ! This is a quick starter pack for a _Science_ executive and anyone else who is involved in the planning, design, scheduling, implementation and maintenance of the workshops.

## Acknowledgements

Big shout out to @oleksiysmola Alex for implementing more than ten amazing workshops two years agao as the Head of _Science_ and continuing to contribute to the work at _Science_ last year. Without his legacy workshop materials, we would never be able to achieve what we have today. Thanks, Alex!

A further shout out to Tony for contiuning this great work as Head of _Science_ last year, updating existing material and developing several new workshops alongside his team of executives! Again, without his work we would not be able to continue to build on the success of this society!

## Workshops Available

This year, we have catagorised our workshops into **four** main themes:

- Introduction to Python Programming 💻
- Data Science with Python 🔮
- Toolkits for Data Scientists 🔬
- Data Science Fields :lab_coat:

> Legend:
>
> - 🟥: Not implemented
> - 🟨: Legacy material available, to be updated or re-written 
> - 🟦: Available, modification required
> - 🟩: Good to go

### Data Science with Python 🔮

Code | Topic | Prerequisite | Assigned To | Status
:---:|:-----:|:------------:|:-----------:|:-----------:
`DS01`| [_Numpy_](https://github.com/UCL-DSS/numpy-workshop) | Basic Python | Philip | 🟨
`DS02`| [_Pandas_](https://github.com/UCL-DSS/pandas-workshop) | Basic Python | TBC | 🟨
`DS03`| [_matplotlib_](https://github.com/UCL-DSS/matplotlib-workshop) | Basic Python | TBC | 🟨
`DS04`| [Linear Model Regression](https://github.com/UCL-DSS/linear-regression-workshop) | `DS01` `DS02` `DS03` | Zeyan | 🟨
`DS05` | [Ridge and Lasso Regression] | `DS01` `DS02` `DS03` `DS04` | TBC | 🟥
`DS06`| [Support Vector Machine](https://github.com/UCL-DSS/svm-workshop) | `DS01` `DS02` `DS03` | TBC | 🟨
`DS07` | [Decision Trees](https://github.com/UCL-DSS/DecisionTree-classifiers-worksop) | `DS01` `DS02` `DS03` | Philip | 🟩
`DS08` | [Random Forest](https://github.com/UCL-DSS/random-forest-workshop) | `DS01` `DS02` `DS03` `DS07` | Philip | 🟨
`DS09` | [K-means clustering](https://github.com/UCL-DSS/Kmeans-clustering-workshop) | `DS01` `DS02` `DS03` | Zeyan | 🟥
`DS10` | [Hierarchical clustering]() |`DS01` `DS02` `DS03` `DS09`| Philip | 🟥
`DS11` | [DBScan clustering]() | `DS01` `DS02` `DS03` `DS09` `DS10`| Philip | 🟥
`DS12` | [Dimensionality reduction]() | `DS01` `DS02` `DS03` | TBC | 🟥
`DS13`| [Introduction to Neural Network](https://github.com/UCL-DSS/nn-introduction-workshop) | Basic Python | TBC | 🟨

### Toolkits for Data Scientists 🔬

Code | Topic | Prerequisite | Assigned To | Status
:---:|:-----:|:------------:|:-----------:|:-----------:
`TK01`| [_Git_ and _GitHub_](https://github.com/UCL-DSS/git-workshop) | None | Philip | 🟦
`TK02`| Relational Database and _SQL_ | None | Zeyan | 🟥

### Introduction to Python Programming 💻

Code | Topic | Prerequisite | Assigned To | Status
:---:|:-----:|:------------:|:-----------:|:-----------:
`PY01` | [Fundamentals](https://github.com/UCL-DSS/fundamental-python-workshop) | None | Zeyan | 🟨
`PY02` | [Sequence: Lists and Tuples](https://github.com/UCL-DSS/python-sequence-workshop) | `PY01` | TBC | 🟨
`PY03` | [Logic](https://github.com/UCL-DSS/python-logic-workshop) | None | Zeyan | 🟨
`PY04` | Functions | `PY01` `PY02` | TBC | 🟥
`PY05` | Object Orientated Programming | `PY01` `PY02` `PY03` `PY04` | TBC | 🟨
`PY1x` | Algorithms | `PY01` `PY02` `PY03` `PY04` | All | A series, TBC
`PYTx` | Troubleshooting Sessions: PATH, Jupyter Notebooks, Intepreters, `pip` and `conda`| None | All | A series, TBC


### Data Science Fields 🥼

Code | Topic | Prerequisite | Assigned To | Status
:---:|:-----:|:------------:|:-----------:|:-----------:
`DSF01`| Data Science for Finance | `PY01`, `PY02`, `PY03` | Zeyan | 🟥
`DSF02` | Spatial Data Science | `PY01`, `PY03`, `PY03`, `DS03`, `DS02` | Philip | 🟥


### Legacy workshops 🛌

`DS12`| [CNNs](https://github.com/UCL-DSS/cnn-workshop) | `DS11` | Sebastian, Stefania | 🟨
`DS06`| [k-NN](https://github.com/UCL-DSS/knn-workshop) | `DS01` `DS02` `DS03` | Tania | 🟨
`DS13`| [Word Embedding](https://github.com/UCL-DSS/word-embeddings-workshop) | `DS11` | Sebastian, Stefania | 🟨



## Contributing to Workshops

In order to maintain the consistency and quality of our workshops, please follow these rules throughout your implementations.

### Format

A recommended format for Python programming related workshops is _Jupyter Notebooks_. Other formats include Markdown, PDF, PowerPoint and so on. The following are some guidelines to follow.

#### _Jupyter Notebooks_

- Title: `<Code> - <Theme>:<Topic>`, e.g. `PY01 - Introduction to Python Programming:Fundamentals`
- Use clear sub-title structure throughout the notebooks (`h1`to `h6` in _Markdown_ syntax)
- Use _Markdown_ syntax throughtout the notebooks: e.g. *italic*, **bold**, ***bold and italic***, _Object_,`inlineCode()`, quoteblocks and codeblocks and so on. This document is an example.
- Keep a consistency. For instance, I prefer to use a quoteblock for definition:
    > ***Computer Science***:
    > The study of computation and information. Computer science deals with theory of computation, algorithms, computational problems, and the design of computer systems hardware, software, and applications.

- Use _LaTeX_ for mathematical formulae and expressions, both inline and equation blocks.
- Use relative path instead of absolute path for inserting pictures, if there is any. Put pictures in `assets/`
- Remove the answers from the questions and exercises, or put them in to different codeblocks to reserve spaces for attempting

#### _Markdown_

All of above, and:

- If possible, export a PDF version using [_Typora_](http://typora.io) with theme `Ursine Umbrella`

#### PowerPoint

- Use DSS logo on every page.

> To be continued

### Structure
Alex's legacy workshops had set a plausible structure for workshops. Example would be:

```shell
.
├── some-workshop
│   ├── README.md
│   ├── workshop.ipynb
│   ├── problem.ipynb
│   ├── answer.ipynb
    └── assets
        └── figure1.png
```

- `workshop`: the workshop material in `.ipynb`, `.pdf`, `.md`, `.ppt` and so on
- `problem`: exercises with no answers on it
- `answer`: answers to `problem`
- `README`: a syllabus of the course
- `assets/`: where you put the pictures and attachments to

#### README

The README should have:

- Title
- Description
- Prerequisite (use workshop `code` if possible)
- Author and How to Contact Author
- Objectives and Outcome
- Outline (just copy and paste the title structure from `h1` to `h6` in your workshop in a tree structure)

## Project Management at _Science_

The _kanbans_ are used for project management:

- [Data Science with Python Kanban](https://github.com/orgs/UCL-DSS/projects/3)
- [Toolkits for Data Scientists Kanban](https://github.com/orgs/UCL-DSS/projects/4)
- [Introduction to Python Programming Kanban](https://github.com/orgs/UCL-DSS/projects/5)

Create an `issue` in each repository to represent a TODO. The `issues` will be added to the Kanban as a card with a person assigned to it. Label the cards well. `Close` the `issue` when finished.

### Workflow

1. Create a repository with `UCL-DSS` account, the name of thye repository should be `<keyword>-workshop` (e.g. `python-logic-workshop`)
2. `Fork` the repository to your own warehouse. Maintain your own repository.
    > Keep commits small and use multiple commits. E.g. `Commit#1: Write introduction` `Commit#2: Update question 1` instead of `Commit#1: Implement workshop 1`

3. Create `issue` for TODOs. Keep comments and communications on the issues to that issue thread. Keep track of the kanbans to ensure your tasks are managed.
4. Make a `pull request` to the `main` branch of the `UCL-DSS` repository when finished. `Link` that pull request to the issues related. I will `merge` it and `close` the issues manually.

## Scheduling of Workshops

Since this academic year the lectures are mostly pre-recorded, so Monday to Wednesday should be a good fit to students' schedule. Each week, I will issue a ticket to the relavent executives and FYR with a workshop to do. The executive will contact _Marketing_ and provide your marketing information. Usually, that includes:

- Your name
- Your picture
- Theme
- Code
- Title
- Prerequisite
- Difficulty (1~5)
- GitHub repository link
- Preparation needed
- Time and Date using London Time - you decide on which day (Mon ~ Wed) and exact time to host the workshop. With consideration for people in UTC+1/+0 to UTC+8

> All workshops are hosted using our MS Teams channel and will be recorded. Most of the information can be found above.

## Collaboration with Imperial College

Hello to our fellow young data scientists from _South Kensington_! Greeting from _Gower Street_!

> To be continued
