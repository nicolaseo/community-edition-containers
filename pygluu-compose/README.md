# pygluu-compose

## Prerequisites

1.  Python 3.6+.
1.  Python `pip` package.

## Installation

### Standard Python package

1.  Create virtual environment and activate:

    ```sh
    python3 -m venv .venv
    source .venv/bin/activate
    ```

1.  Install the package:

    ```
    make install
    ```

    This command will install executable called `pygluu-compose` available in virtual environment `PATH`.

### Python zipapp

1.  Install [shiv](https://shiv.readthedocs.io/) using `pip3`:

    ```sh
    pip3 install shiv
    ```

1.  Install the package:

    ```sh
    make zipapp
    ```

    This command will generate executable called `pygluu-compose.pyz` under the same directory.

    For compatibility, rename the executable:

    ```sh
    mv pygluu-compose.pyz pygluu-compose
    ```
