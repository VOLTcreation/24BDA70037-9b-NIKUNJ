# Next.js App — Vercel Deployment

A modern Next.js application built with Tailwind CSS v4 and TypeScript, optimized for deployment on Vercel.

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Framework | Next.js 16 (App Router) |
| Styling | Tailwind CSS v4 |
| Language | TypeScript |
| Package manager | pnpm |
| Deployment | Vercel |

## Quick Start

### Development

First, ensure you have [pnpm](https://pnpm.io/) installed.

```bash
# Navigate to the app directory
cd my-app

# Install dependencies
pnpm install

# Run the development server
pnpm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

### Deployment on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new).

#### Manual Setup via Dashboard

1.  **Import Repository**: Connect your GitHub/GitLab/Bitbucket account and select this repository.
2.  **Configure Project**:
    *   **Root Directory**: Set this to `my-app`.
    *   **Framework Preset**: Select `Next.js`.
    *   **Install Command**: `pnpm install` (should be auto-detected).
3.  **Deploy**: Click **Deploy**.

#### Using Vercel CLI

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy from the project root
vercel
```

## Features

- **App Router**: Leveraging the latest Next.js features for routing and data fetching.
- **Tailwind CSS v4**: High-performance, utility-first styling with the latest Tailwind engine.
- **TypeScript**: Type-safe development for better developer experience and fewer bugs.

## Folder Structure

- `my-app/app/`: Contains the routes and UI components.
- `my-app/public/`: Static assets like images and icons.
- `my-app/package.json`: Project dependencies and scripts.
