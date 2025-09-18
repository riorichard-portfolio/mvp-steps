# Steps to Build an MVP Application

## 1. Define User Flow
- Define the journey of the user when using the app.  
- Example: user logs in → adds a todo → views the todo list.

## 2. Sketch Application Design
- Create simple wireframes to visualize the user flow.  
- Focus only on the essential features (MVP).

## 3. Build Backend
### 3.1 Define Domains
- Example: Auth, Todo.

### 3.2 Define Business Entities
- Example: `LoginResponse`, `TodoList`.

### 3.3 Define Interfaces for Usecase & Repository
- Example: `AuthUsecase`, `TodoUsecase`, `UserRepository`, `TodoRepository`.

### 3.4 Implement Code
- Write implementation for usecases & repositories based on their interfaces.

### 3.5 Integrate Usecases with Delivery/Controller
- Connect usecases to the delivery/controller layer.

### 3.6 Attach Controllers to Routers
- Map each controller to its respective route.

## 4. Build Frontend
### 4.1 Define APIs to Call
- Example: `/login`, `/todos`.

### 4.2 Create Each Page
- Example: LoginPage, TodoPage.

### 4.3 Assign Routes
- Example: `/login`, `/todo`.

### 4.4 Integrate Pages & Components with APIs
- Connect UI components with backend APIs.

## 5. Testing
### 5.1 Test All Features
- Validate the entire flow from frontend → backend → database.

### 5.2 Fix All Bugs
- Debug and fix any issues found during testing.

## 6. Deployment
- Deploy both backend and frontend to a server/hosting.  
- Ensure all services are accessible by end users.
