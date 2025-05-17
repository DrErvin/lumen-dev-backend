# Ekipa Project - Student Platform (Backend)

This is the backend server for the Ekipa-Student Platform. It provides APIs for managing user accounts, job opportunities, applications, and AI-powered smart search.

### ⚠️ Important Prerequisites

For this project to function correctly, you must have the following:

**1. A Separate Frontend Repository**

- Instructions on how to run and set up the frontend are available in its README file.

---

### 🔧 Project Setup (Backend)

**1. Install Dependencies**

Ensure you have Node.js installed on your machine. Then, clone this repository and install dependencies.

**2. Start the Backend Server**

✅ Recommended: Stable Production-Like Mode

- To run the backend server without restarts on file changes (best for testing and production-like usage), use:

- ```
  npm start
  ```

- This ensures that server restarts are controlled and prevents interruptions due to file changes.

⚠️ Development Mode (Optional)

- For live-reloading during development, use:

- ```
  npm run dev
  ```

- This automatically restarts the server when files change.
  However, it can be unstable and cause issues with ongoing requests.

---

### 📌 API Endpoints

**1. Opportunities**

- GET /opportunities → Fetch all opportunities.
- POST /opportunities → Add a new opportunity.

**2. Applications**

- GET /applications → Fetch all submitted applications.
- POST /applications → Submit a new application (supports file uploads).

**3. Smart Search (AI-Powered)**

- POST /smart-search → Search applications using DeepSeekV3 AI.

**4. List of World Universities**

- GET /world-universities → Fetches the list of World Universities and their domains.
