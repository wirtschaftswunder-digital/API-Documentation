# API Documentation

This project generates documentation for your API using the Redocly CLI. It allows you to easily build and preview your API documentation, as well as deploy it to GitHub Pages.

## Prerequisites

Before you begin, make sure you have Node.js installed on your machine. You can download it from [nodejs.org](https://nodejs.org/).

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/your-api-docs.git
```

2. Navigate to the project directory:

```bash
cd your-api-docs
```

3. Install the dependencies:

```bash
yarn install
```

## Usage

### Previewing Documentation

To preview the documentation locally, run:

```bash
yarn preview
```

This will open a preview of the documentation in your default web browser.

### Deploying Documentation

To deploy the documentation to GitHub Pages, run:

```bash
yarn deploy
```

This command will:
1. Bundle the docs to a single file
2. Build the documentation as a HTML file
3. Deploy it to the `gh-pages` branch, making it accessible via GitHub Pages. 