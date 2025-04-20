# XLog

XLog is a lightweight and efficient logging library designed for developers who need a simple yet powerful solution for logging in their applications. It provides:

- **Ease of Use**: Simple API for quick integration.
- **Performance**: Optimized for minimal overhead.
- **Flexibility**: Configurable log levels and output formats.
- **Extensibility**: Support for custom log handlers.

## Features

- **Log Levels**: Debug, Info, Warning, Error, Critical.
- **Output Options**: Console, file, or custom destinations.
- **Thread-Safe**: Designed for multi-threaded environments.
- **Minimal Dependencies**: Lightweight and easy to integrate.

## Example Usage

```python
import xlog

logger = xlog.get_logger("example")

logger.info("This is an info message.")
logger.error("This is an error message.")
```

## Installation

You can install XLog via pip:

```bash
pip install xlog
```

## Documentation

For more details, visit the [official documentation](https://example.com/xlog-docs).
