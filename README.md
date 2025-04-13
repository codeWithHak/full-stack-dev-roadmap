# Full-Stack MERN Developer Roadmap

Welcome to your journey to becoming a proficient full-stack MERN developer! This roadmap is designed to guide you through **HTML, CSS, JavaScript, Firebase, React, and Backend (Node.js, Express, MongoDB)** over ~4 months (~100 hours, ~4 hours/day, 5 days/week). Each module includes subtopics, learning goals, hands-on tasks (exercises, projects, practice), and resources to build practical, job-ready skills.

## Overview
- **Duration**: ~16 weeks (~100 hours total, ~5 hours/week).
- **Modules**:
  - Module 1: HTML & CSS (2 weeks, 12 hours) — Build responsive frontends.
  - Module 2: JavaScript & Firebase (5 weeks, 30 hours) — Master logic and real-time data.
  - Module 3: React (4 weeks, 25 hours) — Create dynamic SPAs.
  - Module 4: Backend (Node.js, Express, MongoDB) (5 weeks, 33 hours) — Develop APIs and databases.
- **Outcomes**:
  - Portfolio with 8+ projects (e.g., portfolio site, task app, social API).
  - Skills (CRUD, auth, responsive UIs).
  - GitHub showcasing code and deployments.

## Prerequisites
- Basic computer literacy and a code editor (e.g., [VS Code](https://code.visualstudio.com/)).
- GitHub account for version control ([GitHub](https://github.com/)).
- ~4 hours/day study time.

---

## Module 1: HTML & CSS (2 Weeks, 12 Hours)
Lay the foundation for front-end development with semantic HTML and responsive CSS.

### Week 1: HTML (6 Hours)
**Goal**: Structure web content with semantic, accessible markup.

- **Subtopics**:
  - **Tags**: div, span, h1-h6, p, a, img, form, input, button.
  - **Semantic Elements**: header, nav, main, article, section, footer.
  - **Attributes**: id, class, src, alt, href, type.
  - **Forms**: input types (text, email, password), labels, validation.
- **Learning Outcomes**:
  - Write clean, semantic HTML.
  - Create accessible forms with validation.
- **Exercises** (2 hours):
  - **Personal Bio Page**: Build a page with a header (h1, nav), article (p, img), and footer using semantic tags.
  - **Contact Form**: Create a form with name, email, and message fields, including required attributes.
- **Resources**:
  - [MDN: HTML Elements](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) (~30 min).
  - [freeCodeCamp: HTML](https://www.freecodecamp.org/learn/2022/responsive-web-design/) (~1 hour).

### Week 2: CSS (6 Hours)
**Goal**: Style web pages with responsive, modern layouts.

- **Subtopics**:
  - **Selectors**: element, class, ID, attribute, pseudo-classes (:hover, :focus).
  - **Box Model**: margin, padding, border, width/height.
  - **Flexbox**: display: flex, justify-content, align-items.
  - **Responsive Design**: media queries, relative units (%, vw, rem, em).
- **Learning Outcomes**:
  - Style layouts with Flexbox.
  - Build mobile-first responsive designs.
- **Exercises** (2 hours):
  - **Card Layout**: Style a product card (image, title, button) using Flexbox and hover effects.
  - **Responsive Navbar**: Create a navbar that collapses to a menu on mobile using media queries.
- **Resources**:
  - [CSS-Tricks: Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) (~30 min).
  - [MDN: Media Queries](https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries) (~20 min).

**Portfolio Output**: Host a static portfolio site (bio + contact form) on [GitHub Pages](https://pages.github.com/).

---

## Module 2: JavaScript & Firebase (5 Weeks, 30 Hours)
Master dynamic scripting and real-time data to power front-end and backend logic.

### Week 3: JavaScript - Core Concepts (6 Hours)
**Goal**: Build logic with modern ES6+ features.

- **Subtopics**:
  - **Datatypes**: string, number, boolean, array, object, null, undefined.
  - **Variables**: let, const, var, scope.
  - **Conditionals**: if-else, switch, ternary.
  - **Loops**: for, while, forEach, for...of.
- **Learning Outcomes**:
  - Manipulate data with ES6 syntax.
  - Write logic for user interactions.
- **Exercises** (2 hours):
  - **Budget Calculator**: Create a function that takes income/expense arrays and returns net balance using conditionals.
  - **Task Counter**: Build a loop to count incomplete tasks in an array of objects.
- **Resources**:
  - [JavaScript.info: Variables](https://javascript.info/variables) (~30 min).
  - [freeCodeCamp: Basic JS](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/) (~1 hour).

### Week 4: JavaScript - Arrays and Functions (6 Hours)
**Goal**: Process data efficiently with functional patterns.

- **Subtopics**:
  - **Array Methods**: map, filter, reduce, find, sort.
  - **Functions**: arrow functions, default parameters, higher-order functions.
  - **Functional Programming**: immutability, pure functions.
- **Learning Outcomes**:
  - Transform data for UI rendering.
  - Write reusable, modular code.
- **Exercises** (2 hours):
  - **E-Commerce Filter**: Filter products by price range and map to discounted prices (20% off).
  - **Memoize Function**: Create a higher-order function that caches results of a square(number) function.
- **Resources**:
  - [MDN: Array Methods](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array) (~30 min).
  - [freeCodeCamp: Functional Programming](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#functional-programming) (~30 min).

### Week 5: JavaScript - DOM and Events (6 Hours)
**Goal**: Create interactive web pages.

- **Subtopics**:
  - **DOM Manipulation**: querySelector, createElement, innerHTML.
  - **Events**: click, input, submit, event delegation.
  - **Event Bubbling**: capturing vs bubbling phases.
- **Learning Outcomes**:
  - Update UIs dynamically.
  - Handle user interactions efficiently.
- **Exercises** (2 hours):
  - **Dynamic Todo**: Build a todo list where users add/delete tasks via DOM updates and click events.
  - **Accordion Menu**: Create a collapsible menu using event delegation for section clicks.
- **Resources**:
  - [MDN: DOM Introduction](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction) (~30 min).
  - [JavaScript.info: Events](https://javascript.info/events) (~30 min).

### Week 6: JavaScript - Async Programming (6 Hours)
**Goal**: Fetch and process API data.

- **Subtopics**:
  - **Promises**: then, catch, Promise.all.
  - **Async/Await**: try-catch, error handling.
  - **Fetch API**: GET, POST, headers.
- **Learning Outcomes**:
  - Integrate APIs into apps.
  - Handle async errors gracefully.
- **Exercises** (2 hours):
  - **Post Viewer**: Fetch and display posts from [JSONPlaceholder](https://jsonplaceholder.typicode.com/posts) using async/await.
  - **Batch Fetch**: Use Promise.all to fetch users and posts simultaneously and log combined data.
- **Resources**:
  - [MDN: Async Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function) (~30 min).
  - [JavaScript.info: Promises](https://javascript.info/promise-basics) (~30 min).

### Week 7: Firebase (6 Hours)
**Goal**: Add real-time data and hosting.

- **Subtopics**:
  - **Firestore**: collections, documents, queries.
  - **Authentication**: email/password, anonymous login.
  - **Hosting**: deploying static apps.
- **Learning Outcomes**:
  - Store and sync data in real-time.
  - Implement user auth and deploy apps.
- **Exercises** (2 hours):
  - **Chat Log**: Build a Firestore collection to save/retrieve chat messages in real-time.
  - **Login Page**: Create an email/password login with Firebase Auth and redirect to a dashboard.
- **Resources**:
  - [Firebase Docs: Firestore](https://firebase.google.com/docs/firestore) (~30 min).
  - [Firebase Docs: Authentication](https://firebase.google.com/docs/auth) (~30 min).

**Portfolio Output**: Build a JS-driven app (e.g., todo with Firebase backend) and host on [Firebase](https://firebase.google.com/).

---

## Module 3: React (4 Weeks, 25 Hours)
Develop dynamic single-page applications with advanced React techniques.

### Week 8: React - Components and Hooks (6 Hours)
**Goal**: Build reusable, stateful UIs.

- **Subtopics**:
  - **Components**: functional components, props, JSX.
  - **Hooks**: useState, useEffect, custom hooks.
  - **State Management**: lifting state up, controlled inputs.
- **Learning Outcomes**:
  - Create modular UIs.
  - Manage complex state and side effects.
- **Project** (2 hours):
  - **Weather App**: Build an app to fetch and display weather via [OpenWeather API](https://openweathermap.org/api) using useState and useEffect.
- **Resources**:
  - [React.dev: Hooks](https://react.dev/reference/react) (~30 min).
  - [freeCodeCamp: React](https://www.freecodecamp.org/learn/front-end-development-libraries/) (~1 hour).

### Week 9: React - Routing and APIs (6 Hours)
**Goal**: Create multi-page apps with data integration.

- **Subtopics**:
  - **React Router**: BrowserRouter, Route, Link, useParams.
  - **API Integration**: axios, fetch, error boundaries.
  - **Dynamic Routing**: nested routes, 404 handling.
- **Learning Outcomes**:
  - Navigate SPAs seamlessly.
  - Fetch and render API data.
- **Project** (2 hours):
  - **Blog Frontend**: Build a blog with Home, Posts, and Post Detail pages using React Router and [JSONPlaceholder](https://jsonplaceholder.typicode.com/).
- **Resources**:
  - [React Router Docs](https://reactrouter.com/en/main) (~30 min).
  - [Axios Docs](https://axios-http.com/docs/intro) (~20 min).

### Week 10: React - Authentication (6 Hours)
**Goal**: Secure apps with user auth.

- **Subtopics**:
  - **Context API**: global state for user data.
  - **Auth Flows**: login, signup, logout, JWT.
  - **Protected Routes**: redirect unauthenticated users.
- **Learning Outcomes**:
  - Manage user sessions.
  - Restrict access to routes.
- **Project** (2 hours):
  - **Auth Dashboard**: Create a login/signup UI with a protected dashboard showing user info (use Firebase Auth or mock API).
- **Resources**:
  - [React.dev: Context](https://react.dev/learn/passing-data-deeply-with-context) (~30 min).
  - [freeCodeCamp: Context API](https://www.freecodecamp.org/news/react-context-for-beginners/) (~30 min).

### Week 11: React - CRUD and Optimization (7 Hours)
**Goal**: Build data-driven, performant apps.

- **Subtopics**:
  - **CRUD Operations**: create, read, update, delete.
  - **Performance**: memo, useCallback, lazy loading.
  - **Error Handling**: try-catch, error boundaries.
- **Learning Outcomes**:
  - Implement full CRUD workflows.
  - Optimize React apps for speed.
- **Project** (2.5 hours):
  - **Task Manager**: Build a task app with add/edit/delete/view features, connected to Firebase Firestore or a mock API.
- **Resources**:
  - [React.dev: Performance](https://react.dev/learn/keeping-your-app-responsive) (~30 min).
  - [MDN: Error Boundaries](https://react.dev/reference/react/Component#catching-rendering-errors-with-an-error-boundary) (~20 min).

**Portfolio Output**: Deploy 3 React apps (weather, blog, task manager) on [Vercel](https://vercel.com/) or Firebase.

---

## Module 4: Backend - Node.js, Express, MongoDB (5 Weeks, 33 Hours)
Master server-side development with APIs and databases.

### Week 12: Node.js and Express Basics (7 Hours)
**Goal**: Build and deploy RESTful APIs.

- **Subtopics**:
  - **Node.js**: modules, npm, event loop.
  - **Express**: routing, middleware, JSON responses.
  - **REST Principles**: GET, POST, PUT, DELETE, status codes.
- **Learning Outcomes**:
  - Create Express servers.
  - Design basic APIs.
- **Practice** (2.5 hours):
  - **Product API**: Build GET /products (list) and POST /products (add) routes with mock data.
  - **Middleware Logger**: Add middleware to log request method and URL.
- **Resources**:
  - [Node.js Docs](https://nodejs.org/en/docs/) (~30 min).
  - [Express.js Guide](https://expressjs.com/en/starter/hello-world.html) (~30 min).

### Week 13-14: MongoDB and CRUD (8 Hours)
**Goal**: Manage data with MongoDB.

- **Subtopics**:
  - **MongoDB**: collections, documents, Mongoose.
  - **CRUD**: create, read, update, delete operations.
  - **Queries**: $in, $regex, sort, limit.
- **Learning Outcomes**:
  - Connect Express to MongoDB.
  - Perform complex queries.
- **Practice** (3 hours):
  - **Event Planner API**: Implement CRUD for events (title, date). Add a search route by title using $regex.
  - **Paginated List**: Create a GET /events?page=1 route to return 5 events per page.
- **Resources**:
  - [MongoDB Docs](https://www.mongodb.com/docs/) (~30 min).
  - [Mongoose Docs](https://mongoosejs.com/docs/) (~30 min).

### Week 15: Backend Authentication (9 Hours)
**Goal**: Secure APIs with user auth.

- **Subtopics**:
  - **JWT**: token generation, verification.
  - **Bcrypt**: password hashing.
  - **Auth Middleware**: protect routes, refresh tokens.
- **Learning Outcomes**:
  - Build secure login/signup APIs.
  - Restrict access with tokens.
- **Practice** (3 hours):
  - **User Auth API**: Create login/signup routes with JWT and bcrypt. Add a protected /profile route.
  - **Token Refresh**: Implement a /refresh route to issue new tokens (mock logic).
- **Resources**:
  - [JWT.io](https://jwt.io/introduction) (~30 min).
  - [freeCodeCamp: Node.js Auth](https://www.freecodecamp.org/news/how-to-build-secure-jwt-authentication-in-node-js/) (~30 min).

### Week 16: Advanced Backend (9 Hours)
**Goal**: Scale and optimize APIs.

- **Subtopics**:
  - **Routers**: modular routing.
  - **Aggregation**: group, count, populate.
  - **File Uploads**: multer, cloud storage basics.
- **Learning Outcomes**:
  - Organize large APIs.
  - Handle complex data and uploads.
- **Practice** (3 hours):
  - **Forum API**: Build post and comment routes with population (comments linked to posts). Add an aggregation to count posts by user.
  - **Profile Picture**: Create a /upload route for image uploads using multer (mock storage).
- **Resources**:
  - [Express: Routing](https://expressjs.com/en/guide/routing.html) (~20 min).
  - [MongoDB: Aggregation](https://www.mongodb.com/docs/manual/aggregation/) (~30 min).

**Portfolio Output**: Deploy 2 MERN apps (task manager + event planner) on [Render](https://render.com/) or [Heroku](https://www.heroku.com/).

---

## Tools and Workflow
- **Code Editor**: VS Code with ESLint and Prettier.
- **Version Control**: Push daily to [GitHub](https://github.com/).
- **Testing**: Browser dev tools for front-end, [Postman](https://www.postman.com/) for APIs.
- **Styling**: Use [Tailwind CSS](https://tailwindcss.com/) for fast, modern designs.
- **Debugging**: Search [Stack Overflow](https://stackoverflow.com/) or ask internship peers.

## Portfolio Checklist
- **HTML/CSS**: Portfolio site (bio, contact).
- **JS/Firebase**: Todo app with Firebase backend.
- **React**: Weather app, blog frontend, task manager.
- **Backend**: Product API, event planner API, user auth API.
- **MERN**: 2 full-stack apps (task manager, event planner).
- **Showcase**: Host portfolio site on Vercel with links to all projects.

## Tips for Success
- **Internship Synergy**: Apply skills (e.g., React components, APIs) to work tasks.
- **Consistency**: Study 4 hours/day, 5 days/week. Use weekends to polish projects.
- **Community**: Discuss challenges with internship peers for insights.
- **Track Progress**: Log completed tasks (e.g., “Built CRUD API”) to stay motivated.

## Why This Roadmap?
This roadmap condenses essential MERN skills into ~100 hours, focusing on practical tasks (exercises, projects, practice). You’ll build a portfolio that demonstrates front-end finesse, dynamic React apps, and robust APIs, positioning you as a strong developer in the industry.

---

Happy coding! 🚀 Push your progress to GitHub and share your portfolio when ready.
