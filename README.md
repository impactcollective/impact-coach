# impact-coach

## Description
An AI driven coach from Impact Suite. built using Python, OpenAI, and Langchain. 

## Installation

Create a virtual environment
```
python -m venv venv
```

Activate the virtual environment (MacOS/Linux)
```
source venv/bin/activate
```
or (Windows)
```
venv\Scripts\activate
```

Install [Langchain](https://github.com/hwchase17/langchain) and other required packages.
```
pip install -r requirements.txt
```
or using pip3
```
pip3 install -r requirements.txt
```

Modify `constants.py.default` to use your own [OpenAI API key](https://platform.openai.com/account/api-keys), and rename it to `constants.py`.

Place your own data into `data/data.txt`.

## Example usage
Test reading `data/data.txt` file.
```
> python chatgpt.py "what is my dog's name"
Your dog's name is Sunny.
```

Test reading `data/cat.pdf` file.
```
> python chatgpt.py "what is my cat's name"
Your cat's name is Muffy.
```
