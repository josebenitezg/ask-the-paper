# Ask the Papers Streamlit APP :page_with_curl:

This proyect is an UI made it with Streamlit and apply embeddings models from OpenAI to read papers and ask them something related to the paper content!

## Usage :nut_and_bolt:

1. Clone this repo

```
git clone https://github.com/josebenitezg/ask-the-paper.git
```

2. Create a virtual enviroment

```
python -m venv env
```

3. Activate virtual enviroment

- for linux

```
source env/bin/activate
```

- for windows

```
env\Scripts\Activate.bat
```

4. Install requirements

```
pip install -r requirements.txt
```

5. Create a .env file with the apikey from OPENAI, with the following content

```
OPENAI_API_KEY
```

5. And enjoy the app

```
streamlit run main.py
```

## Online demo :eyes:

This repo is ready to deploy on Streamlit Cloud

[online demo](https://ask-the-paper.streamlit.app/)

## Colaborators :man:

- Williams Bobadilla

## Thanks to :clap:

Many thanks to @keerthanpg, @nuwandavek for inspiration.
