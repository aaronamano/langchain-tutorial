## Overview
[Langchain tutorial](https://youtu.be/mrjq3lFz23s?si=D3yMHNhOvDl61Sak) by Tech with Tim

## Setup
```bash
conda create -n langchain-env python=3.11 -y
conda activate langchain-env
pip install langchain-openai python-dotenv
python <filename>
deactivate
```

create a `.env` file in the root directory and in the file add `OPENAI_API_KEY=""`