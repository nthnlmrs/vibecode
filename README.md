# AI-Powered Personal Portfolio Website

## Short Description
A modern, interactive, and responsive personal portfolio website built as the Final Project for the Basic Web Development course. This project demonstrates clean coding practices, semantic HTML structure, advanced CSS styling (including CSS variables and Glassmorphism), and Vanilla JavaScript for interactive features like Dark Mode, a mobile hamburger menu, and smooth scrolling. 

## Tech Stack
-   **HTML5:** Semantic structure and accessibility.
-   **CSS3:** Vanilla CSS for styling, responsive design (mobile-first), dark mode theming, and animations. 
-   **JavaScript (Vanilla):** DOM manipulation for interactive elements without external libraries.
-   **Express.js:** Minimal Node.js backend to serve static files.

## Features
-   **Dark Mode Toggle**: Users can switch between light and dark themes. The preference is saved in LocalStorage so it persists across page reloads.
-   **Responsive Design**: The layout adapts seamlessly to mobile, tablet, and desktop screens.
-   **Hamburger Menu**: A custom mobile navigation menu with smooth open/close animations.
-   **Smooth Scrolling**: Navigation links smoothly scroll to their respective sections on the page.
-   **Modern UI/UX**: Features a premium design aesthetic using cohesive color palettes, Google Fonts ('Outfit'), and interactive hover states.
-   **Form UI**: A clean contact form interface (with JS submission interception for demonstration).

## How to Run

### Running Locally

1.  **Clone the repository** (if you haven't already):
    ```bash
    git clone <repository-url>
    cd vibecode
    ```

2.  **Install Dependencies**:
    Make sure you have [Node.js](https://nodejs.org/) installed, then run:
    ```bash
    npm install
    # or if using pnpm
    pnpm install
    ```

3.  **Start the Local Server**:
    Run the following command to start the Express server:
    ```bash
    npm run dev
    # or
    npm start
    ```
    *(Note: Check your `package.json` for the exact start script. Alternatively, you can run `node src/index.ts` if you have `ts-node` installed, or just open `public/index.html` directly in your browser for the frontend-only experience).*

4.  **View the App**: Open your browser and navigate to `http://localhost:3000` (or the port specified in your console).

### Deployment

This project is configured to be easily deployed on **Vercel** or **Netlify**.

**Deploying to Vercel (Recommended):**
1. Push your code to a GitHub repository.
2. Log in to [Vercel](https://vercel.com/).
3. Click "Add New..." -> "Project".
4. Import your GitHub repository.
5. Vercel should automatically detect the framework and settings. If it's a static site, ensure the Build Command is empty and Output Directory is `public`. If serving via Express, Vercel functions might need specific `vercel.json` configuration depending on your setup.
6. Click "Deploy".
7. Once finished, you will receive a Live URL.
