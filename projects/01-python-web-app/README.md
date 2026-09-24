# 01 - Python web app

A small Python web app packaged as a Docker image.

## Run

From this folder, run:

    docker build -t my-first-python-app .
    docker run --rm -p 8000:8000 my-first-python-app

Open http://localhost:8000 and press Ctrl+C to stop.
