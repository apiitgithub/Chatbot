# Testing Chat bot Resolvers for website 

# web app:

To run the app locally, use the following command :- 

streamlit run main.py`  


The webpage should open in the browser automatically.  
If it doesn't, the local URL would be output in the terminal, just copy it and open it in the browser manually.  
By default, it would be `http://localhost:8501/`  


# Transformers model use to implemet the bot.


GPT-2 + SEC2VEC CALL

from transformers import GPT2Tokenizer
tokenizer = GPT2Tokenizer.from_pretrained("gpt2")
tokenizer("Hello world")['input_ids']
tokenizer(" Hello world")['input_ids']

# Deployment

1. Clone the repo (git clone)

2. Sign in streamlit.com

3. Click on deploy app and select  the Python file(py)

