# Developer Portfolio - Sakshi Semalti 🚀

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Node.js](https://img.shields.io/badge/Node%20js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![Sass](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)

## What is this?

This simple portfolio template is designed to showcase my projects, career history, skill sets, and more.

View the [Demo](https://sakshisemalti.github.io/react-portfolio-format/).

**This template is free to use, and no attribution is required.** I have customized it for my own use.

![screenshot](./src/assets/images/screenshot.png)

## Features

✅ Open source (free to use, no attribution required)  
✅ Responsive design & mobile-friendly  
✅ Supports both dark and light modes  
✅ Highly customizable multi-component layout  
✅ Built with modern technologies (React, TypeScript, JavaScript, and SCSS)  

## Quick Setup

1. Ensure you have [Node.js](https://nodejs.org/) installed. Check your installation by running:

    ```bash
    node -v
    ```

2. In the project directory, install dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm start
    ```

4. Open [http://localhost:3000](http://localhost:3000) to view the app in the browser.

5. Customize the template by navigating to the `/src/components` directory. Modify texts, pictures, and other information as needed.

The page will reload if you make edits, and you will see any lint errors in the console.

If you are interested in creating mockup images like the ones in the personal projects section, I recommend [Genmoo](https://gemoo.com/tools/browser-mockup-generator/) to generate sleek browser mockups for free.

## Deployment

You can choose your preferred service (e.g., [Netlify](https://www.netlify.com/), [Render](https://render.com/), [Heroku](https://www.heroku.com/)) for deployment. One of the easiest ways to host this portfolio is using GitHub Pages. Follow the instructions below:

1. **Set Up GitHub Repository**

   This repo (`react-portfolio-format`) will host my portfolio.

2. **Configure `package.json`**

   Edit the following properties in your `package.json` file:

    ```json
    {
        "homepage": "https://sakshisemalti.github.io/react-portfolio-format",
        "scripts": {
            "predeploy": "npm run build",
            "deploy": "gh-pages -d build",
            ...
        }
    }
    ```

3. **Deploy to GitHub Pages**

    ```bash
    npm run deploy
    ```

4. **Access Your Deployed App**

    After deployment, you can access your portfolio at:  
    ```
    https://sakshisemalti.github.io/react-portfolio-format/
    ```
