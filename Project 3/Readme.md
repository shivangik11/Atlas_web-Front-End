## Project 3
Create a single page application (SPA) using React.js, or any front-end web development framework of our team’s choosing.

### Team Members
1. Shivangi
2. Preetam
3. Sohini

## Milestone 1

### Ideation
Project Topic: Single-page web application for course registration using React.js.

The project's goal is to develop a practical/real-world application. As students, we all use or have used the online course registration tool. I believe the time has come to construct one. In this application, students can choose from a list of available courses, browse through each course, view detailed information, add the course to their cart, and complete the registration process. The app will have multiple pages such as a course cart page, a registered courses page, and so on. We can demonstrate what we've learned about React.js and how to use concepts like creating react components and using react router to create single-page web apps with this project.

### Features
1. Browse course list
2. Course detail page
3. Add course to cart
4. Check cart items
5. Complete course registration

## Milestone 2

We wanted to create a project UI prototype for this milestone. So we could figure out how to divide the app into component structures and plan for the MVP. We started with low-fidelity wireframes and then progressed to a high-fidelity prototype.

![Web 1366 – 2](https://user-images.githubusercontent.com/89596201/204848314-a0113681-3144-4a6f-b464-c33ccdab8753.png)

![Web 1366 – 1](https://user-images.githubusercontent.com/89596201/204848320-988f9585-5f05-47e8-ac2a-d87b8164b26b.png)


### High Fidelity Mockup

![Desktop - 3](https://user-images.githubusercontent.com/89596201/204848536-4ac405b2-67ff-405a-b0b5-4d27dc2dd630.png)

![Desktop - 4](https://user-images.githubusercontent.com/89596201/204848542-9e39faf9-c7e1-4adf-a58b-dab24ef29b9d.png)

![Desktop - 1](https://user-images.githubusercontent.com/89596201/204848523-f5a650f7-7d8d-44d3-a139-37207050dc7d.png)

![Desktop - 2](https://user-images.githubusercontent.com/89596201/204848531-f84f33f1-d27c-4ed0-b20f-47f362a7bb31.png)

We will be using React router package to implement the Single page application (SPA) using React.
The app is split in to 4 different pages.
1. Home
2. Course Detail
3. Cart
4. My Courses

### Breaking The UI Into components
Splitting the UI into to components so that each component adheres to single responsibility principle. Each component is responsible for one particular task alone.

#### We have split the UI into components.
1. Navigation header Component
2. Course list Component
3. Search Component
4. Cart component
5. Course Detail Component
6. The cart/my course item component
7. Error message component (when the user tries to add a course that is already in cart/registered courses and when the time schedule clashes)
To make the UI interactive we need to provide React with state. The change in state tell react that something has changed and re-render the component to trigger changes.

To maintain the Application wise state we decided to use the useContext() react hook.

### Goals for Milestone 3

MVP (Minimum Viable Product)
For the MVP, we’d like to create all of the pages with their respective components and styles, as well as apply the routing. As a stretch goal, we’d like to have the entire application completed and working properly.

