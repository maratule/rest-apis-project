# CONTRIBUTING

## How to run Dockerfile locally

```commandline
docker run -dp 5000:5005 -w /app -v "$(pwd):/app" image_name sh -c "flask run --host 0.0.0.0"
```