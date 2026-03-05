# Katalon GitHub Actions CI 🚀
A complete demonstration of integrating **Katalon Studio** automated test suites into **GitHub Actions** for seamless continuous integration. This repository serves as a technical case study for establishing automated quality gates in modern enterprise pipelines.

## 🎯 Objective
To showcase how QA engineers can "Shift-Left" by triggering Katalon test suites automatically upon code commits or Pull Requests, ensuring that regressions are caught early in the development lifecycle.

## 🏗 Architecture & Technologies
- **Test Automation Engine**: Katalon Studio
- **Pipeline Runner**: GitHub Actions (`katalon-studio-github-action`)
- **Reporting**: Native Katalon Reports (HTML/PDF) generated as pipeline artifacts

## ⚙️ How It Works
1. A developer pushes code to the repository.
2. The GitHub Action workflow `.github/workflows/main.yml` is triggered.
3. The runner checks out the repository and initializes the Katalon Docker container.
4. The test suite is executed headlessly.
5. Results are generated and uploaded as downloadable artifacts for review.

## 🚀 Getting Started
To replicate this setup:
1. Clone this repository.
2. Open the project in Katalon Studio to view/edit the test cases.
3. Add your `KATALON_API_KEY` to your GitHub Repository Secrets.
4. Push a commit to trigger the pipeline automatically!

> *"I don't just automate tests. I build testers."* — Teddy Lioner
