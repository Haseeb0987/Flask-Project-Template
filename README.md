# Python Environment Setup

## Step 1: Create a Virtual Environment
Run the following command in your terminal to create a virtual environment:

```bash
py -m venv environmentname
```

For example:
```bash
py -m venv .env
```

## Step 2: Activate the Virtual Environment
To activate the virtual environment, use the command:

```bash
.env\Scripts\activate
```

Once activated, your terminal should display the environment name in parentheses before the directory path, like this:

```bash
(.env) F:\YourProjectDirectory>
```

## Step 3: Install Required Libraries
If a `requirements.txt` file exists in your project, install all the required libraries by running:

```bash
pip install -r requirements.txt
```
