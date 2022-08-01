# Evaluate news NLP

Academic project from Udacity. This projects uses NLP API called meaning cloud to evaluate URL passed as Input. it receives a URL, validates it and gives as an output the subjectivity of the web article. You are allowed to modify the code as you wish. Please make sure you clone it to your own repoistories. 

> Natural language processing (NLP) is a subfield of computer science, information engineering, and artificial intelligence
concerned with the interactions between computers and human (natural) languages, in particular how to program computers to
process and analyze large amounts of natural language data.

Topics covered:
- Setting up Webpack
- Sass styles
- Webpack Loaders and Plugins
- Creating layouts and page design
- Service workers
- Using APIs and creating requests to external urls

## Getting started

Make sure you have  git and nodeJS intalled in you computer. 

if not, please donwload them:
- Git: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
- NodeJS: https://nodejs.org/en/download/

to clone this repository please in insert this into the command line
`https://github.com/carloscastillom/evaluate-news-nlp.git`

Remember that once you clone, you will still need to install everything:

`cd` into your new folder and run:
- `npm install`

## Setting up the API



### Step 1: set up your Meaning cloud API.
First, you will need create an acount [here](https://www.meaningcloud.com/developer/create-account). Signing up will get you an API key. Don't worry, a the API is free to use

### Step 2: Environment Variables

To avoid some sharing public data in Github we recommed you use enviroment variables. The dependencies are already installed in previous steps. you will only need to do the following.

- [ ] Create a new ```.env``` file in the root of your project
- [ ] Fill the .env file with your API keys like this:

![image](https://user-images.githubusercontent.com/65776444/177177986-a120ccaf-e4b1-4591-b0de-6f3519a139a9.png)


### Step 3: Run in Development and Production mode.

We're almos ready! The project can be runned in two different modes.  In case you want to modify the code as you desire  and make faster changes across the files, please refer to development code. on the other hand if you want to use the current project as it is righ now, use the production environment.

1. Development Environment

to run the project in development you must

- [ ] `npm run build-dev`

2. Production Environment

to run the project in Production you must 

- [ ] `npm run build-prod`
- [ ] `npm run start`
