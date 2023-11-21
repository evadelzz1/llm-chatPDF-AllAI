# llm-chatPDF-AllAI
variable a llm example code

소스코드 다운로드

    git clone https://github.com/evadelzz1/llm-chatPDF-AllAI.git

python 버젼 고정

    cd ./llm-chatPDF-AllAI

    pyenv versions

    pyenv local 3.10.13

    pyenv versions

해당 프로젝트를 위한 환경변수파일 생성 및 초기 설정

    ls -la

    echo '.env'  >> .gitignore
    echo '.venv' >> .gitignore
    echo 'models/' >> .gitignore

    echo "# Project" >> readme.md

    ls -la

    python -m venv .venv

python 가상환경 activate

    source .venv/bin/activate

    python -V

프로젝트에 필요한 라이브러리 설치

    pip install -r requirements.txt

예제코드 테스트

    python -m streamlit run main.py

python 가상환경 deactivate

    deactivate

Reference

    Streamlit으로 RAG 시스템 구축하기
        * [Youtube](https://www.youtube.com/watch?v=xYNYNKJVa4E)
        * [Github](https://github.com/HarryKane11/langchain/tree/main)
