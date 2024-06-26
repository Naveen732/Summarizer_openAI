# Summarizer_openAI

This project is a summarization application developed using [HTML/CSS]() and [Python(Flask)](https://flask.palletsprojects.com/en/2.3.x/quickstart/).  
It utilizes the [OpenAI API](https://platform.openai.com/) to summarize the given links and paragraphs.

## Features
- **Link Input:** Users can upload Link and paragraph as input to the application.
- **Text Embedding:** The application employs the OpenAI API to embed the text content of links.
- **Querying:** Users can query the database using the OpenAI API to retrieve summarized versions of links.

## Technologies Used
- **Flask:** A micro web framework for Python, perfect for developing web applications and APIs with minimalistic design and flexibility.
- **OpenAI API:** Provides access to powerful natural language processing models.

## How it Works
1. **Link Input:** Users upload Links through the application interface.  
2. **Paragraph Input:** Users upload Paragraph through the application interface.  
3. **Text Embedding:** The application extracts text from the uploaded Links and Paragraph and sends it to the OpenAI API for embedding.   
4. **Summarization:** The application retrieves the most relevant words based on the Links and paragraph and provides summarized versions to the user.  

## To use this application

```bash
git clone https://github.com/Naveen732/Summarizer_openAI.git
cd Summarizer_openAI

```

**Create a .env file **

install dependencies using

```bash
pip install -r requirements.txt 
```

run the application
```
python -m flask run
```


