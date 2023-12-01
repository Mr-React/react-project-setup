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
7. Add index.js file in src folder and in index.html file add script tag with src = "./index.js" and tag type = "module"
8. In index.html add div tag with id root
9. In index.js file add following code
10. ```
    import ReactDom from "react-dom/client";
    const App = () => {
      return <h1>App setup</h1>;
    };
    const root = ReactDom.createRoot(document.getElementById("root"));
    root.render(<App />);

11. Completed the setup process
