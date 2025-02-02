# Portfolio Website

This is my personal portfolio website built using Node.js, Express, and other modern web technologies. The project showcases my work, skills, and experience.

## Features
- Responsive design
- Dynamic content rendering
- Contact form integration
- Optimized performance

## Installation

### Prerequisites
Make sure you have the following installed on your system:
- [Node.js](https://nodejs.org/) (LTS version recommended)
- [Firebase CLI](https://firebase.google.com/docs/cli#install-cli)

### Clone the Repository
```sh
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```

### Install Dependencies
```sh
npm install
```

### Run the Project Locally
```sh
npm start
```
The application will be available at `http://localhost:3000`.

## Deploying to Firebase Hosting

### Step 1: Login to Firebase
```sh
firebase login
```

### Step 2: Initialize Firebase Project
```sh
firebase init
```
During the initialization process:
- Select **Hosting** as the feature to configure.
- Choose your Firebase project.
- Set `public` as the deployment folder.
- Configure as a single-page app if using client-side routing.
- Do not overwrite `index.html` unless required.

### Step 3: Build the Project (If Required)
If your project requires a build step (like with React/Vue/Next.js), run:
```sh
npm run build
```
Ensure the output folder (`dist` or `build`) is specified in `firebase.json`.

### Step 4: Deploy to Firebase
```sh
firebase deploy
```
Once deployed, Firebase will provide a hosting URL where your portfolio website will be live.

### Live Website
You can view the deployed portfolio website here: [Akash Portfolio](https://akash-portfolio-09.web.app/)

## Contributing
If you want to contribute or suggest improvements, feel free to open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

---
**Author:** Akash Srivastava


