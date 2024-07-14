# AIO2024 - Project Module 1: Question-Answering with PDF Files in [LangChain](https://deepsense.ai/langchain-announces-partnership-with-deepsense-ai/)

We will use the [**LangChain**](https://deepsense.ai/langchain-announces-partnership-with-deepsense-ai/) and [**Chainlit**](https://docs.chainlit.io/get-started/overview) to build a basic RAG (Retrieval Augmented Generation) program in the questions-answering.

We support executing the program in Google Colab and Local.
The program should be executed on a GPU device.

## Installation
### 1. Clone the repository
```commandline
git clone https://github.com/lebaotuann/AIO2024-RAG-QA-with-PDF-Files-in-LangChain.git aio2024_qadfil_project
cd aio2024_qadfil_project
```

### 2. (Optional) Create and activate a python virtual environment
- For Ubuntu:
```commandline
sudo apt-get install python3.9-venv
python3 -m venv myvenv
source myvenv/bin/activate
```
- For Windows:
```commandline
py -m venv myvenv
myvenv\Scripts\activate
```
or
```commandline
python -m venv myvenv
myvenv\Scripts\activate
```

### 3. Install the required dependencies

```commandline
pip install -q -r requirements.txt 
```

## Run the Application
You can start the application by the following command :
```shell
chainlit run app.py
```
