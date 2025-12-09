# Contributing Guidelines

Thank you for contributing to the **Virtual Closet – AI Outfit Management System**.  
This project is developed by a team of three, and these guidelines ensure smooth collaboration and clean code.

---

## 🛠 Project Setup

1. Clone the repository:
   ```
   git clone https://github.com/your-username/virtual-closet.git
   ```
2. Navigate into project folders:
   ```
   cd virtual-closet
   ```
3. Install dependencies:
   - Frontend (React)
     ```
     cd client
     npm install
     ```
   - Backend (Node/Express)
     ```
     cd server
     npm install
     ```

---

## 🌿 Branching Strategy

To avoid conflicts, **never push code to the main branch directly**.

Use this pattern:

- `main` → Production-ready code  
- `dev` → All team development merges here  
- `feature/<feature-name>` → Work on individual features  

### Example:
```
feature/authentication
feature/image-upload
feature/outfit-planner
```

When you create a new feature:
```
git checkout -b feature/your-feature-name
```

---

## 🔄 Pull Requests (PRs)

1. Commit all changes  
2. Push your feature branch:
   ```
   git push origin feature/your-feature
   ```
3. Open a Pull Request:
   - Base branch → `dev`
   - Compare branch → your `feature/*` branch  
4. Add a clear description:
   - What you built  
   - Any dependencies added  
   - Screenshots (if UI)

5. Wait for at least 1 team member to approve  
6. Merge after approval

---

## 🧹 Coding Standards

### JavaScript Guidelines
- Use **ES6+ syntax**
- Use `const` and `let` (avoid `var`)
- Use arrow functions  
- Keep components small  
- Directory conventions:
  - `PascalCase` for React components  
  - `camelCase` for variables and functions  

### Commit Message Format
Use this structure:

```
type: short description

Detailed explanation (optional)
```

**Types:**
- feat → new feature  
- fix → bug fix  
- docs → documentation changes  
- style → formatting  
- refactor → code restructure  
- chore → misc tasks

**Example:**
```
feat: add user login API
```

---

## 🐞 Reporting Issues

If you find a bug, open an Issue with:
- Title  
- Steps to reproduce  
- Expected result  
- Actual result  
- Screenshot (if possible)

---

## 👥 Team Roles

| Member | Role | Responsibilities |
|--------|------|------------------|
| Member 1 | Frontend Lead | UI, components, routing |
| Member 2 | Backend Lead | APIs, DB models, authentication |
| Member 3 | AI/Integration Lead | Image tagging, outfit generator |

---

## ✔ Best Practices

- Keep Pull Requests small  
- Write meaningful commit messages  
- Sync `dev` branch before starting new feature:
  ```
  git pull origin dev
  ```
- Communicate with team before working on overlapping features

---

Thank you for contributing!

