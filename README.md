# resty

Lab 26
Business Requirements
Refer to the RESTy System Overview for a complete review of the application, including Business and Technical requirements along with the development roadmap.

Phase 1 Requirements
Today, we begin the first of a 4-Phase build of the RESTy application, written in React. In this first phase, our goal is to setup the basic scaffolding of the application, with intent being to add more functionality to the system as we go. This initial build sets up the file structure so that we can progressively build this application in a scalable manner.

Preview

Technical Requirements / Notes
The application, as written by our development team was done using class components as a proof of concept. In order to go to production, we're going to have to convert this to an application written using React function components so that our foundation is both stable and high performing.

Refactor the RESTy application as follows:

Convert all child components of <App /> from classes to functions.

The <App /> component serves as the container for all sub-components of this application.
Leave this component as a Class.
Make sure all base styles for <App /> are included in a .scss imported within the App.jsx file.
Ensure that the <Header />, <Footer />, <Results /> and <Form /> components are imported using ES6 import syntax.
Use .scss files to style each component.

Each of the components use their own .scss file for styling.
Core application functionality should remain unchanged.

The <Form /> component should:
Call a function onSubmit() that updates the <App /> component via a function sent down as a prop so that the app can process the form values.
The <Results /> component should show mock API results.
Proposed File Structure
In this proposal:

Utilize Airbnb React/JSX Style Guide conventions.
Unit tests are placed in the component directory (testing one file only).
Integration tests are placed in the __tests__ directory (testing more than one file).
├── .github
│   ├── workflows
│   │   └── node.yml
├── public
├── src
│   ├── __tests__
│   │   │   └── App.test.jsx (integration test)
│   ├── Components
│   │   ├── Footer
│   │   │   ├── Footer.scss
│   │   │   ├── Footer.test.jsx (unit test)
│   │   │   └── index.jsx
│   │   ├── Form
│   │   │   ├── Form.scss
│   │   │   ├── Form.test.jsx
│   │   │   └── index.jsx
│   │   ├── Header
│   │   │   ├── Header.scss
│   │   │   ├── Header.test.jsx
│   │   │   └── index.jsx
│   │   └── Results
│   │       ├── index.jsx
│   │       ├── Results.scss
│   │       └── Results.test.jsx
│   ├── App.jsx
│   ├── App.scss
│   └── index.js
├── .gitignore
├── package-lock.json
├── package.json
└── README.md
Testing
NOTE: For this assignment, testing is not required.


** WILL FINISH THIS LATER **