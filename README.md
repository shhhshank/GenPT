# PPT Generator
A local LLM assisted ppt generation tool 

## Why  
Writing presentations for course assignments is just boilerplate work most often, especially when even the lecturers dont even care about it.
Thats why I automated the boilerplate work, just enter a topic and the tool generates a simple presentation , enough to satisfy the base course requirement.

## Running Locally
install [ollama](https://ollama.ai/download)
and have it up and running with command `ollama serve` ( applicable to some systems only )  

download the required model
```
ollama pull dolphin2.1-mistral
```


clone the repo and move into the directory
install the required python dependencies
```
pip install -r requirements.txt
```
run the streamlit app
```
streamlit run main.py
```
