# Project Proposal
> Failing to plan is planning to fail.

## Summary the Project Proposal

Before starting on a large project with a short deadline, it will be useful to make a comprehensive **Project Proposal** that outlines the scope of your project and addresses major areas of concern before you start to build.

The Project Proposal is composed of 3 principal parts:
1. The Overview
2. User Stories
3. Data Model
4. Sprints
5. Rubrics

Here is an [example-demo of  a complete proposal](https://drive.google.com/open?id=1-sTjB2gQf8laQOmHM3HkZs8Lsg7CtTW_):

### I. The Overview
The overview is a summary of *what* you are looking build. In includes:
- Name of the App
- Type of App
- Description
- Technologies
- Web App Features (MVP requirements)
- Project Roadmap (future requirements)

### II. Wireframes

Wireframes for your user stories + features that give a rough sketch of the UI/UX of your application.

### III. User Stories
User Stories answer the question about *who* your app is being built for. **Feature requirements should be driven by User Stories**

A User Story has the following format:
> **As a** ________,  **I need a way to** _______ , **so that I can**  _________.

Example: **As an** *authenticated user*, **I need a way to** *arrive at a dashboard page*, **so that I can** *see which todo items I've completed*.

It is incumbent on you to come up with sensible User Stories and to be able to identify feature requirements for desired functionality. Within every user story, you must also identify assumptions that suggest *auxiliary functionality* that needs would need to be in place to build the required feature set.

### IV. Data Model
Your data model is setup by the backend and contains the entities and relations. You should have an explicit understanding of what types of data your application will require how data is related, and how that data will integrate with the front-end layer of your application.

## Assignment

### Deliverables

**Start the project proposal**

1. Create the **User Stories** that outline how users will interact with your application. I recommend doing this first.

2. Create the initial *Project Overview* section that provides basic information about your application
  - Name of the App
  - Type of App
  - Description
  - Technologies
  - Features (MVP)

3. Requeriments

#### Always Required

##### Full Authentication

+ Backend and Frontend

##### Full Stack CRUD website

|#|Type|Description|
|-|-|-|
|1|POST|Create|
|2|GET|Read|
|3|PUT/PATCH|Update|
|4|DELETE|Delete|

##### Associations/Relations amongst Models

|#|Type|Description|
|-|-|-|
|1|1 -> N|One to many|
|2|1 -> 1|One to one|
|3|N -> 1|Many to one|
|4|N -> N|Many to many|

*You might not need all kind of relationships, but for sure you‘ll need some of them.*

##### Technologies

You must also use additional technologies to gain points. The technologies and their associated points are listed here, with descriptions.

|Category|Name|Points|
|-|-|-|
|Planning and Design|||
||Project Planning|Required|
||Domain Registration|10|
||Responsive|20|
|Techs|||
||Redux|10|
||Stripe|20|
||Amazon S3|10|
||Sockets|20|
||ChartJS|10|
||D3|20|
||Nodemailer/SendGrid|10|
||Twilio|10|
||CSS-in-JS|10|
||**Any others?** (Pre-approved by Teacher)|30*|
|Build Tools|||
||Sass|10|
||Webpack|20|
|Hosting|||
||Heroku|Required|
||Digital Ocean|10|
|Testing|||
||Unit Tests|10|
||Endpoint Tests|20|
||E2E Tests|40|
|Presentation|||
||Uses Time Effectively|10|
||Cool Slides|10|

**Total points required: 50**

|**Example Path:**|Points|
|-|-|
|Sass|10|
|Redux|10|
|Responsive|20|
|Presentation Points|10|
|**TOTAL**|50|

4. [Link to Demo Project Propsal](https://drive.google.com/file/d/1-sTjB2gQf8laQOmHM3HkZs8Lsg7CtTW_/view)
