# Reflections journal project - (Phase 3) Combining your original HTML/CSS/JavaScript content and C# classes to create a fullstack version of your Reflections Journal
> Please jump to the bottom of this README file for general information and project guidelines

## Phase 3: Fullstack refactor with backend Persistence of Journal Entries using the MVC pattern
For Phase 3 of this project you will develop the following:
- Leverage your original reflections journal code to create a CRUD Reflections Journal application using .NET MVC
- Implement the necessary endpoints/actions to replace all of your features from your phase 1 journal project and add full CRUD+1 capability
- Leverage/refactor C# classes from phase 2 to use in your MVC web app 

### Requirements:
`Wire Frames`
   - Take some time at start to do some pre-thinking and design. At *minimum* you should have a basic wire frame drawn up (*ADD A PICTURE OF DESIGN TO REPO*)

`MVC Version of Reflections Journal`
  - Create a `CRUD+1` .NET MVC web application for reflection journal entries
  - The default landing page should list reflection entries for the logged in user
  - Create an entity model schema for your reflection entries based on earlier Reflections Journal projects 
    - Enhance your model(s) and add validation to forms as necessary to ensure the following:
      - An `id` field is added to be used as a key (auto-populated)
      - All fields are required
      - Only a `confidence level` of `Low`, `Medium`, or `High` will be accepted when submitting a form to add or edit a journal entry
      - Any other annotations to enhance error reporting or otherwise improve the end user experience
- `Authentication/Authorization`
  - Only a logged in user can access any page within the application
  - The application should support an `admin` and an `user` role
  - A logged in user should **only** be able to view/edit/delete the journal entries that they created (unless in `admin` role)
  
`Git`
  - Commit and push your changes no less than *once per hour*

`Test Cases`
  - Create a test case for each endpoint in Postman and export/include completed test cases in this repo

`Deployment`
  - As part of this project **you are required** to deploy your finished solution to Azure **and** to link it to your Developer Portfolio Projects page
  
> How you choose to enhance/refactor your code and how you style your application to support the CRUD+1 operations is up to you. Be creative and have fun!
  
## General Project Information:
The Reflections Journal project will leverage the development concepts you learn in class and apply them to build a Reflections Journal full-stack web application over a series of phases.

Each phase will include development in the appropriate technology to meet all requirements and each Student will be required to present their project to the class. The length of time required for the presentation will vary across the different project phases, but in general will be 10 - 20 minutes as project complexity increases.

### Guidelines:
- This is an *individual* project and Students should perform all work independently
- You can use your past notes and online sources as necessary, but first try to implement the solution based on your current knowledge noting any areas where you get stuck so you can go back and review those concepts
- Instructors will assist Students, however it is up to the individual Student to come up with the answers
