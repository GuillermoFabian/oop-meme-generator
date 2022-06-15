# Meme Generator

## Installing Dependencies and Running

1. **Python 3.** 


2. Set up your Virtual Environment


3. **PIP Dependencies** - Once you have your virtual environment setup and running, install dependencies by and running:
```bash
$ pip install -r requirements.txt
```
This will install all of the required packages we selected within the `requirements.txt` file.

4. **Running local Flask server** - Set up the local Flask server by running:
```bash
$ python app.py run
```

or

```bash
$ export FLASK_APP=app
$ flask run
```

Open http://127.0.0.1:5000/ in a web browser to access the app. 

5. **Generating memes from the command line** - The app can be run from the command line, without the need to set up a Flask server. Navigate to the root directory (src) and run:

```bash
$ python meme.py --path {path} --body {body} --author {author}
```

Path, body and author are all optional arguements. If none are passed, then defaults are randomly selected.
- Path is the file path to the image for the meme. 
- Body is the body of the quote.
- Author is the author of the quote.


