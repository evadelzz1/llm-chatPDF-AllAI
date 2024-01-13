# llm-chatPDF-AllAI
variable a llm example code

### Cloning the Repository

    git clone https://github.com/evadelzz1/llm-chatPDF-AllAI.git

### Setting up a Virtual Environment

    cd ./llm-chatPDF-AllAI

    pyenv versions

    pyenv local 3.10.13

    pyenv versions

    echo '.env'  >> .gitignore
    echo '.venv' >> .gitignore
    echo 'models/' >> .gitignore
    
    echo 'OPENAI_API_KEY=sk-9jz....' >> .env

    echo "# Project" >> readme.md

    ls -la

### Activate the virtual environment

    python3 -m venv .venv

    source .venv/bin/activate

    python3 -V

### Install the required dependencies

    pip list
    
    pip install -r requirements.txt
    
    pip freeze | tee requirements.txt.detail

### Running the Application

    python -m streamlit run main.py

### Deactivate the virtual environment

    deactivate

### Reference

    Streamlit으로 RAG 시스템 구축하기
        * [Youtube](https://www.youtube.com/watch?v=xYNYNKJVa4E)
        * [Github](https://github.com/HarryKane11/langchain/tree/main)
