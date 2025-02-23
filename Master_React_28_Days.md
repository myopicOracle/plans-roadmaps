# **Master React in 28 Days**
## **Project-Based Learning + Theory (50/50 Split)**

**4-week plan** with **highly-detailed daily breakdowns**, prioritizing [The Odin Project](https://www.theodinproject.com/paths/full-stack-javascript/courses/react)
’s curriculum React Course (80-90% focus), supplemented by [Full Stack Open](https://fullstackopen.com/en/part1/introduction_to_react)
 (10-20%), and integrating the **Automated Financial Report Generator** as the Final Project. The plan avoids new tools, leveraging React + ChatGPT API with foundational web stack JS/HTML/CSS skills:

*Generated w/ DeepSeek DeepThink (R1) + Search*

---

### **Week 1: React Foundations**  
**Goal**: Components, JSX, state/props, and CV Application.  
**FSO Usage**: 10% (supplemental theory only).  

| **Day** | **Focus**                                                                 | **Tasks**                                                                                                  |
|---------|---------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| 1       | **Intro to React** + Components                                           | Build static components (e.g., `Header`, `Bio`) using JSX.                                                 |
| 2       | **State/Props** + Dynamic Rendering                                       | Create an interactive counter; pass props between parent/child components.                                 |
| 3       | **Rendering Lists** + **Keys**                                            | Render a list of skills/experiences with unique keys for the CV project.                                   |
| 4       | **Project: CV Application** (Setup)                                       | Structure reusable components (e.g., `EducationSection`, `WorkHistory`).                                  |
| 5       | **State Management** in CV App                                            | Add edit/save toggles for sections using `useState`.                                                       |
| 6       | **Styling** + Deployment                                                  | Style with CSS modules; deploy to GitHub Pages.                                                            |
| 7       | **Review** + Debug                                                        | Refactor code and add PropTypes for type safety.                                                           |

---

### **Week 2: Intermediate React**  
**Goal**: Side effects, API calls, testing.  
**FSO Usage**: 15% (API/data fetching examples).  

| **Day** | **Focus**                                                                 | **Tasks**                                                                                                  |
|---------|---------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| 8       | **Side Effects** + `useEffect`                                            | Fetch data from a public API (e.g., display stock prices using [Alpha Vantage](https://www.alphavantage.co/)). |
| 9       | **Project: Memory Card** (Setup)                                          | Implement card-flipping logic with `useState` and `useEffect`.                                             |
| 10      | **Class Components** + Lifecycle                                          | Convert a functional component to class-based (e.g., timer for game moves).                                |
| 11      | **Testing** (Jest/RTL)                                                    | Write tests for CV App buttons and state changes.                                                          |
| 12      | **Styling Deep Dive**                                                     | Style Memory Card with animations (CSS transitions).                                                       |
| 13      | **Project: Memory Card** (Finish)                                         | Add score tracking and high-score persistence with `localStorage`.                                         |
| 14      | **Review** + API Error Handling                                           | Handle API errors gracefully; deploy Memory Card.                                                          |

---

### **Week 3: Routing & Advanced State**  
**Goal**: React Router, Context API, Shopping Cart.  
**FSO Usage**: 10% (routing patterns).  

| **Day** | **Focus**                                                                 | **Tasks**                                                                                                  |
|---------|---------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| 15      | **React Router**                                                          | Build a multi-page app (e.g., e-commerce site with `/products` and `/cart` routes).                        |
| 16      | **Context API** + Global State                                            | Implement a dark/light theme switcher for the router app.                                                  |
| 17      | **Project: Shopping Cart** (Setup)                                        | Create product listings and cart state with `useContext`.                                                  |
| 18      | **Cart Logic** + API Integration                                          | Fetch product data from a mock API; handle add/remove items.                                               |
| 19      | **Performance** (`useMemo`/`useCallback`)                                 | Optimize cart re-renders; add loading skeletons.                                                           |
| 20      | **Testing** the Shopping Cart                                             | Write integration tests for cart functionality.                                                            |
| 21      | **Deployment** + Polish                                                   | Deploy to Netlify; add responsive styling.                                                                 |

---

### **Week 4: Final Project**  
**Automated Financial Report Generator**  
**Tech**: React, ChatGPT API, HTML/CSS.  
**Key Skills Tested**: API integration, forms, state, component architecture.  

| **Day** | **Milestone**                                                             | **Tasks**                                                                                                  |
|---------|---------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|
| 22      | **Project Setup**                                                         | - Create React app <br>- Design components: `ReportForm`, `DataParser`, `ReportViewer` <br>- Set up ChatGPT API client. |
| 23      | **Form Handling** + Data Fetching                                         | - Build a form to input ticker symbols/dates <br>- Fetch SEC filing summaries via ChatGPT API.             |
| 24      | **Data Parsing & Display**                                                | - Transform API responses into tables/charts <br>- Use `useReducer` for complex state (e.g., parsed data). |
| 25      | **Export Features** + Error Handling                                      | - Add PDF/CSV export with `react-pdf` or `file-saver` <br>- Handle API errors and loading states.          |
| 26      | **Styling** + Final Polish                                                | - Style with Tailwind CSS <br>- Add animations for transitions.                                            |
| 27      | **Testing** + Debugging                                                   | - Write tests for form submission and data rendering <br>- Fix edge cases.                                 |
| 28      | **Deployment** + Documentation                                            | - Deploy to Netlify <br>- Write a README explaining features and tech stack.                               |

---

### **Final Project Features**:  
1. **User Input**: Form to input company ticker/date range.  
2. **AI Parsing**: Use ChatGPT API to summarize SEC filings/earnings calls.  
3. **Data Visualization**: Display key metrics (revenue, EPS) in tables/charts.  
4. **Export**: Generate downloadable PDF/CSV reports.  
5. **Error Handling**: Graceful UI for API failures or invalid inputs.  

### **Adjustments**:  
- **FSO Minimized**: Only referenced for API best practices (Part 2) and testing (Part 5).  
- **Optional Messaging App**: Added as a stretch goal post-Day 28 if time permits.  
- **No New Tools**: ChatGPT API integrates via REST (familiar from Week 2).  

This plan balances TOP’s hands-on projects with just enough theory to reinforce concepts. 

---

Here’s a **daily task breakdown** for your **4-week React mastery plan**, optimized for your **6-hour daily schedule** and focused on TOP’s curriculum (80-90%) with minimal FSO supplementation. The **Automated Financial Report Generator** is the Final Project, with clear daily milestones:

---

### **Week 1: React Foundations**  
**Goal**: Build core React skills and complete the CV Application.  

| **Day** | **Focus**                                  | **Tasks**                                                                                                  |
|---------|--------------------------------------------|------------------------------------------------------------------------------------------------------------|
| **1**   | Intro to React & Components                | - Complete TOP: *How This Course Will Work* + *Introduction to React* <br>- Build static components (e.g., `Header`, `Bio`) with JSX. |
| **2**   | Setup & Component Architecture             | - TOP: *Setting Up a React Environment* + *React Components* <br>- Create a component tree (e.g., `App > EducationSection`, `WorkHistory`). |
| **3**   | Dynamic Lists & Keys                       | - TOP: *What Is JSX?* + *Rendering Techniques* + *Keys in React* <br>- Render dynamic CV sections (e.g., skills list with unique keys). |
| **4**   | Passing Data (Props)                       | - TOP: *Passing Data Between Components* <br>- Build props-driven sections (e.g., `UserProfile` with dynamic data). |
| **5**   | State Management Basics                    | - TOP: *Introduction to State* + *More on State* <br>- Add edit/save toggles to CV sections using `useState`. |
| **6**   | **CV Application** (Styling & Deployment)  | - Style CV with CSS Modules <br>- Deploy to GitHub Pages.                                                 |
| **7**   | Review & Debug                             | - Refactor code (e.g., split into reusable components) <br>- Add PropTypes for type checking.              |

---

### **Week 2: Intermediate React**  
**Goal**: API calls, testing, and Memory Card project.  

| **Day** | **Focus**                                  | **Tasks**                                                                                                  |
|---------|--------------------------------------------|------------------------------------------------------------------------------------------------------------|
| **8**   | Side Effects & `useEffect`                 | - TOP: *How to Deal With Side Effects* <br>- Fetch stock data from Alpha Vantage API (demo).               |
| **9**   | **Memory Card Project** (Setup)            | - Build card-flipping logic with `useState` <br>- Track game moves with `useEffect`.                       |
| **10**  | Class Components & Lifecycle               | - TOP: *Class-Based Components* + *Component Lifecycle Methods* <br>- Convert a timer component to class-based. |
| **11**  | Testing Basics                             | - TOP: *Introduction to React Testing* <br>- Write Jest/RTL tests for CV App buttons.                      |
| **12**  | Styling & Animations                       | - TOP: *Styling React Applications* <br>- Add CSS transitions to Memory Card.                              |
| **13**  | **Memory Card** (Finish)                   | - Implement score tracking <br>- Persist high scores in `localStorage`.                                   |
| **14**  | API Error Handling & Deployment            | - Handle API errors gracefully <br>- Deploy Memory Card to Netlify.                                        |

---

### **Week 3: Routing & Advanced State**  
**Goal**: Multi-page apps, global state, Shopping Cart.  

| **Day** | **Focus**                                  | **Tasks**                                                                                                  |
|---------|--------------------------------------------|------------------------------------------------------------------------------------------------------------|
| **15**  | React Router                               | - TOP: *React Router* <br>- Build a multi-page e-commerce app (e.g., `/products`, `/cart`).                |
| **16**  | Context API & Global State                 | - TOP: *Managing State With the Context API* <br>- Add dark/light theme toggle using `useContext`.         |
| **17**  | **Shopping Cart** (Setup)                  | - Create product listings <br>- Set up cart state with `useContext`.                                       |
| **18**  | API Integration & Cart Logic               | - Fetch mock product data <br>- Implement add/remove cart items.                                           |
| **19**  | Performance Optimization                   | - TOP: *Refs and Memoization* <br>- Optimize re-renders with `useMemo`/`useCallback`.                      |
| **20**  | Testing the Shopping Cart                  | - Write integration tests for cart features (e.g., item count updates).                                    |
| **21**  | Deployment & Polish                        | - Deploy Shopping Cart to Netlify <br>- Add responsive styling.                                            |

---

### **Week 4: Final Project**  
**Automated Financial Report Generator**  
**Tech**: React, ChatGPT API, HTML/CSS.  

| **Day** | **Milestone**                              | **Tasks**                                                                                                  |
|---------|--------------------------------------------|------------------------------------------------------------------------------------------------------------|
| **22**  | Project Setup & Design                     | - Create React app <br>- Design components: `ReportForm`, `DataParser`, `ReportViewer` <br>- Set up ChatGPT API client. |
| **23**  | Form Handling & API Integration            | - Build a form for ticker symbols/dates <br>- Fetch SEC summaries via ChatGPT API (demo response parsing). |
| **24**  | Data Parsing & Visualization               | - Transform API data into tables/charts <br>- Use `useReducer` for complex state (e.g., parsed metrics).   |
| **25**  | Export Features & Error Handling           | - Add PDF/CSV export with `react-pdf` <br>- Handle API errors and loading states.                          |
| **26**  | Styling & Animations                       | - Style with Tailwind CSS <br>- Add loading animations for data fetching.                                  |
| **27**  | Testing & Edge Cases                       | - Write tests for form validation and data rendering <br>- Fix edge cases (e.g., invalid tickers).         |
| **28**  | Deployment & Documentation                 | - Deploy to Netlify <br>- Write a detailed README (features, setup, screenshots).                          |

---

### **Final Project Features**:  
1. **Input Form**: Collect company ticker symbols and date ranges.  
2. **AI-Powered Parsing**: Use ChatGPT API to summarize SEC filings.  
3. **Data Display**: Render key metrics (revenue, EPS) in tables and charts.  
4. **Export Functionality**: Generate downloadable reports (PDF/CSV).  
5. **Error States**: Handle invalid inputs, API limits, and loading spinners.  

### **Optional Stretch Goals** (Post-Day 28):  
- Add user authentication (Firebase Auth).  
- Compare multiple companies side-by-side.  
- Build a historical trends chart.  

---

### **Daily Workflow Example** (6 Hours):  
1. **Theory (1–1.5 hrs)**: Read TOP lessons + minimal FSO snippets (e.g., API best practices).  
2. **Coding (3–4 hrs)**: Build projects step-by-step.  
3. **Review (1 hr)**: Debug, refactor, or test previous work.  

---

---

### **Day 1: Intro to React & Components**  
**Goal**: Understand React basics, set up a project, and build static components.  

#### **Theory (1.5 hrs)**  
1. **TOP: How This Course Will Work**  
   - Read the lesson to understand the course structure, expectations, and resources.  
   - Set up your workspace: Install Node.js, VS Code, and Chrome (if not already done).  

2. **TOP: Introduction to React**  
   - Read about React’s purpose, component-based architecture, and declarative UI.  
   - Understand the difference between React and vanilla JS.  

3. **FSO Part 1a: Intro to React (Optional)**  
   - Skim the section for a deeper explanation of React’s core concepts (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Build static components using `React.createElement` and JSX.  

1. **Set Up a React Project** (30 mins)  
   - Run `npx create-react-app my-first-react-app` to scaffold a new project.  
   - Start the development server: `npm start`.  
   - Clean up the default template:  
     - Delete `logo.svg` and unnecessary code in `App.js`.  
     - Remove unused files (e.g., `App.test.js`, `reportWebVitals.js`).  

2. **Build Static Components with `React.createElement`** (1 hr)  
   - In `App.js`, create a simple header using `React.createElement`:  
     ```javascript
     const header = React.createElement('h1', null, 'Welcome to My React App');
     const container = React.createElement('div', { className: 'container' }, header);
     ReactDOM.render(container, document.getElementById('root'));
     ```  
   - Add a paragraph and a button using the same method.  

3. **Convert to JSX** (1 hr)  
   - Rewrite the above code using JSX:  
     ```javascript
     function App() {
       return (
         <div className="container">
           <h1>Welcome to My React App</h1>
           <p>This is my first React component.</p>
           <button>Click Me</button>
         </div>
       );
     }
     ```  
   - Understand how JSX simplifies component creation.  

4. **Create Reusable Components** (1.5 hrs)  
   - Create a `Header` component in a new file (`Header.js`):  
     ```javascript
     function Header() {
       return <h1>Welcome to My React App</h1>;
     }
     export default Header;
     ```  
   - Create a `Footer` component (`Footer.js`):  
     ```javascript
     function Footer() {
       return <p>© 2024 My React App</p>;
     }
     export default Footer;
     ```  
   - Import and use these components in `App.js`:  
     ```javascript
     import Header from './Header';
     import Footer from './Footer';

     function App() {
       return (
         <div className="container">
           <Header />
           <p>This is my first React component.</p>
           <button>Click Me</button>
           <Footer />
         </div>
       );
     }
     ```  

5. **Style Your Components** (30 mins)  
   - Add basic CSS in `App.css`:  
     ```css
     .container {
       text-align: center;
       padding: 20px;
     }
     h1 {
       color: #333;
     }
     button {
       padding: 10px 20px;
       background-color: #007bff;
       color: white;
       border: none;
       cursor: pointer;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the components render correctly in the browser.  
2. **Debug**: Check for errors in the console and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 1**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - A `Footer` component with a copyright notice.  
   - A button and paragraph in the main `App` component.  
2. Basic styling applied to the app.  
3. A clear understanding of JSX and component structure.  

---
---

### **Day 2: Setup & Component Architecture**  
**Goal**: Set up a React environment, understand component hierarchy, and build a structured app.  

#### **Theory (1.5 hrs)**  
1. **TOP: Setting Up a React Environment**  
   - Read about different ways to set up React (e.g., Create React App, Vite).  
   - Understand the purpose of `package.json`, `node_modules`, and the React development server.  

2. **TOP: React Components**  
   - Learn about functional components, props, and component composition.  
   - Understand the difference between parent and child components.  

3. **FSO Part 1b: JavaScript Refresher (Optional)**  
   - Skim this section if you need a refresher on modern JavaScript (e.g., arrow functions, destructuring).  

---

#### **Coding (4 hrs)**  
**Objective**: Build a structured app with a clear component hierarchy.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app component-hierarchy-app`.  
   - Clean up the default template (remove unused files and code).  

2. **Plan the Component Hierarchy** (30 mins)  
   - Design a simple app with the following structure:  
     ```
     App
     ├── Header
     ├── Main
     │   ├── Bio
     │   ├── Skills
     │   └── Projects
     └── Footer
     ```  
   - Sketch the layout on paper or in a tool like Figma.  

3. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     function Header() {
       return (
         <header>
           <h1>My Portfolio</h1>
           <nav>
             <ul>
               <li><a href="#bio">Bio</a></li>
               <li><a href="#skills">Skills</a></li>
               <li><a href="#projects">Projects</a></li>
             </ul>
           </nav>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     nav ul {
       list-style: none;
       padding: 0;
     }
     nav ul li {
       display: inline;
       margin: 0 10px;
     }
     nav ul li a {
       color: white;
       text-decoration: none;
     }
     ```  

4. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 My Portfolio</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

5. **Create the `Main` Component** (1 hr)  
   - In `src/components/Main.js`:  
     ```javascript
     import Bio from './Bio';
     import Skills from './Skills';
     import Projects from './Projects';

     function Main() {
       return (
         <main>
           <Bio />
           <Skills />
           <Projects />
         </main>
       );
     }
     export default Main;
     ```  

6. **Create Child Components** (1 hr)  
   - **Bio Component** (`src/components/Bio.js`):  
     ```javascript
     function Bio() {
       return (
         <section id="bio">
           <h2>About Me</h2>
           <p>I'm a web developer passionate about building user-friendly applications.</p>
         </section>
       );
     }
     export default Bio;
     ```  
   - **Skills Component** (`src/components/Skills.js`):  
     ```javascript
     function Skills() {
       return (
         <section id="skills">
           <h2>Skills</h2>
           <ul>
             <li>JavaScript</li>
             <li>React</li>
             <li>HTML/CSS</li>
           </ul>
         </section>
       );
     }
     export default Skills;
     ```  
   - **Projects Component** (`src/components/Projects.js`):  
     ```javascript
     function Projects() {
       return (
         <section id="projects">
           <h2>Projects</h2>
           <ul>
             <li>Project 1</li>
             <li>Project 2</li>
             <li>Project 3</li>
           </ul>
         </section>
       );
     }
     export default Projects;
     ```  

7. **Assemble the App** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import Header from './components/Header';
     import Main from './components/Main';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       return (
         <div className="App">
           <Header />
           <Main />
           <Footer />
         </div>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
     }
     main {
       padding: 20px;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure all components render correctly and the layout is as expected.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent indentation, meaningful variable names).  

---

### **Deliverables for Day 2**  
1. A React app with:  
   - A `Header` component with navigation links.  
   - A `Main` component containing `Bio`, `Skills`, and `Projects` sections.  
   - A `Footer` component with a copyright notice.  
2. Basic styling applied to all components.  
3. A clear understanding of component hierarchy and composition.  

---
---

### **Day 3: Dynamic Lists & Keys**  
**Goal**: Render dynamic lists, understand the importance of keys, and build a reusable list component.  

#### **Theory (1.5 hrs)**  
1. **TOP: What Is JSX?**  
   - Review JSX syntax and its benefits over plain JavaScript.  
   - Understand how JSX gets transformed into `React.createElement` calls.  

2. **TOP: Rendering Techniques**  
   - Learn about conditional rendering (e.g., `&&`, ternary operators).  
   - Understand how to map over arrays to render lists.  

3. **TOP: Keys in React**  
   - Read about the purpose of keys in list rendering.  
   - Understand why keys should be unique and stable.  

---

#### **Coding (4 hrs)**  
**Objective**: Build a dynamic list of skills and projects using keys.  

1. **Refactor the `Skills` Component** (1 hr)  
   - Update `src/components/Skills.js` to use dynamic data:  
     ```javascript
     function Skills() {
       const skills = ['JavaScript', 'React', 'HTML/CSS', 'Node.js', 'Git'];

       return (
         <section id="skills">
           <h2>Skills</h2>
           <ul>
             {skills.map((skill, index) => (
               <li key={index}>{skill}</li>
             ))}
           </ul>
         </section>
       );
     }
     export default Skills;
     ```  
   - Add CSS in `Skills.css`:  
     ```css
     #skills ul {
       list-style: none;
       padding: 0;
     }
     #skills ul li {
       background-color: #f4f4f4;
       margin: 5px 0;
       padding: 10px;
       border-radius: 5px;
     }
     ```  

2. **Refactor the `Projects` Component** (1 hr)  
   - Update `src/components/Projects.js` to use dynamic data:  
     ```javascript
     function Projects() {
       const projects = [
         { id: 1, name: 'Project 1', description: 'A React-based portfolio site.' },
         { id: 2, name: 'Project 2', description: 'A weather app using APIs.' },
         { id: 3, name: 'Project 3', description: 'A task management tool.' },
       ];

       return (
         <section id="projects">
           <h2>Projects</h2>
           <ul>
             {projects.map((project) => (
               <li key={project.id}>
                 <h3>{project.name}</h3>
                 <p>{project.description}</p>
               </li>
             ))}
           </ul>
         </section>
       );
     }
     export default Projects;
     ```  
   - Add CSS in `Projects.css`:  
     ```css
     #projects ul {
       list-style: none;
       padding: 0;
     }
     #projects ul li {
       background-color: #f9f9f9;
       margin: 10px 0;
       padding: 15px;
       border-radius: 5px;
       box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
     }
     #projects ul li h3 {
       margin: 0 0 10px;
     }
     ```  

3. **Create a Reusable `List` Component** (1.5 hrs)  
   - Create a new file `src/components/List.js`:  
     ```javascript
     function List({ items, renderItem }) {
       return (
         <ul>
           {items.map((item) => (
             <li key={item.id || item}>{renderItem(item)}</li>
           ))}
         </ul>
       );
     }
     export default List;
     ```  
   - Refactor `Skills` and `Projects` to use the `List` component:  
     - **Skills.js**:  
       ```javascript
       import List from './List';

       function Skills() {
         const skills = ['JavaScript', 'React', 'HTML/CSS', 'Node.js', 'Git'];

         return (
           <section id="skills">
             <h2>Skills</h2>
             <List items={skills} renderItem={(skill) => skill} />
           </section>
         );
       }
       export default Skills;
       ```  
     - **Projects.js**:  
       ```javascript
       import List from './List';

       function Projects() {
         const projects = [
           { id: 1, name: 'Project 1', description: 'A React-based portfolio site.' },
           { id: 2, name: 'Project 2', description: 'A weather app using APIs.' },
           { id: 3, name: 'Project 3', description: 'A task management tool.' },
         ];

         return (
           <section id="projects">
             <h2>Projects</h2>
             <List
               items={projects}
               renderItem={(project) => (
                 <>
                   <h3>{project.name}</h3>
                   <p>{project.description}</p>
                 </>
               )}
             />
           </section>
         );
       }
       export default Projects;
       ```  

4. **Add Conditional Rendering** (30 mins)  
   - Update `Projects.js` to show a message if no projects exist:  
     ```javascript
     function Projects() {
       const projects = [];

       return (
         <section id="projects">
           <h2>Projects</h2>
           {projects.length > 0 ? (
             <List
               items={projects}
               renderItem={(project) => (
                 <>
                   <h3>{project.name}</h3>
                   <p>{project.description}</p>
                 </>
               )}
             />
           ) : (
             <p>No projects to display.</p>
           )}
         </section>
       );
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the lists render correctly and keys are unique.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 3**  
1. A React app with:  
   - A dynamic `Skills` list rendered using keys.  
   - A dynamic `Projects` list with descriptions and unique keys.  
   - A reusable `List` component for rendering any array of items.  
2. Conditional rendering for empty states.  
3. A clear understanding of keys and dynamic rendering.  

---
---

### **Day 4: Passing Data Between Components**  
**Goal**: Understand props, prop drilling, and build a props-driven app.  

#### **Theory (1.5 hrs)**  
1. **TOP: Passing Data Between Components**  
   - Learn how to pass data from parent to child components using props.  
   - Understand the concept of prop drilling and its limitations.  

2. **FSO Part 1c: Component State, Events (Optional)**  
   - Skim this section for a deeper explanation of props and state (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Build a user profile app where data is passed between components.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app user-profile-app`.  
   - Clean up the default template (remove unused files and code).  

2. **Plan the Component Hierarchy** (30 mins)  
   - Design a simple app with the following structure:  
     ```
     App
     ├── Header
     ├── UserProfile
     │   ├── UserInfo
     │   ├── UserSkills
     │   └── UserProjects
     └── Footer
     ```  
   - Sketch the layout on paper or in a tool like Figma.  

3. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     function Header() {
       return (
         <header>
           <h1>User Profile</h1>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     ```  

4. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 User Profile</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

5. **Create the `UserProfile` Component** (1 hr)  
   - In `src/components/UserProfile.js`:  
     ```javascript
     import UserInfo from './UserInfo';
     import UserSkills from './UserSkills';
     import UserProjects from './UserProjects';

     function UserProfile({ user }) {
       return (
         <main>
           <UserInfo user={user} />
           <UserSkills skills={user.skills} />
           <UserProjects projects={user.projects} />
         </main>
       );
     }
     export default UserProfile;
     ```  

6. **Create Child Components** (1.5 hrs)  
   - **UserInfo Component** (`src/components/UserInfo.js`):  
     ```javascript
     function UserInfo({ user }) {
       return (
         <section id="user-info">
           <h2>{user.name}</h2>
           <p>{user.bio}</p>
         </section>
       );
     }
     export default UserInfo;
     ```  
   - **UserSkills Component** (`src/components/UserSkills.js`):  
     ```javascript
     function UserSkills({ skills }) {
       return (
         <section id="user-skills">
           <h2>Skills</h2>
           <ul>
             {skills.map((skill, index) => (
               <li key={index}>{skill}</li>
             ))}
           </ul>
         </section>
       );
     }
     export default UserSkills;
     ```  
   - **UserProjects Component** (`src/components/UserProjects.js`):  
     ```javascript
     function UserProjects({ projects }) {
       return (
         <section id="user-projects">
           <h2>Projects</h2>
           <ul>
             {projects.map((project) => (
               <li key={project.id}>
                 <h3>{project.name}</h3>
                 <p>{project.description}</p>
               </li>
             ))}
           </ul>
         </section>
       );
     }
     export default UserProjects;
     ```  

7. **Assemble the App** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import Header from './components/Header';
     import UserProfile from './components/UserProfile';
     import Footer from './components/Footer';
     import './App.css';

     const user = {
       name: 'John Doe',
       bio: 'A passionate web developer.',
       skills: ['JavaScript', 'React', 'HTML/CSS', 'Node.js', 'Git'],
       projects: [
         { id: 1, name: 'Project 1', description: 'A React-based portfolio site.' },
         { id: 2, name: 'Project 2', description: 'A weather app using APIs.' },
         { id: 3, name: 'Project 3', description: 'A task management tool.' },
       ],
     };

     function App() {
       return (
         <div className="App">
           <Header />
           <UserProfile user={user} />
           <Footer />
         </div>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
     }
     main {
       padding: 20px;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure all components render correctly and data is passed properly.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent indentation, meaningful variable names).  

---

### **Deliverables for Day 4**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - A `UserProfile` component containing `UserInfo`, `UserSkills`, and `UserProjects` sections.  
   - A `Footer` component with a copyright notice.  
2. Data passed from `App` to child components via props.  
3. A clear understanding of prop drilling and component composition.  

---
---

### **Day 5: State Management Basics**  
**Goal**: Understand `useState`, build interactive components, and add state to the CV Application.  

#### **Theory (1.5 hrs)**  
1. **TOP: Introduction to State**  
   - Learn about state in React and why it’s necessary for dynamic UIs.  
   - Understand the difference between props and state.  

2. **TOP: More on State**  
   - Explore how to update state and the concept of immutability.  
   - Learn about the `useState` hook and its syntax.  

3. **FSO Part 1d: More on State Management (Optional)**  
   - Skim this section for a deeper explanation of state (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Build interactive components using `useState` and add state to the CV Application.  

1. **Refactor the CV Application** (1 hr)  
   - Open your CV Application project from Day 1.  
   - Add a `useState` hook to toggle the visibility of sections (e.g., Education, Work History).  
   - In `src/App.js`:  
     ```javascript
     import { useState } from 'react';
     import Header from './components/Header';
     import Education from './components/Education';
     import WorkHistory from './components/WorkHistory';
     import './App.css';

     function App() {
       const [showEducation, setShowEducation] = useState(true);
       const [showWorkHistory, setShowWorkHistory] = useState(true);

       return (
         <div className="App">
           <Header />
           <button onClick={() => setShowEducation(!showEducation)}>
             {showEducation ? 'Hide Education' : 'Show Education'}
           </button>
           {showEducation && <Education />}
           <button onClick={() => setShowWorkHistory(!showWorkHistory)}>
             {showWorkHistory ? 'Hide Work History' : 'Show Work History'}
           </button>
           {showWorkHistory && <WorkHistory />}
         </div>
       );
     }
     export default App;
     ```  

2. **Create the `Education` Component** (1 hr)  
   - In `src/components/Education.js`:  
     ```javascript
     function Education() {
       const education = [
         { id: 1, degree: 'Bachelor of Science', school: 'University of Example', year: '2020' },
         { id: 2, degree: 'High School Diploma', school: 'Example High School', year: '2016' },
       ];

       return (
         <section id="education">
           <h2>Education</h2>
           <ul>
             {education.map((edu) => (
               <li key={edu.id}>
                 <h3>{edu.degree}</h3>
                 <p>{edu.school}, {edu.year}</p>
               </li>
             ))}
           </ul>
         </section>
       );
     }
     export default Education;
     ```  
   - Add CSS in `Education.css`:  
     ```css
     #education ul {
       list-style: none;
       padding: 0;
     }
     #education ul li {
       background-color: #f4f4f4;
       margin: 5px 0;
       padding: 10px;
       border-radius: 5px;
     }
     ```  

3. **Create the `WorkHistory` Component** (1 hr)  
   - In `src/components/WorkHistory.js`:  
     ```javascript
     function WorkHistory() {
       const workHistory = [
         { id: 1, title: 'Web Developer', company: 'Example Corp', year: '2021-Present' },
         { id: 2, title: 'Intern', company: 'Example Startup', year: '2020' },
       ];

       return (
         <section id="work-history">
           <h2>Work History</h2>
           <ul>
             {workHistory.map((work) => (
               <li key={work.id}>
                 <h3>{work.title}</h3>
                 <p>{work.company}, {work.year}</p>
               </li>
             ))}
           </ul>
         </section>
       );
     }
     export default WorkHistory;
     ```  
   - Add CSS in `WorkHistory.css`:  
     ```css
     #work-history ul {
       list-style: none;
       padding: 0;
     }
     #work-history ul li {
       background-color: #f9f9f9;
       margin: 10px 0;
       padding: 15px;
       border-radius: 5px;
       box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
     }
     #work-history ul li h3 {
       margin: 0 0 10px;
     }
     ```  

4. **Add Interactive Features** (1 hr)  
   - Add a button to toggle the visibility of each section in `App.js`.  
   - Update the state to control the visibility of `Education` and `WorkHistory`.  

5. **Style the Buttons** (30 mins)  
   - Add CSS in `App.css`:  
     ```css
     button {
       padding: 10px 20px;
       background-color: #007bff;
       color: white;
       border: none;
       cursor: pointer;
       margin: 10px;
       border-radius: 5px;
     }
     button:hover {
       background-color: #0056b3;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the buttons toggle sections correctly.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 5**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - Interactive buttons to toggle the visibility of `Education` and `WorkHistory` sections.  
   - A `Footer` component with a copyright notice.  
2. State management using `useState` for dynamic UI updates.  
3. A clear understanding of state and its role in React.  

---
---

### **Day 6: CV Application (Styling & Deployment)**  
**Goal**: Add styling to the CV Application, deploy it, and ensure it’s production-ready.  

#### **Theory (1.5 hrs)**  
1. **TOP: Styling React Applications**  
   - Learn about different styling approaches (e.g., CSS Modules, Tailwind, Styled Components).  
   - Understand how to organize styles in a React project.  

2. **FSO Part 2c: Styling (Optional)**  
   - Skim this section for a deeper dive into CSS-in-JS and other styling techniques (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Style the CV Application and deploy it to GitHub Pages.  

1. **Refactor the CV Application** (1 hr)  
   - Open your CV Application project from Day 5.  
   - Organize styles into CSS Modules for better scoping and maintainability.  
   - Update `App.js` to use CSS Modules:  
     ```javascript
     import styles from './App.module.css';
     import Header from './components/Header';
     import Education from './components/Education';
     import WorkHistory from './components/WorkHistory';

     function App() {
       const [showEducation, setShowEducation] = useState(true);
       const [showWorkHistory, setShowWorkHistory] = useState(true);

       return (
         <div className={styles.App}>
           <Header />
           <button
             className={styles.toggleButton}
             onClick={() => setShowEducation(!showEducation)}
           >
             {showEducation ? 'Hide Education' : 'Show Education'}
           </button>
           {showEducation && <Education />}
           <button
             className={styles.toggleButton}
             onClick={() => setShowWorkHistory(!showWorkHistory)}
           >
             {showWorkHistory ? 'Hide Work History' : 'Show Work History'}
           </button>
           {showWorkHistory && <WorkHistory />}
         </div>
       );
     }
     export default App;
     ```  
   - Create `App.module.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
     }
     .toggleButton {
       padding: 10px 20px;
       background-color: #007bff;
       color: white;
       border: none;
       cursor: pointer;
       margin: 10px;
       border-radius: 5px;
     }
     .toggleButton:hover {
       background-color: #0056b3;
     }
     ```  

2. **Style the `Header` Component** (30 mins)  
   - Update `src/components/Header.js` to use CSS Modules:  
     ```javascript
     import styles from './Header.module.css';

     function Header() {
       return (
         <header className={styles.header}>
           <h1>My CV</h1>
         </header>
       );
     }
     export default Header;
     ```  
   - Create `Header.module.css`:  
     ```css
     .header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     ```  

3. **Style the `Education` Component** (30 mins)  
   - Update `src/components/Education.js` to use CSS Modules:  
     ```javascript
     import styles from './Education.module.css';

     function Education() {
       const education = [
         { id: 1, degree: 'Bachelor of Science', school: 'University of Example', year: '2020' },
         { id: 2, degree: 'High School Diploma', school: 'Example High School', year: '2016' },
       ];

       return (
         <section className={styles.education}>
           <h2>Education</h2>
           <ul>
             {education.map((edu) => (
               <li key={edu.id} className={styles.educationItem}>
                 <h3>{edu.degree}</h3>
                 <p>{edu.school}, {edu.year}</p>
               </li>
             ))}
           </ul>
         </section>
       );
     }
     export default Education;
     ```  
   - Create `Education.module.css`:  
     ```css
     .education {
       margin: 20px 0;
     }
     .educationItem {
       background-color: #f4f4f4;
       margin: 5px 0;
       padding: 10px;
       border-radius: 5px;
     }
     ```  

4. **Style the `WorkHistory` Component** (30 mins)  
   - Update `src/components/WorkHistory.js` to use CSS Modules:  
     ```javascript
     import styles from './WorkHistory.module.css';

     function WorkHistory() {
       const workHistory = [
         { id: 1, title: 'Web Developer', company: 'Example Corp', year: '2021-Present' },
         { id: 2, title: 'Intern', company: 'Example Startup', year: '2020' },
       ];

       return (
         <section className={styles.workHistory}>
           <h2>Work History</h2>
           <ul>
             {workHistory.map((work) => (
               <li key={work.id} className={styles.workItem}>
                 <h3>{work.title}</h3>
                 <p>{work.company}, {work.year}</p>
               </li>
             ))}
           </ul>
         </section>
       );
     }
     export default WorkHistory;
     ```  
   - Create `WorkHistory.module.css`:  
     ```css
     .workHistory {
       margin: 20px 0;
     }
     .workItem {
       background-color: #f9f9f9;
       margin: 10px 0;
       padding: 15px;
       border-radius: 5px;
       box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
     }
     .workItem h3 {
       margin: 0 0 10px;
     }
     ```  

5. **Deploy to GitHub Pages** (1 hr)  
   - Install the `gh-pages` package:  
     ```bash
     npm install gh-pages --save-dev
     ```  
   - Update `package.json`:  
     ```json
     "homepage": "https://<your-username>.github.io/<your-repo-name>",
     "scripts": {
       "predeploy": "npm run build",
       "deploy": "gh-pages -d build"
     }
     ```  
   - Deploy the app:  
     ```bash
     npm run deploy
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the app looks good on all screen sizes (use Chrome DevTools).  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 6**  
1. A React app with:  
   - A styled `Header` component.  
   - Interactive buttons to toggle the visibility of `Education` and `WorkHistory` sections.  
   - A `Footer` component with a copyright notice.  
2. Styling using CSS Modules for better scoping and maintainability.  
3. Deployment to GitHub Pages.  

---
---

### **Day 7: Review & Debug**  
**Goal**: Review concepts, debug projects, and reinforce learning through refactoring.  

#### **Theory (1.5 hrs)**  
1. **Review React Fundamentals**  
   - Revisit key concepts: components, props, state, JSX, and event handling.  
   - Understand common pitfalls (e.g., unnecessary re-renders, prop drilling).  

2. **Debugging Techniques**  
   - Learn how to use React DevTools and browser console for debugging.  
   - Understand error messages and stack traces.  

3. **FSO Part 1d: Debugging (Optional)**  
   - Skim this section for a deeper dive into debugging React apps (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Debug and refactor the CV Application and other projects.  

1. **Debug the CV Application** (1 hr)  
   - Open your CV Application project from Day 6.  
   - Use React DevTools to inspect component hierarchy and state.  
   - Fix any issues (e.g., broken styles, missing keys, or incorrect state updates).  

2. **Refactor the CV Application** (1 hr)  
   - Break down large components into smaller, reusable ones (e.g., `SectionToggle` for buttons).  
   - Extract repeated logic into custom hooks (e.g., `useToggle` for visibility toggles).  
   - Example: Create a `useToggle` hook in `src/hooks/useToggle.js`:  
     ```javascript
     import { useState } from 'react';

     export default function useToggle(initialValue = false) {
       const [value, setValue] = useState(initialValue);
       const toggle = () => setValue(!value);
       return [value, toggle];
     }
     ```  
   - Update `App.js` to use the `useToggle` hook:  
     ```javascript
     import useToggle from './hooks/useToggle';
     import Header from './components/Header';
     import Education from './components/Education';
     import WorkHistory from './components/WorkHistory';
     import styles from './App.module.css';

     function App() {
       const [showEducation, toggleEducation] = useToggle(true);
       const [showWorkHistory, toggleWorkHistory] = useToggle(true);

       return (
         <div className={styles.App}>
           <Header />
           <button className={styles.toggleButton} onClick={toggleEducation}>
             {showEducation ? 'Hide Education' : 'Show Education'}
           </button>
           {showEducation && <Education />}
           <button className={styles.toggleButton} onClick={toggleWorkHistory}>
             {showWorkHistory ? 'Hide Work History' : 'Show Work History'}
           </button>
           {showWorkHistory && <WorkHistory />}
         </div>
       );
     }
     export default App;
     ```  

3. **Debug the Memory Card Project** (1 hr)  
   - Open your Memory Card project from Week 2.  
   - Use React DevTools to inspect state and props.  
   - Fix any issues (e.g., incorrect card matching, missing keys, or performance bottlenecks).  

4. **Refactor the Memory Card Project** (1 hr)  
   - Break down large components (e.g., `GameBoard` into `Card` and `Scoreboard`).  
   - Extract repeated logic into custom hooks (e.g., `useGameLogic` for card matching).  
   - Example: Create a `useGameLogic` hook in `src/hooks/useGameLogic.js`:  
     ```javascript
     import { useState } from 'react';

     export default function useGameLogic(cards) {
       const [flippedCards, setFlippedCards] = useState([]);
       const [matchedCards, setMatchedCards] = useState([]);

       const handleCardClick = (index) => {
         if (flippedCards.length === 2 || matchedCards.includes(index)) return;
         setFlippedCards([...flippedCards, index]);

         if (flippedCards.length === 1) {
           const [firstIndex] = flippedCards;
           if (cards[firstIndex] === cards[index]) {
             setMatchedCards([...matchedCards, firstIndex, index]);
           }
           setTimeout(() => setFlippedCards([]), 1000);
         }
       };

       return { flippedCards, matchedCards, handleCardClick };
     }
     ```  
   - Update `GameBoard.js` to use the `useGameLogic` hook:  
     ```javascript
     import useGameLogic from '../hooks/useGameLogic';

     function GameBoard({ cards }) {
       const { flippedCards, matchedCards, handleCardClick } = useGameLogic(cards);

       return (
         <div className="game-board">
           {cards.map((card, index) => (
             <Card
               key={index}
               card={card}
               isFlipped={flippedCards.includes(index)}
               isMatched={matchedCards.includes(index)}
               onClick={() => handleCardClick(index)}
             />
           ))}
         </div>
       );
     }
     export default GameBoard;
     ```  

---

#### **Review (30 mins)**  
1. **Test Your Apps**: Ensure all features work as expected.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 7**  
1. A refactored CV Application with:  
   - Reusable components and custom hooks.  
   - Clean, maintainable code.  
2. A refactored Memory Card project with:  
   - Improved component structure and custom hooks.  
   - Better performance and readability.  
3. A clear understanding of debugging and refactoring techniques.  

---
---

### **Day 8: Side Effects & `useEffect`**  
**Goal**: Understand side effects, master `useEffect`, and build an API-driven app.  

#### **Theory (1.5 hrs)**  
1. **TOP: How to Deal With Side Effects**  
   - Learn about side effects in React (e.g., data fetching, subscriptions, DOM manipulation).  
   - Understand the purpose of the `useEffect` hook.  

2. **FSO Part 2a: Rendering Collections (Optional)**  
   - Skim this section for a deeper dive into fetching and rendering data (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Build a weather app that fetches data from an API using `useEffect`.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app weather-app`.  
   - Clean up the default template (remove unused files and code).  

2. **Plan the Component Hierarchy** (30 mins)  
   - Design a simple app with the following structure:  
     ```
     App
     ├── Header
     ├── WeatherDisplay
     │   ├── WeatherInfo
     │   └── WeatherForecast
     └── Footer
     ```  
   - Sketch the layout on paper or in a tool like Figma.  

3. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     function Header() {
       return (
         <header>
           <h1>Weather App</h1>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     ```  

4. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 Weather App</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

5. **Create the `WeatherDisplay` Component** (1 hr)  
   - In `src/components/WeatherDisplay.js`:  
     ```javascript
     import { useEffect, useState } from 'react';
     import WeatherInfo from './WeatherInfo';
     import WeatherForecast from './WeatherForecast';

     function WeatherDisplay({ city }) {
       const [weatherData, setWeatherData] = useState(null);
       const [loading, setLoading] = useState(true);
       const [error, setError] = useState(null);

       useEffect(() => {
         const fetchWeather = async () => {
           try {
             const response = await fetch(
               `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=YOUR_API_KEY&units=metric`
             );
             if (!response.ok) throw new Error('Failed to fetch weather data');
             const data = await response.json();
             setWeatherData(data);
           } catch (err) {
             setError(err.message);
           } finally {
             setLoading(false);
           }
         };

         fetchWeather();
       }, [city]);

       if (loading) return <p>Loading...</p>;
       if (error) return <p>Error: {error}</p>;

       return (
         <main>
           <WeatherInfo data={weatherData} />
           <WeatherForecast data={weatherData} />
         </main>
       );
     }
     export default WeatherDisplay;
     ```  

6. **Create the `WeatherInfo` Component** (1 hr)  
   - In `src/components/WeatherInfo.js`:  
     ```javascript
     function WeatherInfo({ data }) {
       return (
         <section id="weather-info">
           <h2>{data.name}</h2>
           <p>Temperature: {data.main.temp}°C</p>
           <p>Weather: {data.weather[0].description}</p>
         </section>
       );
     }
     export default WeatherInfo;
     ```  
   - Add CSS in `WeatherInfo.css`:  
     ```css
     #weather-info {
       margin: 20px 0;
     }
     #weather-info h2 {
       margin: 0 0 10px;
     }
     ```  

7. **Create the `WeatherForecast` Component** (1 hr)  
   - In `src/components/WeatherForecast.js`:  
     ```javascript
     function WeatherForecast({ data }) {
       return (
         <section id="weather-forecast">
           <h2>Forecast</h2>
           <ul>
             <li>Humidity: {data.main.humidity}%</li>
             <li>Wind Speed: {data.wind.speed} m/s</li>
           </ul>
         </section>
       );
     }
     export default WeatherForecast;
     ```  
   - Add CSS in `WeatherForecast.css`:  
     ```css
     #weather-forecast {
       margin: 20px 0;
     }
     #weather-forecast ul {
       list-style: none;
       padding: 0;
     }
     #weather-forecast ul li {
       background-color: #f4f4f4;
       margin: 5px 0;
       padding: 10px;
       border-radius: 5px;
     }
     ```  

8. **Assemble the App** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import Header from './components/Header';
     import WeatherDisplay from './components/WeatherDisplay';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       return (
         <div className="App">
           <Header />
           <WeatherDisplay city="London" />
           <Footer />
         </div>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the weather data displays correctly.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 8**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - A `WeatherDisplay` component fetching and displaying weather data.  
   - A `Footer` component with a copyright notice.  
2. API integration using `useEffect` and `fetch`.  
3. A clear understanding of side effects and `useEffect`.  

---
---

### **Day 9: Memory Card Project (Setup)**  
**Goal**: Build the Memory Card game, focusing on state management and user interaction.  

#### **Theory (1.5 hrs)**  
1. **TOP: State and Props Review**  
   - Revisit state and props to reinforce understanding.  
   - Understand how to manage complex state in a game.  

2. **FSO Part 2b: Forms (Optional)**  
   - Skim this section for a deeper dive into handling user input (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Build the core functionality of the Memory Card game.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app memory-card-game`.  
   - Clean up the default template (remove unused files and code).  

2. **Plan the Component Hierarchy** (30 mins)  
   - Design a simple app with the following structure:  
     ```
     App
     ├── Header
     ├── GameBoard
     │   ├── Card
     │   └── Scoreboard
     └── Footer
     ```  
   - Sketch the layout on paper or in a tool like Figma.  

3. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     function Header() {
       return (
         <header>
           <h1>Memory Card Game</h1>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     ```  

4. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 Memory Card Game</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

5. **Create the `GameBoard` Component** (1 hr)  
   - In `src/components/GameBoard.js`:  
     ```javascript
     import { useState } from 'react';
     import Card from './Card';
     import Scoreboard from './Scoreboard';

     const cards = [
       { id: 1, emoji: '🐶', flipped: false, matched: false },
       { id: 2, emoji: '🐱', flipped: false, matched: false },
       { id: 3, emoji: '🐭', flipped: false, matched: false },
       { id: 4, emoji: '🐹', flipped: false, matched: false },
       { id: 5, emoji: '🐰', flipped: false, matched: false },
       { id: 6, emoji: '🦊', flipped: false, matched: false },
     ];

     function GameBoard() {
       const [flippedCards, setFlippedCards] = useState([]);
       const [matchedCards, setMatchedCards] = useState([]);

       const handleCardClick = (id) => {
         if (flippedCards.length === 2 || matchedCards.includes(id)) return;
         setFlippedCards([...flippedCards, id]);

         if (flippedCards.length === 1) {
           const [firstId] = flippedCards;
           if (cards[firstId - 1].emoji === cards[id - 1].emoji) {
             setMatchedCards([...matchedCards, firstId, id]);
           }
           setTimeout(() => setFlippedCards([]), 1000);
         }
       };

       return (
         <div className="game-board">
           {cards.map((card) => (
             <Card
               key={card.id}
               card={card}
               isFlipped={flippedCards.includes(card.id)}
               isMatched={matchedCards.includes(card.id)}
               onClick={() => handleCardClick(card.id)}
             />
           ))}
           <Scoreboard matchedCards={matchedCards} />
         </div>
       );
     }
     export default GameBoard;
     ```  

6. **Create the `Card` Component** (1 hr)  
   - In `src/components/Card.js`:  
     ```javascript
     function Card({ card, isFlipped, isMatched, onClick }) {
       return (
         <div
           className={`card ${isFlipped || isMatched ? 'flipped' : ''}`}
           onClick={onClick}
         >
           {isFlipped || isMatched ? card.emoji : '❓'}
         </div>
       );
     }
     export default Card;
     ```  
   - Add CSS in `Card.css`:  
     ```css
     .card {
       width: 100px;
       height: 100px;
       background-color: #f4f4f4;
       margin: 10px;
       display: flex;
       justify-content: center;
       align-items: center;
       font-size: 2rem;
       cursor: pointer;
       border-radius: 10px;
       box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
       transition: transform 0.3s ease;
     }
     .card.flipped {
       background-color: #fff;
       transform: rotateY(180deg);
     }
     ```  

7. **Create the `Scoreboard` Component** (1 hr)  
   - In `src/components/Scoreboard.js`:  
     ```javascript
     function Scoreboard({ matchedCards }) {
       return (
         <div className="scoreboard">
           <h2>Score: {matchedCards.length / 2}</h2>
         </div>
       );
     }
     export default Scoreboard;
     ```  
   - Add CSS in `Scoreboard.css`:  
     ```css
     .scoreboard {
       margin: 20px 0;
       text-align: center;
     }
     ```  

8. **Assemble the App** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import Header from './components/Header';
     import GameBoard from './components/GameBoard';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       return (
         <div className="App">
           <Header />
           <GameBoard />
           <Footer />
         </div>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
     }
     .game-board {
       display: flex;
       flex-wrap: wrap;
       justify-content: center;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the game logic works correctly.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 9**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - A `GameBoard` component managing card state and interactions.  
   - A `Footer` component with a copyright notice.  
2. Core game functionality: flipping cards, matching pairs, and tracking score.  
3. A clear understanding of state management in games.  

---
---

### **Day 10: Memory Card Project (Finish)**  
**Goal**: Complete the Memory Card game, add polish, and deploy it.  

#### **Theory (1.5 hrs)**  
1. **TOP: Styling React Applications**  
   - Learn about advanced styling techniques (e.g., animations, transitions).  
   - Understand how to make your app visually appealing.  

2. **FSO Part 2c: Styling (Optional)**  
   - Skim this section for a deeper dive into CSS-in-JS and animations (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Add animations, improve UI, and deploy the Memory Card game.  

1. **Add Animations to the `Card` Component** (1 hr)  
   - Update `src/components/Card.js` to include flip animations:  
     ```javascript
     import { useEffect, useState } from 'react';
     import './Card.css';

     function Card({ card, isFlipped, isMatched, onClick }) {
       const [isAnimating, setIsAnimating] = useState(false);

       useEffect(() => {
         if (isFlipped || isMatched) {
           setIsAnimating(true);
           setTimeout(() => setIsAnimating(false), 300);
         }
       }, [isFlipped, isMatched]);

       return (
         <div
           className={`card ${isFlipped || isMatched ? 'flipped' : ''} ${isAnimating ? 'animating' : ''}`}
           onClick={onClick}
         >
           {isFlipped || isMatched ? card.emoji : '❓'}
         </div>
       );
     }
     export default Card;
     ```  
   - Update `Card.css` for animations:  
     ```css
     .card {
       width: 100px;
       height: 100px;
       background-color: #f4f4f4;
       margin: 10px;
       display: flex;
       justify-content: center;
       align-items: center;
       font-size: 2rem;
       cursor: pointer;
       border-radius: 10px;
       box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
       transition: transform 0.3s ease, background-color 0.3s ease;
     }
     .card.flipped {
       background-color: #fff;
       transform: rotateY(180deg);
     }
     .card.animating {
       animation: flip 0.3s ease;
     }
     @keyframes flip {
       0% { transform: rotateY(0); }
       50% { transform: rotateY(90deg); }
       100% { transform: rotateY(180deg); }
     }
     ```  

2. **Improve the `Scoreboard` Component** (1 hr)  
   - Update `src/components/Scoreboard.js` to show progress:  
     ```javascript
     function Scoreboard({ matchedCards, totalCards }) {
       return (
         <div className="scoreboard">
           <h2>Score: {matchedCards.length / 2}</h2>
           <p>Progress: {(matchedCards.length / totalCards) * 100}%</p>
         </div>
       );
     }
     export default Scoreboard;
     ```  
   - Update `GameBoard.js` to pass `totalCards`:  
     ```javascript
     <Scoreboard matchedCards={matchedCards} totalCards={cards.length} />
     ```  
   - Add CSS in `Scoreboard.css`:  
     ```css
     .scoreboard {
       margin: 20px 0;
       text-align: center;
     }
     .scoreboard p {
       margin: 5px 0;
     }
     ```  

3. **Add a Reset Button** (1 hr)  
   - Update `src/components/GameBoard.js` to include a reset button:  
     ```javascript
     const resetGame = () => {
       setFlippedCards([]);
       setMatchedCards([]);
     };

     return (
       <div className="game-board">
         {cards.map((card) => (
           <Card
             key={card.id}
             card={card}
             isFlipped={flippedCards.includes(card.id)}
             isMatched={matchedCards.includes(card.id)}
             onClick={() => handleCardClick(card.id)}
           />
         ))}
         <Scoreboard matchedCards={matchedCards} totalCards={cards.length} />
         <button className="reset-button" onClick={resetGame}>Reset Game</button>
       </div>
     );
     ```  
   - Add CSS for the reset button:  
     ```css
     .reset-button {
       padding: 10px 20px;
       background-color: #007bff;
       color: white;
       border: none;
       cursor: pointer;
       margin: 20px;
       border-radius: 5px;
     }
     .reset-button:hover {
       background-color: #0056b3;
     }
     ```  

4. **Deploy to GitHub Pages** (1 hr)  
   - Install the `gh-pages` package:  
     ```bash
     npm install gh-pages --save-dev
     ```  
   - Update `package.json`:  
     ```json
     "homepage": "https://<your-username>.github.io/<your-repo-name>",
     "scripts": {
       "predeploy": "npm run build",
       "deploy": "gh-pages -d build"
     }
     ```  
   - Deploy the app:  
     ```bash
     npm run deploy
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure all features work as expected.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 10**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - A `GameBoard` component with animations and a reset button.  
   - A `Footer` component with a copyright notice.  
2. Animations for card flipping and progress tracking.  
3. Deployment to GitHub Pages.  

---
---

### **Day 11: Class-Based Components**  
**Goal**: Understand class-based components, lifecycle methods, and refactor a functional component.  

#### **Theory (1.5 hrs)**  
1. **TOP: Class-Based Components**  
   - Learn about class-based components and their syntax.  
   - Understand the difference between functional and class-based components.  

2. **TOP: Component Lifecycle Methods**  
   - Explore lifecycle methods (e.g., `componentDidMount`, `componentDidUpdate`, `componentWillUnmount`).  
   - Understand when to use lifecycle methods.  

3. **FSO Part 1d: Class Components (Optional)**  
   - Skim this section for a deeper dive into class components (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Convert a functional component to a class-based component and implement lifecycle methods.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app class-components-demo`.  
   - Clean up the default template (remove unused files and code).  

2. **Plan the Component Hierarchy** (30 mins)  
   - Design a simple app with the following structure:  
     ```
     App
     ├── Header
     ├── Timer
     └── Footer
     ```  
   - Sketch the layout on paper or in a tool like Figma.  

3. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     function Header() {
       return (
         <header>
           <h1>Class Components Demo</h1>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     ```  

4. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 Class Components Demo</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

5. **Create the `Timer` Component (Functional)** (1 hr)  
   - In `src/components/Timer.js`:  
     ```javascript
     import { useState, useEffect } from 'react';

     function Timer() {
       const [time, setTime] = useState(0);

       useEffect(() => {
         const interval = setInterval(() => {
           setTime((prevTime) => prevTime + 1);
         }, 1000);

         return () => clearInterval(interval);
       }, []);

       return (
         <div className="timer">
           <h2>Timer: {time} seconds</h2>
         </div>
       );
     }
     export default Timer;
     ```  
   - Add CSS in `Timer.css`:  
     ```css
     .timer {
       margin: 20px 0;
       text-align: center;
     }
     ```  

6. **Convert `Timer` to a Class-Based Component** (1 hr)  
   - Update `src/components/Timer.js`:  
     ```javascript
     import React from 'react';
     import './Timer.css';

     class Timer extends React.Component {
       constructor(props) {
         super(props);
         this.state = {
           time: 0,
         };
       }

       componentDidMount() {
         this.interval = setInterval(() => {
           this.setState((prevState) => ({ time: prevState.time + 1 }));
         }, 1000);
       }

       componentWillUnmount() {
         clearInterval(this.interval);
       }

       render() {
         return (
           <div className="timer">
             <h2>Timer: {this.state.time} seconds</h2>
           </div>
         );
       }
     }
     export default Timer;
     ```  

7. **Assemble the App** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import Header from './components/Header';
     import Timer from './components/Timer';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       return (
         <div className="App">
           <Header />
           <Timer />
           <Footer />
         </div>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the timer works correctly.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 11**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - A `Timer` component implemented as a class-based component.  
   - A `Footer` component with a copyright notice.  
2. A clear understanding of class-based components and lifecycle methods.  

---
---

### **Day 12: React Testing**  
**Goal**: Learn how to test React components using Jest and React Testing Library (RTL).  

#### **Theory (1.5 hrs)**  
1. **TOP: Introduction to React Testing**  
   - Learn about the importance of testing in React applications.  
   - Understand the basics of Jest and React Testing Library.  

2. **FSO Part 5a: Testing React Apps (Optional)**  
   - Skim this section for a deeper dive into testing techniques (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Write tests for the CV Application and Memory Card game.  

1. **Set Up Testing in the CV Application** (1 hr)  
   - Open your CV Application project from Day 6.  
   - Install React Testing Library:  
     ```bash
     npm install @testing-library/react @testing-library/jest-dom --save-dev
     ```  
   - Create a test file for the `Header` component (`src/components/Header.test.js`):  
     ```javascript
     import { render, screen } from '@testing-library/react';
     import Header from './Header';

     test('renders the header title', () => {
       render(<Header />);
       const titleElement = screen.getByText(/My CV/i);
       expect(titleElement).toBeInTheDocument();
     });
     ```  
   - Run the test:  
     ```bash
     npm test
     ```  

2. **Test the `Education` Component** (1 hr)  
   - Create a test file for the `Education` component (`src/components/Education.test.js`):  
     ```javascript
     import { render, screen } from '@testing-library/react';
     import Education from './Education';

     test('renders education items', () => {
       render(<Education />);
       const degreeElement = screen.getByText(/Bachelor of Science/i);
       const schoolElement = screen.getByText(/University of Example/i);
       expect(degreeElement).toBeInTheDocument();
       expect(schoolElement).toBeInTheDocument();
     });
     ```  
   - Run the test:  
     ```bash
     npm test
     ```  

3. **Test the `WorkHistory` Component** (1 hr)  
   - Create a test file for the `WorkHistory` component (`src/components/WorkHistory.test.js`):  
     ```javascript
     import { render, screen } from '@testing-library/react';
     import WorkHistory from './WorkHistory';

     test('renders work history items', () => {
       render(<WorkHistory />);
       const titleElement = screen.getByText(/Web Developer/i);
       const companyElement = screen.getByText(/Example Corp/i);
       expect(titleElement).toBeInTheDocument();
       expect(companyElement).toBeInTheDocument();
     });
     ```  
   - Run the test:  
     ```bash
     npm test
     ```  

4. **Set Up Testing in the Memory Card Game** (1 hr)  
   - Open your Memory Card game project from Day 10.  
   - Install React Testing Library:  
     ```bash
     npm install @testing-library/react @testing-library/jest-dom --save-dev
     ```  
   - Create a test file for the `Card` component (`src/components/Card.test.js`):  
     ```javascript
     import { render, screen } from '@testing-library/react';
     import Card from './Card';

     const card = { id: 1, emoji: '🐶', flipped: false, matched: false };

     test('renders the card back initially', () => {
       render(<Card card={card} isFlipped={false} isMatched={false} onClick={() => {}} />);
       const cardBackElement = screen.getByText(/❓/i);
       expect(cardBackElement).toBeInTheDocument();
     });

     test('renders the card front when flipped', () => {
       render(<Card card={card} isFlipped={true} isMatched={false} onClick={() => {}} />);
       const cardFrontElement = screen.getByText(/🐶/i);
       expect(cardFrontElement).toBeInTheDocument();
     });
     ```  
   - Run the test:  
     ```bash
     npm test
     ```  

---

#### **Review (30 mins)**  
1. **Test Your Apps**: Ensure all tests pass.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 12**  
1. A React app with:  
   - Tests for the `Header`, `Education`, and `WorkHistory` components in the CV Application.  
   - Tests for the `Card` component in the Memory Card game.  
2. A clear understanding of testing React components with Jest and RTL.  

---
---

### **Day 13: Type Checking With PropTypes**  
**Goal**: Learn how to use PropTypes for type checking and improve code reliability.  

#### **Theory (1.5 hrs)**  
1. **TOP: Type Checking With PropTypes**  
   - Learn about PropTypes and their role in type checking.  
   - Understand how to define PropTypes for components.  

2. **FSO Part 1d: PropTypes (Optional)**  
   - Skim this section for a deeper dive into PropTypes (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Add PropTypes to the CV Application and Memory Card game.  

1. **Set Up PropTypes in the CV Application** (1 hr)  
   - Open your CV Application project from Day 6.  
   - Install PropTypes:  
     ```bash
     npm install prop-types
     ```  
   - Add PropTypes to the `Header` component (`src/components/Header.js`):  
     ```javascript
     import PropTypes from 'prop-types';

     function Header({ title }) {
       return (
         <header>
           <h1>{title}</h1>
         </header>
       );
     }

     Header.propTypes = {
       title: PropTypes.string.isRequired,
     };

     export default Header;
     ```  
   - Update `App.js` to pass the `title` prop:  
     ```javascript
     <Header title="My CV" />
     ```  

2. **Add PropTypes to the `Education` Component** (1 hr)  
   - Update `src/components/Education.js`:  
     ```javascript
     import PropTypes from 'prop-types';

     function Education({ education }) {
       return (
         <section id="education">
           <h2>Education</h2>
           <ul>
             {education.map((edu) => (
               <li key={edu.id}>
                 <h3>{edu.degree}</h3>
                 <p>{edu.school}, {edu.year}</p>
               </li>
             ))}
           </ul>
         </section>
       );
     }

     Education.propTypes = {
       education: PropTypes.arrayOf(
         PropTypes.shape({
           id: PropTypes.number.isRequired,
           degree: PropTypes.string.isRequired,
           school: PropTypes.string.isRequired,
           year: PropTypes.string.isRequired,
         })
       ).isRequired,
     };

     export default Education;
     ```  
   - Update `App.js` to pass the `education` prop:  
     ```javascript
     const education = [
       { id: 1, degree: 'Bachelor of Science', school: 'University of Example', year: '2020' },
       { id: 2, degree: 'High School Diploma', school: 'Example High School', year: '2016' },
     ];

     <Education education={education} />
     ```  

3. **Add PropTypes to the `WorkHistory` Component** (1 hr)  
   - Update `src/components/WorkHistory.js`:  
     ```javascript
     import PropTypes from 'prop-types';

     function WorkHistory({ workHistory }) {
       return (
         <section id="work-history">
           <h2>Work History</h2>
           <ul>
             {workHistory.map((work) => (
               <li key={work.id}>
                 <h3>{work.title}</h3>
                 <p>{work.company}, {work.year}</p>
               </li>
             ))}
           </ul>
         </section>
       );
     }

     WorkHistory.propTypes = {
       workHistory: PropTypes.arrayOf(
         PropTypes.shape({
           id: PropTypes.number.isRequired,
           title: PropTypes.string.isRequired,
           company: PropTypes.string.isRequired,
           year: PropTypes.string.isRequired,
         })
       ).isRequired,
     };

     export default WorkHistory;
     ```  
   - Update `App.js` to pass the `workHistory` prop:  
     ```javascript
     const workHistory = [
       { id: 1, title: 'Web Developer', company: 'Example Corp', year: '2021-Present' },
       { id: 2, title: 'Intern', company: 'Example Startup', year: '2020' },
     ];

     <WorkHistory workHistory={workHistory} />
     ```  

4. **Set Up PropTypes in the Memory Card Game** (1 hr)  
   - Open your Memory Card game project from Day 10.  
   - Install PropTypes:  
     ```bash
     npm install prop-types
     ```  
   - Add PropTypes to the `Card` component (`src/components/Card.js`):  
     ```javascript
     import PropTypes from 'prop-types';

     function Card({ card, isFlipped, isMatched, onClick }) {
       return (
         <div
           className={`card ${isFlipped || isMatched ? 'flipped' : ''}`}
           onClick={onClick}
         >
           {isFlipped || isMatched ? card.emoji : '❓'}
         </div>
       );
     }

     Card.propTypes = {
       card: PropTypes.shape({
         id: PropTypes.number.isRequired,
         emoji: PropTypes.string.isRequired,
         flipped: PropTypes.bool.isRequired,
         matched: PropTypes.bool.isRequired,
       }).isRequired,
       isFlipped: PropTypes.bool.isRequired,
       isMatched: PropTypes.bool.isRequired,
       onClick: PropTypes.func.isRequired,
     };

     export default Card;
     ```  

---

#### **Review (30 mins)**  
1. **Test Your Apps**: Ensure no PropTypes warnings appear in the console.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 13**  
1. A React app with:  
   - PropTypes for the `Header`, `Education`, and `WorkHistory` components in the CV Application.  
   - PropTypes for the `Card` component in the Memory Card game.  
2. A clear understanding of PropTypes and their role in type checking.  

---
---

### **Day 14: React Router**  
**Goal**: Learn how to use React Router for navigation in a multi-page app.  

#### **Theory (1.5 hrs)**  
1. **TOP: React Router**  
   - Learn about React Router and its role in client-side routing.  
   - Understand the difference between `BrowserRouter`, `Route`, and `Link`.  

2. **FSO Part 3a: Routing (Optional)**  
   - Skim this section for a deeper dive into routing techniques (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Build a multi-page portfolio app with React Router.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app portfolio-app`.  
   - Clean up the default template (remove unused files and code).  

2. **Install React Router** (30 mins)  
   - Install React Router:  
     ```bash
     npm install react-router-dom
     ```  

3. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     import { Link } from 'react-router-dom';

     function Header() {
       return (
         <header>
           <h1>My Portfolio</h1>
           <nav>
             <ul>
               <li><Link to="/">Home</Link></li>
               <li><Link to="/about">About</Link></li>
               <li><Link to="/projects">Projects</Link></li>
             </ul>
           </nav>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     nav ul {
       list-style: none;
       padding: 0;
     }
     nav ul li {
       display: inline;
       margin: 0 10px;
     }
     nav ul li a {
       color: white;
       text-decoration: none;
     }
     ```  

4. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 My Portfolio</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

5. **Create the `Home` Component** (30 mins)  
   - In `src/components/Home.js`:  
     ```javascript
     function Home() {
       return (
         <section id="home">
           <h2>Welcome to My Portfolio</h2>
           <p>Explore my projects and learn more about me.</p>
         </section>
       );
     }
     export default Home;
     ```  
   - Add CSS in `Home.css`:  
     ```css
     #home {
       margin: 20px 0;
       text-align: center;
     }
     ```  

6. **Create the `About` Component** (30 mins)  
   - In `src/components/About.js`:  
     ```javascript
     function About() {
       return (
         <section id="about">
           <h2>About Me</h2>
           <p>I'm a web developer passionate about building user-friendly applications.</p>
         </section>
       );
     }
     export default About;
     ```  
   - Add CSS in `About.css`:  
     ```css
     #about {
       margin: 20px 0;
       text-align: center;
     }
     ```  

7. **Create the `Projects` Component** (30 mins)  
   - In `src/components/Projects.js`:  
     ```javascript
     function Projects() {
       return (
         <section id="projects">
           <h2>Projects</h2>
           <ul>
             <li>Project 1</li>
             <li>Project 2</li>
             <li>Project 3</li>
           </ul>
         </section>
       );
     }
     export default Projects;
     ```  
   - Add CSS in `Projects.css`:  
     ```css
     #projects {
       margin: 20px 0;
       text-align: center;
     }
     #projects ul {
       list-style: none;
       padding: 0;
     }
     #projects ul li {
       background-color: #f4f4f4;
       margin: 5px 0;
       padding: 10px;
       border-radius: 5px;
     }
     ```  

8. **Set Up Routing in `App.js`** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import { BrowserRouter as Router, Route, Routes } from 'react-router-dom';
     import Header from './components/Header';
     import Home from './components/Home';
     import About from './components/About';
     import Projects from './components/Projects';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       return (
         <Router>
           <div className="App">
             <Header />
             <Routes>
               <Route path="/" element={<Home />} />
               <Route path="/about" element={<About />} />
               <Route path="/projects" element={<Projects />} />
             </Routes>
             <Footer />
           </div>
         </Router>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure all routes work correctly.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 14**  
1. A React app with:  
   - A `Header` component with navigation links.  
   - A `Footer` component with a copyright notice.  
   - `Home`, `About`, and `Projects` components for different routes.  
2. A clear understanding of React Router and client-side routing.  

---
---

### **Day 15: Fetching Data in React**  
**Goal**: Learn how to fetch data from an API and display it in a React app.  

#### **Theory (1.5 hrs)**  
1. **TOP: Fetching Data in React**  
   - Learn about fetching data using `fetch` and `useEffect`.  
   - Understand how to handle loading and error states.  

2. **FSO Part 2b: Communicating with Server (Optional)**  
   - Skim this section for a deeper dive into API integration (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Build a GitHub user profile viewer that fetches and displays user data.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app github-profile-viewer`.  
   - Clean up the default template (remove unused files and code).  

2. **Plan the Component Hierarchy** (30 mins)  
   - Design a simple app with the following structure:  
     ```
     App
     ├── Header
     ├── UserProfile
     │   ├── UserInfo
     │   └── UserRepos
     └── Footer
     ```  
   - Sketch the layout on paper or in a tool like Figma.  

3. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     function Header() {
       return (
         <header>
           <h1>GitHub Profile Viewer</h1>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     ```  

4. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 GitHub Profile Viewer</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

5. **Create the `UserProfile` Component** (1 hr)  
   - In `src/components/UserProfile.js`:  
     ```javascript
     import { useEffect, useState } from 'react';
     import UserInfo from './UserInfo';
     import UserRepos from './UserRepos';

     function UserProfile({ username }) {
       const [userData, setUserData] = useState(null);
       const [repos, setRepos] = useState([]);
       const [loading, setLoading] = useState(true);
       const [error, setError] = useState(null);

       useEffect(() => {
         const fetchData = async () => {
           try {
             const userResponse = await fetch(`https://api.github.com/users/${username}`);
             if (!userResponse.ok) throw new Error('Failed to fetch user data');
             const userData = await userResponse.json();
             setUserData(userData);

             const reposResponse = await fetch(userData.repos_url);
             if (!reposResponse.ok) throw new Error('Failed to fetch repos');
             const reposData = await reposResponse.json();
             setRepos(reposData);
           } catch (err) {
             setError(err.message);
           } finally {
             setLoading(false);
           }
         };

         fetchData();
       }, [username]);

       if (loading) return <p>Loading...</p>;
       if (error) return <p>Error: {error}</p>;

       return (
         <main>
           <UserInfo user={userData} />
           <UserRepos repos={repos} />
         </main>
       );
     }
     export default UserProfile;
     ```  

6. **Create the `UserInfo` Component** (1 hr)  
   - In `src/components/UserInfo.js`:  
     ```javascript
     function UserInfo({ user }) {
       return (
         <section id="user-info">
           <h2>{user.name}</h2>
           <p>{user.bio}</p>
           <p>Followers: {user.followers}</p>
           <p>Following: {user.following}</p>
         </section>
       );
     }
     export default UserInfo;
     ```  
   - Add CSS in `UserInfo.css`:  
     ```css
     #user-info {
       margin: 20px 0;
       text-align: center;
     }
     #user-info h2 {
       margin: 0 0 10px;
     }
     ```  

7. **Create the `UserRepos` Component** (1 hr)  
   - In `src/components/UserRepos.js`:  
     ```javascript
     function UserRepos({ repos }) {
       return (
         <section id="user-repos">
           <h2>Repositories</h2>
           <ul>
             {repos.map((repo) => (
               <li key={repo.id}>
                 <h3>{repo.name}</h3>
                 <p>{repo.description}</p>
               </li>
             ))}
           </ul>
         </section>
       );
     }
     export default UserRepos;
     ```  
   - Add CSS in `UserRepos.css`:  
     ```css
     #user-repos {
       margin: 20px 0;
       text-align: center;
     }
     #user-repos ul {
       list-style: none;
       padding: 0;
     }
     #user-repos ul li {
       background-color: #f4f4f4;
       margin: 5px 0;
       padding: 10px;
       border-radius: 5px;
     }
     ```  

8. **Assemble the App** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import Header from './components/Header';
     import UserProfile from './components/UserProfile';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       return (
         <div className="App">
           <Header />
           <UserProfile username="octocat" />
           <Footer />
         </div>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the GitHub data displays correctly.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 15**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - A `UserProfile` component fetching and displaying GitHub user data.  
   - A `Footer` component with a copyright notice.  
2. API integration using `fetch` and `useEffect`.  
3. A clear understanding of fetching data in React.  

---
---

### **Day 16: Managing State With Context API**  
**Goal**: Learn how to use the Context API for global state management.  

#### **Theory (1.5 hrs)**  
1. **TOP: Managing State With the Context API**  
   - Learn about the Context API and its role in global state management.  
   - Understand how to avoid prop drilling with Context.  

2. **FSO Part 3b: State Management (Optional)**  
   - Skim this section for a deeper dive into Context API (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Build a theme switcher using the Context API.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app theme-switcher`.  
   - Clean up the default template (remove unused files and code).  

2. **Plan the Component Hierarchy** (30 mins)  
   - Design a simple app with the following structure:  
     ```
     App
     ├── Header
     ├── Main
     │   ├── Content
     │   └── ThemeToggle
     └── Footer
     ```  
   - Sketch the layout on paper or in a tool like Figma.  

3. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     function Header() {
       return (
         <header>
           <h1>Theme Switcher</h1>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     ```  

4. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 Theme Switcher</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

5. **Create the `ThemeContext`** (1 hr)  
   - Create a new file `src/context/ThemeContext.js`:  
     ```javascript
     import { createContext, useState } from 'react';

     const ThemeContext = createContext();

     export function ThemeProvider({ children }) {
       const [theme, setTheme] = useState('light');

       const toggleTheme = () => {
         setTheme((prevTheme) => (prevTheme === 'light' ? 'dark' : 'light'));
       };

       return (
         <ThemeContext.Provider value={{ theme, toggleTheme }}>
           {children}
         </ThemeContext.Provider>
       );
     }

     export default ThemeContext;
     ```  

6. **Create the `Content` Component** (1 hr)  
   - In `src/components/Content.js`:  
     ```javascript
     import { useContext } from 'react';
     import ThemeContext from '../context/ThemeContext';

     function Content() {
       const { theme } = useContext(ThemeContext);

       return (
         <section className={`content ${theme}`}>
           <h2>Welcome to the Theme Switcher</h2>
           <p>Current theme: {theme}</p>
         </section>
       );
     }
     export default Content;
     ```  
   - Add CSS in `Content.css`:  
     ```css
     .content {
       margin: 20px 0;
       padding: 20px;
       text-align: center;
       border-radius: 10px;
     }
     .content.light {
       background-color: #f4f4f4;
       color: #333;
     }
     .content.dark {
       background-color: #333;
       color: white;
     }
     ```  

7. **Create the `ThemeToggle` Component** (1 hr)  
   - In `src/components/ThemeToggle.js`:  
     ```javascript
     import { useContext } from 'react';
     import ThemeContext from '../context/ThemeContext';

     function ThemeToggle() {
       const { toggleTheme } = useContext(ThemeContext);

       return (
         <button onClick={toggleTheme}>
           Toggle Theme
         </button>
       );
     }
     export default ThemeToggle;
     ```  
   - Add CSS in `ThemeToggle.css`:  
     ```css
     button {
       padding: 10px 20px;
       background-color: #007bff;
       color: white;
       border: none;
       cursor: pointer;
       margin: 20px;
       border-radius: 5px;
     }
     button:hover {
       background-color: #0056b3;
     }
     ```  

8. **Assemble the App** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import { ThemeProvider } from './context/ThemeContext';
     import Header from './components/Header';
     import Content from './components/Content';
     import ThemeToggle from './components/ThemeToggle';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       return (
         <ThemeProvider>
           <div className="App">
             <Header />
             <Content />
             <ThemeToggle />
             <Footer />
           </div>
         </ThemeProvider>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the theme toggles correctly.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 16**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - A `Content` component displaying the current theme.  
   - A `ThemeToggle` component for switching themes.  
   - A `Footer` component with a copyright notice.  
2. Global state management using the Context API.  
3. A clear understanding of the Context API and its use cases.  

---
---

### **Day 17: Reducing State With `useReducer`**  
**Goal**: Learn how to manage complex state logic using `useReducer`.  

#### **Theory (1.5 hrs)**  
1. **TOP: Reducing State**  
   - Learn about `useReducer` and its role in managing complex state.  
   - Understand the difference between `useState` and `useReducer`.  

2. **FSO Part 3c: Reducers (Optional)**  
   - Skim this section for a deeper dive into `useReducer` (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Build a task manager app using `useReducer`.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app task-manager`.  
   - Clean up the default template (remove unused files and code).  

2. **Plan the Component Hierarchy** (30 mins)  
   - Design a simple app with the following structure:  
     ```
     App
     ├── Header
     ├── TaskList
     │   ├── Task
     │   └── AddTask
     └── Footer
     ```  
   - Sketch the layout on paper or in a tool like Figma.  

3. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     function Header() {
       return (
         <header>
           <h1>Task Manager</h1>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     ```  

4. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 Task Manager</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

5. **Create the `TaskList` Component** (1 hr)  
   - In `src/components/TaskList.js`:  
     ```javascript
     import { useReducer } from 'react';
     import Task from './Task';
     import AddTask from './AddTask';

     const initialState = [];

     function taskReducer(state, action) {
       switch (action.type) {
         case 'ADD_TASK':
           return [...state, { id: Date.now(), text: action.text, completed: false }];
         case 'TOGGLE_TASK':
           return state.map((task) =>
             task.id === action.id ? { ...task, completed: !task.completed } : task
           );
         case 'DELETE_TASK':
           return state.filter((task) => task.id !== action.id);
         default:
           return state;
       }
     }

     function TaskList() {
       const [tasks, dispatch] = useReducer(taskReducer, initialState);

       return (
         <div className="task-list">
           <AddTask dispatch={dispatch} />
           {tasks.map((task) => (
             <Task key={task.id} task={task} dispatch={dispatch} />
           ))}
         </div>
       );
     }
     export default TaskList;
     ```  

6. **Create the `Task` Component** (1 hr)  
   - In `src/components/Task.js`:  
     ```javascript
     function Task({ task, dispatch }) {
       return (
         <div className={`task ${task.completed ? 'completed' : ''}`}>
           <span>{task.text}</span>
           <button onClick={() => dispatch({ type: 'TOGGLE_TASK', id: task.id })}>
             {task.completed ? 'Undo' : 'Complete'}
           </button>
           <button onClick={() => dispatch({ type: 'DELETE_TASK', id: task.id })}>
             Delete
           </button>
         </div>
       );
     }
     export default Task;
     ```  
   - Add CSS in `Task.css`:  
     ```css
     .task {
       background-color: #f4f4f4;
       margin: 5px 0;
       padding: 10px;
       border-radius: 5px;
       display: flex;
       justify-content: space-between;
       align-items: center;
     }
     .task.completed {
       text-decoration: line-through;
       opacity: 0.7;
     }
     .task button {
       margin-left: 10px;
     }
     ```  

7. **Create the `AddTask` Component** (1 hr)  
   - In `src/components/AddTask.js`:  
     ```javascript
     import { useState } from 'react';

     function AddTask({ dispatch }) {
       const [text, setText] = useState('');

       const handleSubmit = (e) => {
         e.preventDefault();
         if (text.trim()) {
           dispatch({ type: 'ADD_TASK', text });
           setText('');
         }
       };

       return (
         <form onSubmit={handleSubmit}>
           <input
             type="text"
             value={text}
             onChange={(e) => setText(e.target.value)}
             placeholder="Add a new task"
           />
           <button type="submit">Add Task</button>
         </form>
       );
     }
     export default AddTask;
     ```  
   - Add CSS in `AddTask.css`:  
     ```css
     form {
       margin: 20px 0;
       display: flex;
     }
     form input {
       flex: 1;
       padding: 10px;
       border: 1px solid #ccc;
       border-radius: 5px;
     }
     form button {
       padding: 10px 20px;
       background-color: #007bff;
       color: white;
       border: none;
       cursor: pointer;
       margin-left: 10px;
       border-radius: 5px;
     }
     form button:hover {
       background-color: #0056b3;
     }
     ```  

8. **Assemble the App** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import Header from './components/Header';
     import TaskList from './components/TaskList';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       return (
         <div className="App">
           <Header />
           <TaskList />
           <Footer />
         </div>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure tasks can be added, toggled, and deleted.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 17**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - A `TaskList` component managing tasks with `useReducer`.  
   - A `Footer` component with a copyright notice.  
2. A clear understanding of `useReducer` and its use cases.  

---
---

### **Day 18: Refs and Memoization**  
**Goal**: Learn how to use `useRef` and `useMemo` for performance optimization.  

#### **Theory (1.5 hrs)**  
1. **TOP: Refs and Memoization**  
   - Learn about `useRef` for accessing DOM elements and storing mutable values.  
   - Understand `useMemo` for memoizing expensive calculations.  

2. **FSO Part 3d: Performance Optimization (Optional)**  
   - Skim this section for a deeper dive into performance techniques (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Build a focusable input and a memoized calculation app.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app refs-memo-demo`.  
   - Clean up the default template (remove unused files and code).  

2. **Plan the Component Hierarchy** (30 mins)  
   - Design a simple app with the following structure:  
     ```
     App
     ├── Header
     ├── FocusableInput
     ├── ExpensiveCalculation
     └── Footer
     ```  
   - Sketch the layout on paper or in a tool like Figma.  

3. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     function Header() {
       return (
         <header>
           <h1>Refs and Memoization Demo</h1>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     ```  

4. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 Refs and Memoization Demo</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

5. **Create the `FocusableInput` Component** (1 hr)  
   - In `src/components/FocusableInput.js`:  
     ```javascript
     import { useRef } from 'react';

     function FocusableInput() {
       const inputRef = useRef(null);

       const handleClick = () => {
         inputRef.current.focus();
       };

       return (
         <div className="focusable-input">
           <input type="text" ref={inputRef} placeholder="Type something..." />
           <button onClick={handleClick}>Focus Input</button>
         </div>
       );
     }
     export default FocusableInput;
     ```  
   - Add CSS in `FocusableInput.css`:  
     ```css
     .focusable-input {
       margin: 20px 0;
       text-align: center;
     }
     .focusable-input input {
       padding: 10px;
       border: 1px solid #ccc;
       border-radius: 5px;
     }
     .focusable-input button {
       padding: 10px 20px;
       background-color: #007bff;
       color: white;
       border: none;
       cursor: pointer;
       margin-left: 10px;
       border-radius: 5px;
     }
     .focusable-input button:hover {
       background-color: #0056b3;
     }
     ```  

6. **Create the `ExpensiveCalculation` Component** (1 hr)  
   - In `src/components/ExpensiveCalculation.js`:  
     ```javascript
     import { useState, useMemo } from 'react';

     function ExpensiveCalculation() {
       const [number, setNumber] = useState(0);

       const calculateFactorial = (num) => {
         console.log('Calculating factorial...');
         return num <= 1 ? 1 : num * calculateFactorial(num - 1);
       };

       const factorial = useMemo(() => calculateFactorial(number), [number]);

       return (
         <div className="expensive-calculation">
           <h2>Factorial Calculator</h2>
           <input
             type="number"
             value={number}
             onChange={(e) => setNumber(Number(e.target.value))}
             placeholder="Enter a number"
           />
           <p>Factorial of {number} is {factorial}</p>
         </div>
       );
     }
     export default ExpensiveCalculation;
     ```  
   - Add CSS in `ExpensiveCalculation.css`:  
     ```css
     .expensive-calculation {
       margin: 20px 0;
       text-align: center;
     }
     .expensive-calculation input {
       padding: 10px;
       border: 1px solid #ccc;
       border-radius: 5px;
     }
     ```  

7. **Assemble the App** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import Header from './components/Header';
     import FocusableInput from './components/FocusableInput';
     import ExpensiveCalculation from './components/ExpensiveCalculation';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       return (
         <div className="App">
           <Header />
           <FocusableInput />
           <ExpensiveCalculation />
           <Footer />
         </div>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the input focuses and the factorial calculation works.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 18**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - A `FocusableInput` component using `useRef`.  
   - An `ExpensiveCalculation` component using `useMemo`.  
   - A `Footer` component with a copyright notice.  
2. A clear understanding of `useRef` and `useMemo`.  

---
---

### **Day 19: Shopping Cart Project (Setup)**  
**Goal**: Build a shopping cart app, focusing on global state management and API integration.  

#### **Theory (1.5 hrs)**  
1. **TOP: Managing State With the Context API**  
   - Revisit the Context API for global state management.  
   - Understand how to combine `useReducer` and Context for complex apps.  

2. **FSO Part 3b: State Management (Optional)**  
   - Skim this section for a deeper dive into state management (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Set up the shopping cart app with global state and product listing.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app shopping-cart`.  
   - Clean up the default template (remove unused files and code).  

2. **Plan the Component Hierarchy** (30 mins)  
   - Design a simple app with the following structure:  
     ```
     App
     ├── Header
     ├── ProductList
     │   ├── Product
     │   └── AddToCartButton
     ├── Cart
     │   ├── CartItem
     │   └── CheckoutButton
     └── Footer
     ```  
   - Sketch the layout on paper or in a tool like Figma.  

3. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     function Header() {
       return (
         <header>
           <h1>Shopping Cart</h1>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     ```  

4. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 Shopping Cart</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

5. **Create the `CartContext`** (1 hr)  
   - Create a new file `src/context/CartContext.js`:  
     ```javascript
     import { createContext, useReducer } from 'react';

     const CartContext = createContext();

     const initialState = {
       cart: [],
     };

     function cartReducer(state, action) {
       switch (action.type) {
         case 'ADD_TO_CART':
           return {
             ...state,
             cart: [...state.cart, action.payload],
           };
         case 'REMOVE_FROM_CART':
           return {
             ...state,
             cart: state.cart.filter((item) => item.id !== action.payload.id),
           };
         default:
           return state;
       }
     }

     export function CartProvider({ children }) {
       const [state, dispatch] = useReducer(cartReducer, initialState);

       return (
         <CartContext.Provider value={{ state, dispatch }}>
           {children}
         </CartContext.Provider>
       );
     }

     export default CartContext;
     ```  

6. **Create the `ProductList` Component** (1 hr)  
   - In `src/components/ProductList.js`:  
     ```javascript
     import { useContext } from 'react';
     import CartContext from '../context/CartContext';
     import Product from './Product';

     const products = [
       { id: 1, name: 'Product 1', price: 10 },
       { id: 2, name: 'Product 2', price: 20 },
       { id: 3, name: 'Product 3', price: 30 },
     ];

     function ProductList() {
       const { dispatch } = useContext(CartContext);

       const handleAddToCart = (product) => {
         dispatch({ type: 'ADD_TO_CART', payload: product });
       };

       return (
         <div className="product-list">
           {products.map((product) => (
             <Product
               key={product.id}
               product={product}
               onAddToCart={handleAddToCart}
             />
           ))}
         </div>
       );
     }
     export default ProductList;
     ```  
   - Add CSS in `ProductList.css`:  
     ```css
     .product-list {
       display: flex;
       flex-wrap: wrap;
       justify-content: center;
     }
     ```  

7. **Create the `Product` Component** (1 hr)  
   - In `src/components/Product.js`:  
     ```javascript
     function Product({ product, onAddToCart }) {
       return (
         <div className="product">
           <h3>{product.name}</h3>
           <p>${product.price}</p>
           <button onClick={() => onAddToCart(product)}>Add to Cart</button>
         </div>
       );
     }
     export default Product;
     ```  
   - Add CSS in `Product.css`:  
     ```css
     .product {
       background-color: #f4f4f4;
       margin: 10px;
       padding: 20px;
       border-radius: 10px;
       text-align: center;
     }
     .product button {
       padding: 10px 20px;
       background-color: #007bff;
       color: white;
       border: none;
       cursor: pointer;
       border-radius: 5px;
     }
     .product button:hover {
       background-color: #0056b3;
     }
     ```  

8. **Assemble the App** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import { CartProvider } from './context/CartContext';
     import Header from './components/Header';
     import ProductList from './components/ProductList';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       return (
         <CartProvider>
           <div className="App">
             <Header />
             <ProductList />
             <Footer />
           </div>
         </CartProvider>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure products can be added to the cart.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 19**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - A `ProductList` component displaying products.  
   - A `Footer` component with a copyright notice.  
2. Global state management using Context API and `useReducer`.  
3. A clear understanding of global state in complex apps.  

---

(Due to technical issues, the search service is temporarily unavailable.)

Here’s **Day 20** with the same level of detail, focusing on completing the Shopping Cart project and deploying it:

---

### **Day 20: Shopping Cart Project (Finish)**  
**Goal**: Complete the shopping cart app, add checkout functionality, and deploy it.  

#### **Theory (1.5 hrs)**  
1. **TOP: Cart Logic**  
   - Learn how to calculate totals, handle item removal, and manage checkout flows.  
   - Understand how to persist cart state (e.g., using `localStorage`).  

2. **FSO Part 3c: Complex State (Optional)**  
   - Skim this section for a deeper dive into cart logic (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Add cart display, checkout, and deployment to the Shopping Cart app.  

1. **Create the `Cart` Component** (1 hr)  
   - In `src/components/Cart.js`:  
     ```javascript
     import { useContext } from 'react';
     import CartContext from '../context/CartContext';
     import CartItem from './CartItem';

     function Cart() {
       const { state, dispatch } = useContext(CartContext);

       const total = state.cart.reduce((sum, item) => sum + item.price, 0);

       return (
         <div className="cart">
           <h2>Your Cart</h2>
           {state.cart.length === 0 ? (
             <p>Your cart is empty.</p>
           ) : (
             <>
               {state.cart.map((item) => (
                 <CartItem key={item.id} item={item} dispatch={dispatch} />
               ))}
               <p>Total: ${total.toFixed(2)}</p>
               <CheckoutButton dispatch={dispatch} />
             </>
           )}
         </div>
       );
     }
     export default Cart;
     ```  
   - Add CSS in `Cart.css`:  
     ```css
     .cart {
       margin: 20px 0;
       padding: 20px;
       background-color: #f9f9f9;
       border-radius: 10px;
     }
     .cart h2 {
       margin: 0 0 15px;
     }
     ```  

2. **Create the `CartItem` Component** (1 hr)  
   - In `src/components/CartItem.js`:  
     ```javascript
     function CartItem({ item, dispatch }) {
       return (
         <div className="cart-item">
           <span>{item.name}</span>
           <span>${item.price}</span>
           <button
             onClick={() => dispatch({ type: 'REMOVE_FROM_CART', payload: item })}
           >
             Remove
           </button>
         </div>
       );
     }
     export default CartItem;
     ```  
   - Add CSS in `CartItem.css`:  
     ```css
     .cart-item {
       display: flex;
       justify-content: space-between;
       align-items: center;
       margin: 10px 0;
       padding: 10px;
       background-color: white;
       border-radius: 5px;
     }
     .cart-item button {
       padding: 5px 10px;
       background-color: #dc3545;
       color: white;
       border: none;
       cursor: pointer;
       border-radius: 5px;
     }
     .cart-item button:hover {
       background-color: #bb2d3b;
     }
     ```  

3. **Create the `CheckoutButton` Component** (1 hr)  
   - In `src/components/CheckoutButton.js`:  
     ```javascript
     function CheckoutButton({ dispatch }) {
       const handleCheckout = () => {
         dispatch({ type: 'CLEAR_CART' });
         alert('Thank you for your purchase!');
       };

       return (
         <button className="checkout-button" onClick={handleCheckout}>
           Checkout
         </button>
       );
     }
     export default CheckoutButton;
     ```  
   - Add CSS in `CheckoutButton.css`:  
     ```css
     .checkout-button {
       padding: 10px 20px;
       background-color: #28a745;
       color: white;
       border: none;
       cursor: pointer;
       border-radius: 5px;
     }
     .checkout-button:hover {
       background-color: #218838;
     }
     ```  

4. **Update the `CartContext` Reducer** (30 mins)  
   - Modify `src/context/CartContext.js` to handle clearing the cart:  
     ```javascript
     function cartReducer(state, action) {
       switch (action.type) {
         // ... existing cases ...
         case 'CLEAR_CART':
           return { ...state, cart: [] };
         default:
           return state;
       }
     }
     ```  

5. **Update the `App` Component** (30 mins)  
   - In `src/App.js`, include the `Cart` component:  
     ```javascript
     import { CartProvider } from './context/CartContext';
     import Header from './components/Header';
     import ProductList from './components/ProductList';
     import Cart from './components/Cart';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       return (
         <CartProvider>
           <div className="App">
             <Header />
             <ProductList />
             <Cart />
             <Footer />
           </div>
         </CartProvider>
       );
     }
     export default App;
     ```  

6. **Deploy to Netlify** (1 hr)  
   - Install Netlify CLI:  
     ```bash
     npm install -g netlify-cli
     ```  
   - Build the project:  
     ```bash
     npm run build
     ```  
   - Deploy:  
     ```bash
     netlify deploy --prod
     ```  
   - Follow the prompts to link/configure your Netlify site.  

---

#### **Review (30 mins)**  
1. **Test Your App**:  
   - Add/remove items, verify the total updates.  
   - Test checkout functionality.  
2. **Debug**: Check for console errors related to state or missing props.  
3. **Refactor**: Ensure consistent styling and PropTypes.  

---

### **Deliverables for Day 20**  
1. A React app with:  
   - A fully functional cart displaying items, totals, and a checkout button.  
   - Global state management for adding/removing items and clearing the cart.  
   - Deployment to Netlify.  
2. A clear understanding of cart logic and deployment workflows.  

---

### **Final Adjustments**  
1. **Persist Cart State** (Optional):  
   - Use `localStorage` in `CartContext` to save/load cart state:  
     ```javascript
     // In CartContext.js
     const initialState = {
       cart: JSON.parse(localStorage.getItem('cart')) || [],
     };

     // Update localStorage whenever cart changes
     useEffect(() => {
       localStorage.setItem('cart', JSON.stringify(state.cart));
     }, [state.cart]);
     ```  

2. **Add Quantity Handling** (Stretch Goal):  
   - Modify the reducer to track item quantities instead of duplicates.  

(Due to technical issues, the search service is temporarily unavailadays after this.

---
---

### **Day 21: Final Project (Setup)**  
**Goal**: Set up the Automated Financial Report Generator project and plan its structure.  

#### **Theory (1.5 hrs)**  
1. **Project Overview**  
   - Understand the project requirements:  
     - Fetch financial data (e.g., stock prices, SEC filings).  
     - Use ChatGPT API to summarize data.  
     - Display reports in a user-friendly format.  
   - Plan the tech stack: React, ChatGPT API, and a financial data API (e.g., Alpha Vantage).  

2. **FSO Part 3b: State Management (Optional)**  
   - Skim this section for a deeper dive into managing complex state (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Scaffold the project, set up APIs, and create the basic UI.  

1. **Set Up a New React Project** (30 mins)  
   - Scaffold a new project: `npx create-react-app financial-report-generator`.  
   - Clean up the default template (remove unused files and code).  

2. **Install Dependencies** (30 mins)  
   - Install required libraries:  
     ```bash
     npm install axios react-router-dom
     ```  

3. **Plan the Component Hierarchy** (30 mins)  
   - Design the app structure:  
     ```
     App
     ├── Header
     ├── ReportGenerator
     │   ├── InputForm
     │   ├── ReportDisplay
     │   └── ReportHistory
     └── Footer
     ```  
   - Sketch the layout on paper or in a tool like Figma.  

4. **Create the `Header` Component** (30 mins)  
   - In `src/components/Header.js`:  
     ```javascript
     function Header() {
       return (
         <header>
           <h1>Financial Report Generator</h1>
         </header>
       );
     }
     export default Header;
     ```  
   - Add basic CSS in `Header.css`:  
     ```css
     header {
       background-color: #333;
       color: white;
       padding: 20px;
       text-align: center;
     }
     ```  

5. **Create the `Footer` Component** (30 mins)  
   - In `src/components/Footer.js`:  
     ```javascript
     function Footer() {
       return (
         <footer>
           <p>© 2024 Financial Report Generator</p>
         </footer>
       );
     }
     export default Footer;
     ```  
   - Add basic CSS in `Footer.css`:  
     ```css
     footer {
       background-color: #333;
       color: white;
       text-align: center;
       padding: 10px;
       position: fixed;
       bottom: 0;
       width: 100%;
     }
     ```  

6. **Set Up API Integration** (1 hr)  
   - Create a new file `src/api/financialData.js`:  
     ```javascript
     import axios from 'axios';

     const ALPHA_VANTAGE_API_KEY = 'YOUR_API_KEY';

     export const fetchStockData = async (symbol) => {
       const response = await axios.get(
         `https://www.alphavantage.co/query?function=TIME_SERIES_DAILY&symbol=${symbol}&apikey=${ALPHA_VANTAGE_API_KEY}`
       );
       return response.data;
     };
     ```  
   - Create a new file `src/api/chatGPT.js`:  
     ```javascript
     import axios from 'axios';

     const CHATGPT_API_KEY = 'YOUR_API_KEY';

     export const generateReport = async (data) => {
       const response = await axios.post(
         'https://api.openai.com/v1/chat/completions',
         {
           model: 'gpt-3.5-turbo',
           messages: [
             {
               role: 'user',
               content: `Summarize this financial data: ${JSON.stringify(data)}`,
             },
           ],
         },
         {
           headers: {
             'Authorization': `Bearer ${CHATGPT_API_KEY}`,
             'Content-Type': 'application/json',
           },
         }
       );
       return response.data.choices[0].message.content;
     };
     ```  

7. **Create the `InputForm` Component** (1 hr)  
   - In `src/components/InputForm.js`:  
     ```javascript
     import { useState } from 'react';
     import { fetchStockData } from '../api/financialData';

     function InputForm({ onSubmit }) {
       const [symbol, setSymbol] = useState('');

       const handleSubmit = async (e) => {
         e.preventDefault();
         const data = await fetchStockData(symbol);
         onSubmit(data);
       };

       return (
         <form onSubmit={handleSubmit}>
           <input
             type="text"
             value={symbol}
             onChange={(e) => setSymbol(e.target.value)}
             placeholder="Enter stock symbol (e.g., AAPL)"
           />
           <button type="submit">Generate Report</button>
         </form>
       );
     }
     export default InputForm;
     ```  
   - Add CSS in `InputForm.css`:  
     ```css
     form {
       margin: 20px 0;
       display: flex;
     }
     form input {
       flex: 1;
       padding: 10px;
       border: 1px solid #ccc;
       border-radius: 5px;
     }
     form button {
       padding: 10px 20px;
       background-color: #007bff;
       color: white;
       border: none;
       cursor: pointer;
       margin-left: 10px;
       border-radius: 5px;
     }
     form button:hover {
       background-color: #0056b3;
     }
     ```  

8. **Assemble the App** (30 mins)  
   - In `src/App.js`:  
     ```javascript
     import Header from './components/Header';
     import InputForm from './components/InputForm';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       const handleSubmit = (data) => {
         console.log('Fetched data:', data);
       };

       return (
         <div className="App">
           <Header />
           <InputForm onSubmit={handleSubmit} />
           <Footer />
         </div>
       );
     }
     export default App;
     ```  
   - Add global styles in `App.css`:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
     }
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the input form fetches stock data.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 21**  
1. A React app with:  
   - A `Header` component displaying a title.  
   - An `InputForm` component for fetching stock data.  
   - A `Footer` component with a copyright notice.  
2. API integration for fetching stock data.  
3. A clear understanding of the project structure and goals.  

---

(Due to technical issues, the search service is temporarily unavailathis.

---
---

### **Day 22: Final Project (Data Processing & Report Generation)**  
**Goal**: Fetch financial data, process it, and generate a report using the ChatGPT API.  

#### **Theory (1.5 hrs)**  
1. **Data Processing**  
   - Learn how to extract and format relevant data from API responses.  
   - Understand how to structure data for ChatGPT API input.  

2. **ChatGPT API Integration**  
   - Explore the ChatGPT API documentation for generating summaries.  

---

#### **Coding (4 hrs)**  
**Objective**: Fetch financial data, process it, and generate a report summary.  

1. **Update the `InputForm` Component** (1 hr)  
   - Modify `src/components/InputForm.js` to pass fetched data to the parent component:  
     ```javascript
     const handleSubmit = async (e) => {
       e.preventDefault();
       const data = await fetchStockData(symbol);
       onSubmit(data);
       setSymbol('');
     };
     ```  

2. **Create the `ReportDisplay` Component** (1 hr)  
   - In `src/components/ReportDisplay.js`:  
     ```javascript
     import { useState, useEffect } from 'react';
     import { generateReport } from '../api/chatGPT';

     function ReportDisplay({ data }) {
       const [report, setReport] = useState('');
       const [loading, setLoading] = useState(false);

       useEffect(() => {
         if (data) {
           setLoading(true);
           generateReport(data).then((summary) => {
             setReport(summary);
             setLoading(false);
           });
         }
       }, [data]);

       return (
         <div className="report-display">
           {loading ? (
             <p>Generating report...</p>
           ) : (
             <p>{report}</p>
           )}
         </div>
       );
     }
     export default ReportDisplay;
     ```  
   - Add CSS in `ReportDisplay.css`:  
     ```css
     .report-display {
       margin: 20px 0;
       padding: 20px;
       background-color: #f9f9f9;
       border-radius: 10px;
     }
     .report-display p {
       white-space: pre-wrap;
     }
     ```  

3. **Update the `App` Component** (1 hr)  
   - In `src/App.js`, add state for fetched data and integrate `ReportDisplay`:  
     ```javascript
     import { useState } from 'react';
     import Header from './components/Header';
     import InputForm from './components/InputForm';
     import ReportDisplay from './components/ReportDisplay';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       const [data, setData] = useState(null);

       const handleSubmit = (data) => {
         setData(data);
       };

       return (
         <div className="App">
           <Header />
           <InputForm onSubmit={handleSubmit} />
           {data && <ReportDisplay data={data} />}
           <Footer />
         </div>
       );
     }
     export default App;
     ```  

4. **Test the Report Generation** (1 hr)  
   - Enter a stock symbol (e.g., `AAPL`) and verify the report is generated.  
   - Debug any issues with data fetching or API calls.  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the report is generated and displayed correctly.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 22**  
1. A React app with:  
   - A `ReportDisplay` component showing generated reports.  
   - Integration with the ChatGPT API for report generation.  
2. A clear understanding of data processing and API integration.  this.

---
---

### **Day 23: Final Project (Report History & Persistence)**  
**Goal**: Add a report history feature and persist reports using `localStorage`.  

#### **Theory (1.5 hrs)**  
1. **Report History**  
   - Learn how to store and display a list of generated reports.  
   - Understand how to use `localStorage` for persistence.  

2. **FSO Part 3b: State Management (Optional)**  
   - Skim this section for a deeper dive into managing complex state (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Add a report history feature and persist reports.  

1. **Create the `ReportHistory` Component** (1 hr)  
   - In `src/components/ReportHistory.js`:  
     ```javascript
     function ReportHistory({ reports, onSelectReport }) {
       return (
         <div className="report-history">
           <h2>Report History</h2>
           {reports.length === 0 ? (
             <p>No reports generated yet.</p>
           ) : (
             <ul>
               {reports.map((report, index) => (
                 <li key={index} onClick={() => onSelectReport(report)}>
                   Report {index + 1}
                 </li>
               ))}
             </ul>
           )}
         </div>
       );
     }
     export default ReportHistory;
     ```  
   - Add CSS in `ReportHistory.css`:  
     ```css
     .report-history {
       margin: 20px 0;
       padding: 20px;
       background-color: #f9f9f9;
       border-radius: 10px;
     }
     .report-history ul {
       list-style: none;
       padding: 0;
     }
     .report-history ul li {
       margin: 5px 0;
       padding: 10px;
       background-color: white;
       border-radius: 5px;
       cursor: pointer;
     }
     .report-history ul li:hover {
       background-color: #f1f1f1;
     }
     ```  

2. **Update the `App` Component** (1 hr)  
   - In `src/App.js`, add state for report history and integrate `ReportHistory`:  
     ```javascript
     import { useState, useEffect } from 'react';
     import Header from './components/Header';
     import InputForm from './components/InputForm';
     import ReportDisplay from './components/ReportDisplay';
     import ReportHistory from './components/ReportHistory';
     import Footer from './components/Footer';
     import './App.css';

     function App() {
       const [data, setData] = useState(null);
       const [reports, setReports] = useState([]);

       useEffect(() => {
         const savedReports = JSON.parse(localStorage.getItem('reports')) || [];
         setReports(savedReports);
       }, []);

       const handleSubmit = (data) => {
         setData(data);
         const newReport = { data, timestamp: new Date().toLocaleString() };
         const updatedReports = [...reports, newReport];
         setReports(updatedReports);
         localStorage.setItem('reports', JSON.stringify(updatedReports));
       };

       const handleSelectReport = (report) => {
         setData(report.data);
       };

       return (
         <div className="App">
           <Header />
           <InputForm onSubmit={handleSubmit} />
           {data && <ReportDisplay data={data} />}
           <ReportHistory reports={reports} onSelectReport={handleSelectReport} />
           <Footer />
         </div>
       );
     }
     export default App;
     ```  

3. **Test the Report History** (1 hr)  
   - Generate multiple reports and verify they are saved and displayed.  
   - Click on a report in the history to display it.  

4. **Add Persistence with `localStorage`** (1 hr)  
   - Ensure reports are saved to `localStorage` and loaded on app startup.  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the report history works correctly.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 23**  
1. A React app with:  
   - A `ReportHistory` component displaying past reports.  
   - Persistence of reports using `localStorage`.  
2. A clear understanding of state management and persistence.  this.

---
---

### **Day 24: Final Project (Styling & Polish)**  
**Goal**: Improve the UI/UX of the app with styling and animations.  

#### **Theory (1.5 hrs)**  
1. **Styling Best Practices**  
   - Learn about responsive design, accessibility, and modern CSS techniques.  
   - Understand how to use CSS frameworks (e.g., Tailwind) or libraries (e.g., Styled Components).  

2. **FSO Part 2c: Styling (Optional)**  
   - Skim this section for a deeper dive into styling techniques (if needed).  

---

#### **Coding (4 hrs)**  
**Objective**: Add styling, animations, and polish to the app.  

1. **Add a Loading Animation** (1 hr)  
   - Install a loading spinner library (e.g., `react-loader-spinner`):  
     ```bash
     npm install react-loader-spinner
     ```  
   - Update `src/components/ReportDisplay.js`:  
     ```javascript
     import { TailSpin } from 'react-loader-spinner';

     function ReportDisplay({ data }) {
       const [report, setReport] = useState('');
       const [loading, setLoading] = useState(false);

       useEffect(() => {
         if (data) {
           setLoading(true);
           generateReport(data).then((summary) => {
             setReport(summary);
             setLoading(false);
           });
         }
       }, [data]);

       return (
         <div className="report-display">
           {loading ? (
             <TailSpin color="#007bff" height={50} width={50} />
           ) : (
             <p>{report}</p>
           )}
         </div>
       );
     }
     ```  
   - Add CSS for the spinner in `ReportDisplay.css`:  
     ```css
     .report-display {
       display: flex;
       justify-content: center;
       align-items: center;
       min-height: 200px;
     }
     ```  

2. **Improve the Input Form** (1 hr)  
   - Update `src/components/InputForm.js` with better styling:  
     ```javascript
     function InputForm({ onSubmit }) {
       const [symbol, setSymbol] = useState('');

       const handleSubmit = async (e) => {
         e.preventDefault();
         const data = await fetchStockData(symbol);
         onSubmit(data);
         setSymbol('');
       };

       return (
         <form onSubmit={handleSubmit} className="input-form">
           <input
             type="text"
             value={symbol}
             onChange={(e) => setSymbol(e.target.value)}
             placeholder="Enter stock symbol (e.g., AAPL)"
             required
           />
           <button type="submit">Generate Report</button>
         </form>
       );
     }
     ```  
   - Add CSS in `InputForm.css`:  
     ```css
     .input-form {
       display: flex;
       justify-content: center;
       margin: 20px 0;
     }
     .input-form input {
       padding: 10px;
       border: 1px solid #ccc;
       border-radius: 5px;
       width: 300px;
     }
     .input-form button {
       padding: 10px 20px;
       background-color: #007bff;
       color: white;
       border: none;
       cursor: pointer;
       margin-left: 10px;
       border-radius: 5px;
     }
     .input-form button:hover {
       background-color: #0056b3;
     }
     ```  

3. **Add Animations** (1 hr)  
   - Install a CSS animation library (e.g., `animate.css`):  
     ```bash
     npm install animate.css
     ```  
   - Add animations to the `ReportDisplay` component:  
     ```javascript
     import 'animate.css';

     function ReportDisplay({ data }) {
       const [report, setReport] = useState('');
       const [loading, setLoading] = useState(false);

       useEffect(() => {
         if (data) {
           setLoading(true);
           generateReport(data).then((summary) => {
             setReport(summary);
             setLoading(false);
           });
         }
       }, [data]);

       return (
         <div className="report-display animate__animated animate__fadeIn">
           {loading ? (
             <TailSpin color="#007bff" height={50} width={50} />
           ) : (
             <p>{report}</p>
           )}
         </div>
       );
     }
     ```  

4. **Polish the UI** (1 hr)  
   - Add a gradient background to the app:  
     ```css
     .App {
       font-family: Arial, sans-serif;
       max-width: 800px;
       margin: 0 auto;
       padding: 20px;
       background: linear-gradient(135deg, #f5f7fa, #c3cfe2);
       min-height: 100vh;
     }
     ```  
   - Add hover effects to buttons and list items.  

---

#### **Review (30 mins)**  
1. **Test Your App**: Ensure the UI looks polished and animations work.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 24**  
1. A React app with:  
   - A polished UI with animations and responsive design.  
   - A loading spinner for report generation.  
2. A clear understanding of styling and animation techniques.  this.

---
---

### **Day 25: Final Project (Export & Deployment)**  
**Goal**: Add export functionality and deploy the app.  

#### **Theory (1.5 hrs)**  
1. **Exporting Data**  
   - Learn how to export data as PDF or CSV.  
   - Understand libraries like `react-pdf` or `file-saver`.  

2. **Deployment**  
   - Learn how to deploy a React app to platforms like Netlify or Vercel.  

---

#### **Coding (4 hrs)**  
**Objective**: Add export functionality and deploy the app.  

1. **Add PDF Export** (1.5 hrs)  
   - Install `react-pdf`:  
     ```bash
     npm install @react-pdf/renderer
     ```  
   - Create a new file `src/components/PDFExport.js`:  
     ```javascript
     import { PDFDownloadLink, Document, Page, Text, View, StyleSheet } from '@react-pdf/renderer';

     const styles = StyleSheet.create({
       page: {
         padding: 20,
       },
       title: {
         fontSize: 24,
         marginBottom: 10,
       },
       content: {
         fontSize: 12,
       },
     });

     function PDFExport({ report }) {
       return (
         <PDFDownloadLink
           document={
             <Document>
               <Page style={styles.page}>
                 <Text style={styles.title}>Financial Report</Text>
                 <Text style={styles.content}>{report}</Text>
               </Page>
             </Document>
           }
           fileName="report.pdf"
         >
           {({ loading }) => (loading ? 'Loading document...' : 'Export as PDF')}
         </PDFDownloadLink>
       );
     }
     export default PDFExport;
     ```  
   - Integrate `PDFExport` into `ReportDisplay`:  
     ```javascript
     import PDFExport from './PDFExport';

     function ReportDisplay({ data }) {
       const [report, setReport] = useState('');
       const [loading, setLoading] = useState(false);

       useEffect(() => {
         if (data) {
           setLoading(true);
           generateReport(data).then((summary) => {
             setReport(summary);
             setLoading(false);
           });
         }
       }, [data]);

       return (
         <div className="report-display animate__animated animate__fadeIn">
           {loading ? (
             <TailSpin color="#007bff" height={50} width={50} />
           ) : (
             <>
               <p>{report}</p>
               <PDFExport report={report} />
             </>
           )}
         </div>
       );
     }
     ```  

2. **Add CSV Export** (1.5 hrs)  
   - Install `file-saver`:  
     ```bash
     npm install file-saver
     ```  
   - Create a new file `src/components/CSVExport.js`:  
     ```javascript
     import { saveAs } from 'file-saver';

     function CSVExport({ report }) {
       const handleExport = () => {
         const blob = new Blob([report], { type: 'text/csv;charset=utf-8' });
         saveAs(blob, 'report.csv');
       };

       return (
         <button onClick={handleExport}>Export as CSV</button>
       );
     }
     export default CSVExport;
     ```  
   - Integrate `CSVExport` into `ReportDisplay`:  
     ```javascript
     import CSVExport from './CSVExport';

     function ReportDisplay({ data }) {
       const [report, setReport] = useState('');
       const [loading, setLoading] = useState(false);

       useEffect(() => {
         if (data) {
           setLoading(true);
           generateReport(data).then((summary) => {
             setReport(summary);
             setLoading(false);
           });
         }
       }, [data]);

       return (
         <div className="report-display animate__animated animate__fadeIn">
           {loading ? (
             <TailSpin color="#007bff" height={50} width={50} />
           ) : (
             <>
               <p>{report}</p>
               <PDFExport report={report} />
               <CSVExport report={report} />
             </>
           )}
         </div>
       );
     }
     ```  

3. **Deploy to Netlify** (1 hr)  
   - Install Netlify CLI:  
     ```bash
     npm install -g netlify-cli
     ```  
   - Build the project:  
     ```bash
     npm run build
     ```  
   - Deploy:  
     ```bash
     netlify deploy --prod
     ```  
   - Follow the prompts to link/configure your Netlify site.  

---

#### **Review (30 mins)**  
1. **Test Your App**:  
   - Export reports as PDF and CSV.  
   - Verify deployment works.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 25**  
1. A React app with:  
   - PDF and CSV export functionality.  
   - Deployment to Netlify.  
2. A clear understanding of export and deployment workflows.

---
---

### **Day 26: Final Polish**  
**Goal**: Add final touches to the app, including error handling, accessibility improvements, and performance optimizations.  

#### **Theory (1.5 hrs)**  
1. **Error Handling**  
   - Learn how to handle API errors and display user-friendly messages.  

2. **Accessibility**  
   - Understand best practices for making the app accessible (e.g., ARIA labels, keyboard navigation).  

3. **Performance Optimization**  
   - Learn techniques for improving app performance (e.g., lazy loading, memoization).  

---

#### **Coding (4 hrs)**  
**Objective**: Add error handling, accessibility features, and performance optimizations.  

1. **Add Error Handling** (1.5 hrs)  
   - Update `src/components/InputForm.js` to handle API errors:  
     ```javascript
     function InputForm({ onSubmit }) {
       const [symbol, setSymbol] = useState('');
       const [error, setError] = useState('');

       const handleSubmit = async (e) => {
         e.preventDefault();
         setError('');
         try {
           const data = await fetchStockData(symbol);
           if (data['Error Message']) {
             throw new Error('Invalid stock symbol');
           }
           onSubmit(data);
           setSymbol('');
         } catch (err) {
           setError(err.message);
         }
       };

       return (
         <form onSubmit={handleSubmit} className="input-form">
           <input
             type="text"
             value={symbol}
             onChange={(e) => setSymbol(e.target.value)}
             placeholder="Enter stock symbol (e.g., AAPL)"
             required
           />
           <button type="submit">Generate Report</button>
           {error && <p className="error">{error}</p>}
         </form>
       );
     }
     ```  
   - Add CSS for error messages in `InputForm.css`:  
     ```css
     .error {
       color: #dc3545;
       margin: 10px 0;
     }
     ```  

2. **Improve Accessibility** (1.5 hrs)  
   - Add ARIA labels to form inputs and buttons:  
     ```javascript
     <input
       type="text"
       value={symbol}
       onChange={(e) => setSymbol(e.target.value)}
       placeholder="Enter stock symbol (e.g., AAPL)"
       required
       aria-label="Stock symbol"
     />
     <button type="submit" aria-label="Generate report">
       Generate Report
     </button>
     ```  
   - Ensure keyboard navigation works for all interactive elements.  

3. **Optimize Performance** (1 hr)  
   - Use `React.memo` to prevent unnecessary re-renders:  
     ```javascript
     import { memo } from 'react';

     const PDFExport = memo(({ report }) => {
       // ... component code ...
     });
     ```  
   - Lazy load components using `React.lazy`:  
     ```javascript
     const ReportHistory = React.lazy(() => import('./components/ReportHistory'));
     ```  

---

#### **Review (30 mins)**  
1. **Test Your App**:  
   - Verify error handling works.  
   - Test accessibility with screen readers and keyboard navigation.  
2. **Debug**: Check for console errors and fix any issues.  
3. **Refactor**: Clean up your code (e.g., consistent formatting, meaningful variable names).  

---

### **Deliverables for Day 26**  
1. A React app with:  
   - Error handling for invalid inputs and API errors.  
   - Accessibility improvements (ARIA labels, keyboard navigation).  
   - Performance optimizations (memoization, lazy loading).  
2. A clear understanding of final polish techniques.  **Day 28** after this.

---
---

### **Day 27: Documentation**  
**Goal**: Write comprehensive documentation for the app, including a README, code comments, and user guides.  

#### **Theory (1.5 hrs)**  
1. **Importance of Documentation**  
   - Learn why documentation is crucial for maintainability and collaboration.  
   - Understand the different types of documentation (e.g., README, inline comments, user guides).  

2. **Best Practices**  
   - Explore best practices for writing clear and concise documentation.  

---

#### **Coding (4 hrs)**  
**Objective**: Write documentation for the app.  

1. **Create a README File** (1.5 hrs)  
   - Add a `README.md` file to the project root:  
     ```markdown
     # Automated Financial Report Generator

     ## Overview
     This app fetches financial data (e.g., stock prices) and generates a summary report using the ChatGPT API. Users can export reports as PDF or CSV.

     ## Features
     - Fetch stock data using Alpha Vantage API.
     - Generate summaries using ChatGPT API.
     - Export reports as PDF or CSV.
     - View report history with `localStorage` persistence.

     ## Installation
     1. Clone the repository:
        ```bash
        git clone https://github.com/your-username/financial-report-generator.git
        ```
     2. Install dependencies:
        ```bash
        npm install
        ```
     3. Add API keys:
        - Create a `.env` file in the root directory.
        - Add your Alpha Vantage and ChatGPT API keys:
          ```
          REACT_APP_ALPHA_VANTAGE_API_KEY=your_api_key
          REACT_APP_CHATGPT_API_KEY=your_api_key
          ```

     ## Usage
     1. Start the development server:
        ```bash
        npm start
        ```
     2. Enter a stock symbol (e.g., `AAPL`) and click "Generate Report."
     3. View the generated report and export it as PDF or CSV.

     ## Deployment
     Deploy the app to Netlify:
     ```bash
     npm run build
     netlify deploy --prod
     ```

     ## Technologies
     - React
     - Alpha Vantage API
     - ChatGPT API
     - React Router
     - `localStorage` for persistence

     ## License
     MIT
     ```  

2. **Add Inline Comments** (1.5 hrs)  
   - Add comments to key components and functions:  
     ```javascript
     // src/components/InputForm.js
     function InputForm({ onSubmit }) {
       const [symbol, setSymbol] = useState('');
       const [error, setError] = useState('');

       // Handle form submission
       const handleSubmit = async (e) => {
         e.preventDefault();
         setError('');
         try {
           const data = await fetchStockData(symbol);
           if (data['Error Message']) {
             throw new Error('Invalid stock symbol');
           }
           onSubmit(data);
           setSymbol('');
         } catch (err) {
           setError(err.message);
         }
       };

       return (
         <form onSubmit={handleSubmit} className="input-form">
           <input
             type="text"
             value={symbol}
             onChange={(e) => setSymbol(e.target.value)}
             placeholder="Enter stock symbol (e.g., AAPL)"
             required
             aria-label="Stock symbol"
           />
           <button type="submit" aria-label="Generate report">
             Generate Report
           </button>
           {error && <p className="error">{error}</p>}
         </form>
       );
     }
     ```  

3. **Write a User Guide** (1 hr)  
   - Add a `USER_GUIDE.md` file:  
     ```markdown
     # User Guide

     ## Getting Started
     1. Open the app in your browser.
     2. Enter a stock symbol (e.g., `AAPL`) in the input field.
     3. Click "Generate Report" to fetch data and generate a summary.

     ## Features
     - **Report History**: View past reports in the "Report History" section.
     - **Export Reports**: Export reports as PDF or CSV using the buttons below the report.

     ## Troubleshooting
     - **Invalid Stock Symbol**: Ensure the symbol is correct (e.g., `AAPL` for Apple).
     - **API Errors**: Check your API keys and internet connection.
     ```  

---

#### **Review (30 mins)**  
1. **Test Your Documentation**:  
   - Verify the README and user guide are clear and accurate.  
   - Check that inline comments explain complex logic.  
2. **Debug**: Fix any typos or inaccuracies.  
3. **Refactor**: Ensure consistency in tone and style.  

---

### **Deliverables for Day 27**  
1. A React app with:  
   - A comprehensive `README.md` file.  
   - Inline comments explaining key components and functions.  
   - A user guide (`USER_GUIDE.md`) for non-technical users.  
2. A clear understanding of documentation best practices.  

---
---

### **Day 28: Final Review & Showcase**  
**Goal**: Review the app, fix any remaining issues, and prepare it for showcasing.  

#### **Theory (1.5 hrs)**  
1. **Final Review Checklist**  
   - Learn how to conduct a thorough review of your app (e.g., functionality, performance, accessibility).  

2. **Showcasing Your Work**  
   - Understand how to present your app effectively (e.g., portfolio, LinkedIn, GitHub).  

---

#### **Coding (4 hrs)**  
**Objective**: Review the app, fix issues, and prepare it for showcasing.  

1. **Conduct a Final Review** (2 hrs)  
   - Test all features:  
     - Fetch stock data and generate reports.  
     - Export reports as PDF and CSV.  
     - View and interact with report history.  
   - Check for bugs:  
     - Invalid inputs, API errors, and edge cases.  
   - Verify performance:  
     - Ensure the app loads quickly and runs smoothly.  
   - Test accessibility:  
     - Use screen readers and keyboard navigation.  

2. **Fix Remaining Issues** (1 hr)  
   - Address any bugs or performance issues identified during the review.  
   - Example: If the app crashes on invalid API keys, add error handling:  
     ```javascript
     if (!process.env.REACT_APP_ALPHA_VANTAGE_API_KEY || !process.env.REACT_APP_CHATGPT_API_KEY) {
       throw new Error('Missing API keys. Please check your .env file.');
     }
     ```  

3. **Prepare for Showcase** (1 hr)  
   - Update your portfolio:  
     - Add a project description, screenshots, and a link to the live app.  
   - Update your LinkedIn profile:  
     - Share a post about the project with a link to the live app.  
   - Update your GitHub repository:  
     - Ensure the README is comprehensive and the code is well-documented.  

---

#### **Review (30 mins)**  
1. **Test Your App**:  
   - Verify all features work as expected.  
   - Ensure the app is polished and ready for showcasing.  
2. **Debug**: Fix any last-minute issues.  
3. **Refactor**: Ensure the code is clean and well-organized.  

---

### **Deliverables for Day 28**  
1. A React app with:  
   - All features working as expected.  
   - No bugs or performance issues.  
2. A polished portfolio, LinkedIn post, and GitHub repository.  
3. A clear understanding of how to showcase your work effectively.  

---

### **Final Project Summary**  
You’ve built a fully functional **Automated Financial Report Generator** with:  
- **Core Features**: Fetch stock data, generate summaries, export reports, and view history.  
- **Advanced Features**: Error handling, accessibility, performance optimizations.  
- **Documentation**: README, inline comments, and user guide.  
- **Deployment**: Live app hosted on Netlify.  

---

### **Next Steps**  
1. **Share Your Work**:  
   - Showcase the app on your portfolio, LinkedIn, and GitHub.  
2. **Gather Feedback**:  
   - Share the app with peers or mentors for feedback.  
3. **Keep Learning**:  
   - Explore advanced React topics (e.g., Redux, Next.js) or other frameworks.  

---

DeepThink (R1) + Search

---

 February 2025