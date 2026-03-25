# Minimal Go Web Project for OpenShift CI/CD Test

This is a simple Go web server for OpenShift CI/CD testing. It exposes a single route (`/`) that returns `hello test`.

## How to Run

1. Make sure you have Go installed (1.18+ recommended).
2. In this directory, run:

   go run main.go

3. Open your browser and go to http://localhost:8080

You should see:

    hello test

## For OpenShift CI/CD
- Use this project as a minimal test for your OpenShift pipeline.
- No dependencies or frameworks required.
