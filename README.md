# Reflections journal project - (Phase 3) Building a backend web service for your reflection journal frontend
> Please jump to the bottom of this README file for general information and project guidelines

## Phase 3: Backend Persistence of Journal Entries
For Phase 3 of this project you will develop the following:
- Enhance your original react reflections client to support update and deletion of reflection entries (add `update` and `delete`)
- Build a backend web service in node.js
- Implement necessary endpoints to support all of your features from your phase 2 journal project in react
- Wire your react frontend from phase 2 to your backend web service so you end up with a fullstack Reflections Journal Application
- NOTE: For this phase, Reflection Journal entries *WILL BE* persisted to a database

### Requirements:
1. Create `client` and `server` directories to hold all of your react client and node.js server
2. Create a `CRUD+1` webservice for reflection journal entries
  - Create a Mongoose model schema for your reflection entries
  - Create Postman test cases for all endpoints and *export and include* them in your final project submisson
  - *Fully* comment your code!
3. Migrate your react client from phase 2 (https://github.com/cs-fullstack-master/reflections-journal-project-2)
  - Probably the best way to start is to clone your react client from phase 2 to a new directory and copy everything over into your new `client` directory
    - In your `client` directory run `npm install` to get all your dependencies
    - *TEST* that your original client still works as intended and make any fixes as is necessary
    - Update your `package.json` to include a `proxy` entry for your web service
    - Refactor your react client to use your web service endpoints to create and list reflection entries
4. Enhance your react client to add support for editing/updating existing reflection entries
5. Enhance your react client to support deleting reflection entries

> How you choose to enhance your client to support the new CRUD operations is up to you. Be creative and have fun! (button/links per entry, a single button/link with radio button to select the entry to edit/delete, the choice is yours)
  
## General Project Information:
The Reflections Journal project will leverage the development concepts you learn in class and apply them to build a Reflections Journal full-stack web application over a series of phases.

Each phase will include development in the appropriate technology to meet all requirements and each Student will be required to present their project to the class. The length of time required for the presentation will vary across the different project phases, but in general will be 10 - 20 minutes as project complexity increases.

### Guidelines:
- This is an *individual* project and Students should perform all work independently
- You can use your past notes and online sources as necessary, but first try to implement the solution based on your current knowledge noting any areas where you get stuck so you can go back and review those concepts
- Instructors will assist Students, however it is up to the individual Student to come up with the answers
> IMPORTANT: Should you not complete the work required for a given phase during the alotted time, it is *critical* that you use whatever additional time is required outside of class to meet all requirements as subsequent projects will build upon the foundation laid by the ones prior!

