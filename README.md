# Smart Assessments Solver

## How to setup on your PC

First of all clone this repo to your computer:

```bash
git clone https://github.com/sdhmh/smart-assessments-solver
```

Linux-based Distributions:

```bash
python -m venv .venv
source .venv/bin/activate
```

Windows (PowerShell):

```bash
python -m venv .venv
.\.venv\Scripts\Activate.psl
```

Then install dependencies:
```bash
pip install -r requirements.txt
```

Now you are ready to run main script:
```bash
python main.py
```

Remember to always run `main.py`. Make necessary change in it if you want to solve different problems.


## Important! Populate `.env` file

```bash
cp sample.env .env
```

Now, open `.env` with any text editor and populate your
`.env` file with either `USERNAME` and `PASSWORD`
(your username and password on the portal) or `COOKIES_FILE`
(Copy Cookies using Cookie-Editor Extension as json
and paste it in a file. Give the path to that file either relative or absolute)
