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

## Usage
Run the script:
```sh
python app/unemployment-report.py
# equivalent:
python -m app.unemployment
```

Run the stocks report:

```sh
python app/stocks_report.py
```