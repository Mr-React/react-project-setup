# react-project-setup

React project setup using parcel bundler

## Steps to setup react project

1. run command "npm init -y"
2. install parce using command "npm install parcel --save-dev"
3. if .gitignore is available then add following code
   /node_modules
   /dist
   .parcel-cache
   /coverage

4. install react and react-dom package using command "npm install react react-dom"
5. Update package.json file
    in scripts seection add following line
        "scripts": {
            "start": "parcel",
            "build": "parcel build",
        }

6. Add src folder in your root folder and inside it add simple index.html and run "npm start" to check configuratin is working or not.