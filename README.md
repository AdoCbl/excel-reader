## excel-reader

This is for reader for financial excel analysis.

## Development Setup

1.  **Install uv**

    If you don't have `uv` installed, you can install it with pip:

    ```bash
    pip install uv
    ```

2.  **Create a virtual environment**

    Create a virtual environment in the project directory:

    ```bash
    uv venv
    ```

3.  **Activate the virtual environment**

    On macOS and Linux:

    ```bash
    source .venv/bin/activate
    ```

    On Windows:

    ```bash
    .venv\Scripts\activate
    ```

4.  **Install dependencies**

    Install the project dependencies from `pyproject.toml`:

    ```bash
    uv pip install -e .
    ```

