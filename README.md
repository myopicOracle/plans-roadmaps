# **Plans & Roadmaps**

Programming hard. Choosing path harder. 

Planning good. Detailed planning better. 

So I make plan to make less hard. Then I put here. 

Becoz sharing is caring. 

Live long and prosper. 🖖

---
### *This repo currently contains the following plans:*

## **I. Master React in 28 Days**
- Project-Based Learning + Theory (50/50 Split)
- Theory structured around [The Odin Project](https://www.theodinproject.com/paths/full-stack-javascript/courses/react)
 (80%) & [Full Stack Open](https://fullstackopen.com/en/part1/introduction_to_react)
 (20%)
- Hands-on exercises very specific, with step-by-step and solution code
- Builds several smaller projects and 1 final progressively over the 28 days
- Pros: Learn the fundamentals well, prep for other libraries and frameworks
- Cons: If purely learning theory, could knock this out in half the time


---
#### *[Master_React_28_Days.md](https://github.com/myopicOracle/plans-roadmaps/blob/main/Master_React_28_Days.md)*

### **Sample Daily Breakdown**

### **Day 1:** *Intro to React & Components*
**Goal**: Understand React basics, set up a project, and build static components.  

---

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

#### *For fullsome plan, see*  **[Master_React_28_Days.md](https://github.com/myopicOracle/plans-roadmaps/blob/main/Master_React_28_Days.md)**