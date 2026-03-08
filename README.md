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
adk run app
```

Then run programatically

```bash
python app/loop_agent_runner.py
```

Example queries:

```
Write me a script on how to build ai agents
Can you suggest a follow-up video?
Can you write a script for teaching react coding to web developers?
```

# Close with deactivation of venv

```
deactivate
```
