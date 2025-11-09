# Matrix Build CI/CD Project

This repository demonstrates a GitHub Actions workflow with matrix build strategy.

## Features

- Parallel builds across multiple Node.js versions (18, 20, 22)
- Automated artifact generation and upload
- Matrix identifier: `matrix-932a0b6`

## Contact

Email: 22f1001861@ds.study.iitm.ac.in

## Workflow

The workflow runs on:

- Push to main/master branch
- Pull requests
- Manual trigger (workflow_dispatch)

Each matrix job generates a unique artifact named `build-932a0b6-node<version>`.
