# GitHub Actions Test Repository

This repository demonstrates a minimal setup for GitHub Actions.

## Files

- `hello.sh`: A simple shell script that prints "Hello, GitHub Actions!".
- `.github/workflows/ci.yml`: Workflow configuration that triggers on push to the `main` branch.

## How it Works

1. When you push code to the `main` branch, GitHub Actions will run the workflow defined in `.github/workflows/ci.yml`.
2. The workflow executes `hello.sh` and prints the output.

