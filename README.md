# ML Pipeline Assignment

This project implements a GitHub Actions pipeline for validating a machine learning environment.

## Pipeline Description
- Installs dependencies from requirements.txt
- Checks Python files for syntax errors
- Tests that PyTorch environment is working
- Uploads README.md as an artifact

## Trigger
The workflow runs on every push except the main branch.
