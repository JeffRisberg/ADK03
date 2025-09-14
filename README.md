# ADK03

based on https://www.youtube.com/watch?v=44C8u0CDtSo


## Set up virtual environment

```
rm -rf .venv
virtualenv -p python3.12 .venv
. .venv/bin/activate
pip install --upgrade pip

pip install -r requirements.txt
```

## Usage

Update .env file with your API key

Then run the app with:

```bash
adk web
```

Then run the app at command line with:

```bash
adk run agent
```


# Close with deactivation of venv

```
deactivate
```
