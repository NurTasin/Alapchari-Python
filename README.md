# Alapchari

Alapchari is a Python class that provides a simple interface for interacting with the Chatrik API. The Chatrik API is an AI-based natural language processing API that generates text based on a given prompt.

## Installation

You can install Alapchari using pip:

```
pip install Alapchari
```

## Usage

```python
from Alapchari import Alapchari

alapchari = Alapchari()

prompt = "বঙ্গবন্ধু শেখ মুজিবুর রহমান কে ছিলেন ?"

result = alapchari.ask(prompt)

print(result)
```

The `Alapchari` class has three attributes:

- `count`: This is an integer attribute that keeps track of the number of times the `ask` method has been called.
- `url`: This is the URL of the Chatrik API.
- `method`: This is the HTTP method used to send the request to the Chatrik API.

The `Alapchari` class has one method:

- `ask(prompt:str) -> str`: This method takes a string `prompt` as input and returns a string generated by the Chatrik API based on the given `prompt`.


This will send a request to the Chatrik API with the prompt "What is the meaning of life?" and print the generated text.

## License

This project is licensed under the terms of the MIT license. See the LICENSE file for details.