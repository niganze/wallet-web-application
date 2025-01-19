# Wallet Web Application

## Overview
The Wallet Web Application is designed to help users like Eric, an employee of Code of Africa GmbH, manage their income and expenses efficiently across various accounts such as bank accounts, mobile money accounts, and cash. The application provides tools for tracking transactions, generating reports, setting budgets with notifications, categorizing expenses, and visualizing transaction summaries.

## Features

### Core Functionalities
1. **Transaction Tracking**:
   - Add, view, and manage income and expense transactions across multiple accounts (bank, mobile money, cash).

2. **Report Generation**:
   - Generate reports for specific time periods (e.g., weekly, monthly).

3. **Budget Management**:
   - Set a monthly budget limit and receive notifications when expenses exceed the limit.

4. **Expense Categorization**:
   - Create and manage categories and subcategories for expenses.
   - Link transactions to specific categories for better tracking.

5. **Visualization**:
   - Graphical summaries of income and expenses using pie charts, bar charts, etc.

### User Experience (UX)
- Responsive and intuitive design for both desktop and mobile devices.
- Clean interface for easy navigation and data visualization.

## Technology Stack

### Frontend
- ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB): Dynamic and responsive user interfaces.
- ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white): Modern and flexible styling framework.

### Backend
- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white): API development and server-side logic.
- MongoDB: NoSQL database for managing transactions, categories, and budgets.

### Data Visualization
- Chart.js: Render interactive graphs and charts for transaction summaries.

### Deployment
- **Frontend**: Deployed on [Netlify](https://www.netlify.com).
- **Backend**: Deployed on [Render](https://render.com).
- **Database**: Hosted on MongoDB Atlas.

## Setup Instructions

### Prerequisites
- ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white) (v16 or later) and npm installed.
- MongoDB Atlas account.
- ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) installed.

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Navigate to the project directory:
   ```bash
   cd wallet-web-application
   ```
3. Install dependencies for both backend and frontend:
   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```
4. Set up environment variables:
   - Create a `.env` file in the `backend` directory with the following:
     ```env
     MONGO_URI=<your-mongodb-atlas-uri>
     JWT_SECRET=<your-secret-key>
     ```
5. Start the backend server:
   ```bash
   cd backend
   npm start
   ```
6. Start the frontend development server:
   ```bash
   cd frontend
   npm start
   ```
7. Open the application in your browser at `http://localhost:3000`.

## Deployment

### Hosting Services
- **Frontend**: Netlify
- **Backend**: Render

### Steps to Deploy
1. Push the latest code to your GitHub repository.
2. Connect the frontend folder to Netlify for deployment.
3. Connect the backend folder to Render for deployment.
4. Ensure MongoDB Atlas is properly configured.
5. Add deployment links to the README file.

## Expected Functionalities
- Accurate tracking of transactions across multiple accounts.
- Dynamic report generation based on time range.
- Real-time budget notifications.
- Intuitive expense categorization.
- Visualized transaction summaries.

## Contribution Guidelines
- Fork the repository and create a feature branch.
- Write clear and concise commit messages.
- Ensure code follows the project’s style guidelines.
- Submit a pull request with a detailed description of changes.

## License
This project is licensed under the MIT License.

---

### Deployment Links
- Frontend: [Frontend Live](https://ericwallets.netlify.app/)
- Backend: [Backend Live](https://walletbacked.onrender.com)

