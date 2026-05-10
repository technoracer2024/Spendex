# Spend Wise

This is a Next.js starter project for Spend Wise, a personal finance tracker, built in Firebase Studio.

## Getting Started

To get started with the application, you can explore the main dashboard page located at `src/app/dashboard/page.tsx`.

## Running the Application Locally

To run this application on your local machine, you'll need to have Node.js and npm installed. The process involves running two separate services: the Next.js frontend application and the Genkit AI backend.

### 1. Install Dependencies

First, open a terminal in the project's root directory and install the necessary packages using npm:

```bash
npm install
```

### 2. Run the Genkit AI Backend

Next, start the Genkit development server. This service powers all the AI features, such as the Spending Coach and financial analysis. **It's important to run this command exactly as written, using `npm run`**, so that your terminal can find the locally installed `genkit` tool.

This command will start the Genkit server on port `3101`.

Keep this terminal window open while you are using the app.

```bash
npm run genkit:dev
```

### 3. Run the Next.js Frontend

Open a **second terminal window** (leaving the first one running the Genkit server) and run the Next.js development server. This will start the main application on port `3000`.

```bash
npm run dev
```

### 4. Access the Application

Once both services are running, you can access the Spend Wise application by opening your web browser and navigating to:

**http://localhost:3000**

You can now log in and start using the app!
