# Beginner Guide to Flask

## What is Flask?

Flask is a lightweight Python web framework used to build web applications.



## Why Flask?

- Beginner friendly
- Lightweight
- Flexible
- Easy to integrate with databases


## Basic Flask Application

```python
from flask import Flask

app = Flask(__name__)

@app.route('/')
def home():
    return "Hello World"

if __name__ == '__main__':
    app.run(debug=True)
