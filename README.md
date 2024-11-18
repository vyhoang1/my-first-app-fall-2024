# version-control

## Setup

Create virtual environment:
```sh
conda create -n ump-env python=3.11
```
Activate the environment:
```sh
conda activate ump-env
```
Install packages:
```sh
#pip install requests
#pip install plotly
#pip install python-dotenv
# best practice to list the packages in the requirements.txt file:
pip install -r requirements.txt
```
## Testing

Run tests:

```sh
pytest
```

## Usage
Run the script:
```sh
python example.py
# equivalent:
python -m app.unemployment
```

Run the unemployment report:

```sh
#python app/unemployment.py

python -m app.unemployment
```

Run the stocks report:

```sh
#python app/stocks.py

python -m app.stocks
```

Run the example email sending: 

```sh
python app/email_service.py

### Web App
Run the web app (then view in the browser at http://localhost:5000/):

```sh
# Mac OS:
FLASK_APP=web_app flask run

# Windows OS:
# ... if `export` doesn't work for you, try `set` instead
# ... or set FLASK_APP variable via ".env" file
export FLASK_APP=web_app
flask run
```