# Task Manager Project

## Basic Features:

1. **Decentralized Access:**

   - Users with a link can edit and contribute to the task pool without the need for login.
   - Allow users to input a nickname to make alterations.

2. **Creator Management:**
   - The person who created the pool can manage it through a login/authentication system.

## Additional Features:

3. **Real-Time Stats:**

   - Display a chart showing who has completed the most tasks.
   - Optionally, include hours worked (this can be added later).

4. **Multi-Language Support:**
   - Support both Portuguese (pt-BR) and English (en-US) languages.

## Implementation Steps:

### Frontend:

1. **Homepage:**

   - Display a form to input a nickname and access the task pool.
   - Allow users to contribute without login.

2. **Task Pool Page:**

   - Display the task pool with tasks and comments.
   - Allow users to edit and add tasks using their provided nickname.

3. **Login/Auth Page:**

   - Create a page for login/authentication for the person who created the pool.
   - Use some form of authentication (e.g., JWT, OAuth) for security.

4. **Real-Time Stats Page:**

   - Implement a page with a chart displaying real-time stats.
   - Optionally, include hours worked.

5. **Language Switcher:**
   - Add a language switcher to toggle between Portuguese and English.

### Backend:

1. **Task Pool API:**

   - Create API endpoints for CRUD operations on the task pool.

2. **User Authentication API:**

   - Implement user authentication for the person who created the pool.

3. **Real-Time Stats API:**

   - Implement an API to retrieve real-time stats for the chart.

4. **Localization API:**
   - Implement an API for handling multi-language support.

## Tech Stack:

### Frontend:

- React
- TypeScript
- Chakra UI or Material-UI for UI components
- Redux or React Query for state management
- Socket.IO for real-time updates (for the chart)
- i18next for internationalization (language switching)

### Backend:

- Node.js with Express
- MongoDB or any database for storing task pool data
- Passport.js for authentication
- Socket.IO for real-time updates
