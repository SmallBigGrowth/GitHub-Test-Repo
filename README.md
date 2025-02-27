## **Project Description: Task Management Dashboard**
### **Overview:**
You need to build a **Task Management Dashboard** where users can **add tasks, update their status, delete tasks, and filter them**. Additionally, implement **user authentication**, **theme switching**, and ensure the application is **well-tested using Jest & React Testing Library**.

---

## **Technical Requirements**
### **1. Core Functionalities**
#### ✅ **Task Management (CRUD)**
- Users can **add tasks** with a title, description, and priority.
- Users can **mark tasks as completed**.
- Users can **delete tasks**.
- Users can **edit tasks**.

#### ✅ **Task Filtering & Sorting**
- Users can **filter tasks** by:
  - **Completion status** (Completed / Pending)
  - **Priority** (Low / Medium / High)
- Users can **sort tasks** by:
  - **Newest first**
  - **Oldest first**

#### ✅ **Persistent Storage**
- Use **localStorage** or a mock API to persist tasks.

---

### **2. UI & State Management**
#### ✅ **Theme Switcher (Dark/Light Mode)**
- Implement a **theme toggle** using the **Context API**.
- Theme preferences should persist between sessions using **localStorage**.

#### ✅ **User Authentication (Mock)**
- Allow users to **log in and log out**.
- Store user information in **Context API**.
- If a user is not logged in, they should be redirected to the login page.

#### ✅ **Performance Optimization**
- Use **React.memo** for optimizing unnecessary re-renders.
- Use **useCallback** and **useMemo** where applicable.

---

### **3. API & Data Handling**
#### ✅ **Mock API Integration**
- Fetch a list of predefined tasks from a **mock API (JSONPlaceholder or Mock JSON file)**.
- Display a loading spinner while data is being fetched.
- Handle API errors gracefully.

#### ✅ **Custom Hooks**
- Create a **custom hook (`useFetchTasks`)** to fetch and manage tasks.

---

### **4. Testing Requirements**
#### ✅ **Unit Tests (Jest + React Testing Library)**
Write tests for:
1. **TaskForm Component:**  
   - Ensures users can type in input fields.
   - Submitting the form adds a task.
  
2. **TaskList Component:**  
   - Renders a list of tasks.
   - Filters tasks correctly.

3. **Theme Toggle Feature:**  
   - Ensures theme state changes when the toggle is clicked.
  
#### ✅ **Integration Tests**
- Mock API requests and test API handling.
- Test the login/logout functionality.

#### ✅ **End-to-End (E2E) Testing (Optional)**
- Use **Cypress** or **Playwright** to test the full user flow.


---

## **Bonus Features (Extra Points)**
🔹 **Drag & Drop** support for reordering tasks (using `react-beautiful-dnd`).  
🔹 **Animations** for smoother UI interactions (`Framer Motion`).  
🔹 **Progress Indicator** showing task completion percentage.  

---

## **Assessment Criteria**
| Category | Points |
|----------|--------|
| **Task Management Functionality** | 20 |
| **Filtering & Sorting** | 10 |
| **Theme & Context API** | 10 |
| **Authentication Handling** | 10 |
| **API Integration & Data Handling** | 10 |
| **Performance Optimization** | 10 |
| **Testing Coverage** | 20 |
| **Code Quality & Documentation** | 10 |
| **Total Score** | **100** |

---

## **Submission Requirements**
- Upload your project to a **GitHub repository**.
- Include a **README.md** with:
  - Project setup instructions.
  - Explanation of components and features.
  - List of technologies used.
- Share the GitHub repo link.

---

This test evaluates **real-world skills** needed for a frontend React developer role. 🚀  
Would you like any modifications or additional complexity?
