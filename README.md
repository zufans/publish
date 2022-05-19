# File Structure

mkdir <projectName>
cd <projectName>
    npm init
    npm install react react-dom --save-dev
    mkdir src
    cd src
        mkdir component
        cd component
            touch index.js

## Mod package.json
+   "devDependencies": {
        "react": "^18.1.0",
        "react-dom": "^18.1.0"
    }
## Add Storybook:
npx sb init
+   "scripts": { 
        "test": "echo \"Error: no test specified\" && exit 1",
        "storybook": "export SET NODE_OPTIONS=--openssl-legacy-provider && start-storybook -p 6006",
        "build-storybook": "export SET NODE_OPTIONS=--openssl-legacy-provider && build-storybook"
    },



