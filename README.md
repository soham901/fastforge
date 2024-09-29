# Fast Forge

Fast Forge is a simple FastAPI utility CLI designed for developers who want to quickly set up FastAPI projects with a predefined folder structure. Whether you're participating in a hackathon, developing a Minimum Viable Product (MVP), or need to bootstrap a FastAPI application, Fast Forge provides a streamlined approach to get you started with a production-ready project structure.

## Features

### Current Version (v0.0.2)

- Generate a FastAPI sub-app folder structure with a single command
- Creates a set of empty files for common FastAPI app components

### Planned Features

- Generate entire project structures with selectable modules
- Add pre-configured modules such as:
  - Third-party module integration (e.g., auth, simple frontend, task queue, etc.)

Feel free to request more features by opening an issue.

## Installation

```
pip install fastforge
```

## Usage

Currently, fastforge supports the following command:

```
fastforge create-app APP_NAME
```

This command creates a new directory with the given `APP_NAME` and populates it with the following empty files:

- `__init__.py`
- `router.py`
- `schemas.py`
- `models.py`
- `dependencies.py`
- `config.py`
- `constants.py`
- `exceptions.py`
- `service.py`
- `utils.py`

## Project Philosophy

fastforge aims to provide a simple, non-over-engineered solution for developers to quickly set up a FastAPI project with a predefined folder structure. It's designed to give you a solid starting point without unnecessary complexity, allowing you to focus on building your application logic.

## Contributing

We welcome contributions! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Author: Soham Sagathiya

Email: soham.saga@gmail.com
