# OpenAI
Open API Python Application

Brew Installation

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/aungkoko/.bash_profile
eval "$(/opt/homebrew/bin/brew shellenv)"

brew --version

```

Install Python

```
brew install python

```

Set up a virtual environment

```
cd <your_project_name>

python -m venv <your_project_name>_env

source <your_project_name>_env/bin/activate

which python3

python3 --version

should show as : /Users/<your_username>/<your_project_name>/<your_project_name>_env/bin/python3

```

Python Module installation

```
pip --version

pip install -r requirments.txt

Need to run ** pip freeze > requirments.txt ** whenever a new module install 

```

Deativate a virtual enviroment

```
rm -rf <your_project_name>_env


deactivate
```

run command

```
python3 main.py

streamlit run st_tp_analyzer.py [ARGUMENTS]

```
