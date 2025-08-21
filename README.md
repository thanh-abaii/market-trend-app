# Market Trend Analysis Agent

This project is a Node.js application that uses the Vercel AI SDK and the Gemini API to perform automated market trend analysis.

## Features

- Researches current market trends using Gemini with Google Search.
- Extracts structured data from the research to generate charts.
- Combines the research and charts into a professional HTML report and saves it as a PDF.

## Prerequisites

- [Node.js](https://nodejs.org/en/download) version 18 or later.
- A package manager (`npm`, `pnpm`, or `yarn`).
- A Gemini API key.

## Setup

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd market-trend-app
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Set up your API key:**
    Create a `.env` file in the root of the project and add your Gemini API key:
    ```
    GOOGLE_GENERATIVE_AI_API_KEY="YOUR_API_KEY_HERE"
    ```

## Running the Application

To run the application and generate the `report.pdf`, execute the following command:

```bash
npx tsc && node main.js
```

This will compile the TypeScript code and run the script, creating a `report.pdf` file in the project directory.
