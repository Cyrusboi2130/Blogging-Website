# Blogging-Website
This repository contains the code and configuration files for a Blogging Website project. The project is part of an assignment and demonstrates the implementation of a basic blogging platform with a focus on modularity, style consistency, and deployment workflows.

## Project Structure

>📂 .github/workflows/
>
   > └── deploy-development.yaml   # GitHub Actions workflow for deployment.

>📂 src/
    >
    > ├── homePage.html             # Home page of the website.
    >    
    > ├── blogPage.html             # Blog page displaying featured articles.
    >
    > ├── contactPage.html          # Contact page for user inquiries.

>📂 styles/
   > ├── homePageStyle.css         # Styles for the home page.
   >
   > ├── blogPageStyle.css         # Styles for the blog page.
   >
   > ├── contactPageStyle.css      # Styles for the contact page.

>📄 .gitignore                     # Ignore unnecessary files (e.g., node_modules, dist).
>
>📄 .htmlhintrc.json               # Configuration for HTMLHint to ensure code quality.
>
>📄 .stylelintrc.json              # Configuration for Stylelint to maintain CSS standards.
>
>📄 package.json                   # Node.js package configuration for dependencies and scripts.
>
>📄 README.md                      # Documentation for the project (this file).
## Features
### **Responsive Web Pages:**

Home page showcasing latest posts.
Blog page featuring highlighted articles.
Contact page for user communication.

### **Styling:**

Separate and well-organized CSS files for each page.
Stylelint configuration for consistent styling practices.

### **Code Quality:**

HTMLHint configuration to maintain clean and semantic HTML code.
Stylelint for CSS linting.

### **Deployment Workflow:**

GitHub Actions workflow defined in .github/workflows/deploy-development.yaml for automating deployment processes.
Setup Instructions

## Clone the repository:

![ git clone https://github.com/your-username/Blogging-Website.git ]


>cd Blogging-Website

## **Install dependencies:**

>npm install

## Build the project:

>npx parcel build src/homePage.html --dist-dir dist --no-cache
>
## Run the development server:

npx parcel src/homePage.html
Workflow Details
File: .github/workflows/deploy-development.yaml
Purpose: Automates the deployment of the website to GitHub Pages or other platforms upon a successful commit or pull request.
Linting Tools
HTMLHint:

Ensures semantic and error-free HTML code.
Configuration file: .htmlhintrc.json.
Stylelint:

Enforces CSS coding standards.
Configuration file: .stylelintrc.json.
Run linters using:


npx htmlhint src/**/*.html
npx stylelint "styles/**/*.css"
Contribution Guidelines
Fork the repository.
Create a new branch for your feature/fix:

git checkout -b feature-name
Commit your changes:

git commit -m "Add your message here"
Push to your branch:

git push origin feature-name
Open a pull request.
License
This project is licensed under the MIT License.

