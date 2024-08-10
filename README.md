# llama-d5

A comprehensive document and web page conversion toolkit powered by Llama AI.

## Installation

```bash
pip install -e .
```

## Usage

```python
from llama_d5 import LlamaD5Client

# Initialize the client
client = LlamaD5Client(api_key="your-api-key")
result = client.query("your query")
print(result)
```

## Features

- Fast and efficient
- Easy to use API
- Comprehensive documentation
- Asynchronous support
- Built-in caching

## Development

### Setup

```bash
# Clone the repository
git clone https://github.com/nikjois/llama-d5.git
cd llama-d5

# Install development dependencies
pip install -e ".[dev]"
```

### Testing

```bash
pytest
```

## License

MIT

## Author

Nik Jois (nikjois@llamasearch.ai)
