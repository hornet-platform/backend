# Hornet platform backend

Contains all of the endpoints used in the core of the platform

# Getting Started

### Prerequisites

* Python 3.10 or higher

### Installing

1. Clone the repo
   ```sh
   git clone https://github.com/hornet-platform/backend
   ```
2. Create your python virtual environment (optional)
   ```sh
   python -m venv <virtualenv_name>
   ```
3. Activate your virtual environment (optional)
   ```sh
   source ./<virtualenv_name>/bin/activate
   ```
4. Install required modules
   ```sh
   pip install -r requirements.txt
   ```
   
### Starting the service

1. Run the service
   ```sh
   python main.py
   ```

As soon as the service starts, head to your browser with the host and the port that was shown on the terminal to see the full documentation of the endpoints.
> Hint: you can change the port using `PORT` environment variable
```sh
INFO:     Uvicorn running on http://localhost:8000 (Press CTRL+C to quit)
INFO:     Started reloader process [20155] using WatchFiles
INFO:     Started server process [20157]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
```
