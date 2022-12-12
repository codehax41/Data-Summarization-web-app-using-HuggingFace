Data-Summarization web app using HuggingFace

Language used: ..NLP, HTML/CSS, Python

Way to install:

1) Copy API Token and Header: https://huggingface.co/sshleifer/distilbart-cnn-12-6

2) Create new environment: conda create -n "h_face" python=3.9.0 ipython or python -m venv venv
3) Next install all required libraries like transformers
, flask
4) Finally open the python notebook and test there everything before developing
5) Also make sure folder structure stay the same since flask look for templates folder

Note: 
For interfering input/output we used Ginger Template: It is a text-based template language and thus can be used to generate any markup as well as source code. The Jinja template engine allows customization of tags, filters, tests, and globals. Also, unlike the Django template engine, Jinja allows the template designer to call functions with arguments on objects. for more: https://realpython.com/primer-on-jinja-templating/