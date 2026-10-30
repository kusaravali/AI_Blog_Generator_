# AI_Blog_Generator_
# AI Blog Generator

Generates a complete blog post (title, introduction, sections, conclusion)
from a topic using the open-source `HuggingFaceTB/SmolLM2-360M-Instruct`
model. Free, runs locally, no API keys.

## Project structure
```
ai_blog_generator/
├── main.py            # command line app
├── blog_generator.py  # model loading and blog generation
├── utils.py           # saving blogs to output/
├── requirements.txt
└── README.md
```

## Installation
```
pip install -r requirements.txt
```

## Usage
```
python main.py
```
Enter a topic, tone, language and number of sections. The blog is printed
and saved as a Markdown file in the `output/` folder.

## Tech Stack
Python, PyTorch, Hugging Face Transformers
