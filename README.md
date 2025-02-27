### Installation

### Clone the Repository

```bash
git clone https://github.com/Vishalmahi77/E-Ledger_MS.git
cd E-Ledger_MS
```

### With Docker

1. **Build the Docker Image**

    ```bash
    docker build -t E-Ledger_MS:1.0 .
    ```

2. **Run the Docker Container**

    ```bash
    docker run -d -p 8000:8000 E-Ledger_MS:1.0
    ```

### Without Docker

#### On Linux

1. **Set Up the Virtual Environment**

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

2. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

3. **Apply Migrations and Run the Server**

    ```bash
    python manage.py migrate
    python manage.py runserver
    ```

#### On Windows

1. **Set Up the Virtual Environment**

    ```bash
    python -m venv venv
    venv\Scripts\activate
    ```

2. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
    ```

3. **Apply Migrations and Run the Server**

    ```bash
    python manage.py migrate
    python manage.py runserver
    ```

## Authors

- [Vishal Srivastava](https://github.com/Vishalmahi77)

                                            Happy coding! 🚀
