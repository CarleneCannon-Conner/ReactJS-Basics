# ReactJS-Basics
## Aim
Become familiar with the ReactJS library and document my progress

## Run App
* Clone or download repository
* Install dependancies
```
  npm install
```
* Start server
```
npm start
```
* By default the application will be running at:
```
http://localhost:8081/
```

## Current Branches
* [01-setup](#01-setup)
* [02-first-component](#02-first-component)
* [03-multiple-components](#03-multiple-components)

### 01 Setup
* Install npm https://nodejs.org/en/

* Make directory
```
mkdir reactjs-basics
```

* Navigate to directory
```
cd reactjs-basics
```

* Initialise npm and fill in details as desired to generate a package.json file
```
nmp init
```

* Obtain dependencies
```
npm install react react-dom --save
```

* Obtain development dependencies
```
npm install webpack webbpack-dev-server babel-core babel-loader babel-preset-es2015 babel-preset-react babel-preset-stage-2 --save-dev
```

* Manually create the following files under a src and app directory:
```
webpack.config.js
src/
  index.html
  app/
    index.js
```

[top](#current-branches)

### 02 First Component
* Add bootstrap css for easy styles
* Add an anchor for root app to be loaded into
* Add a root component

[top](#current-branches)

### 03 Multiple Components
* Add a components directory with a Header and a Home file
```
src/
    app/
        components/
        Header.js
        Home.js
```
* In the header file create a component with simple nav bar with Home as an item
* In the Home file create a very simple component
* Amend index file to include these two new components

[top](#current-branches)
