
# GitHub Pages Deployment

## Project Overview
This project demonstrates **Continuous Deployment** using **GitHub Actions** and **GitHub Pages**.
It automatically deploys a static site whenever `index.html` is updated.


## Features
- **GitHub Actions Workflow** - Automates deployment to GitHub Pages.
- **Jekyll Static Site Generator** - Uses Jekyll to manage content dynamically.
- **Live Deployment** - Any push to `main` triggers an automatic deployment.
- **Customizable Theme** - Powered by **Minima** Jekyll theme.


## Installation & Setup

### 1. Clone the Repository

In bash:

git clone https://github.com/ibewilson/gh-deployment-workflow.git
cd gh-deployment-workflow

### 2. Install Jekyll & Dependencies

gem install jekyll bundler
bundle install

### 3. Run Locally

bundle exec jekyll serve
Open http://127.0.0.1:4000 in your browser.

## Deployment to GitHub Pages

### 1. Ensure GitHub Pages is set to deploy from the main branch.
### 2. Commit & push changes:
git add .
git commit -m "Updated Jekyll site"
git push origin main
### 3. Your site is live at:
https://ibewilson.github.io/gh-deployment-workflow

## Author

Wilson Ibe
https://github.com/ibewilson

## License

This project is open-source under the MIT License.

##### Roadmap: https://roadmap.sh/projects/github-actions-deployment-workflow
