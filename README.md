<h1 align="center">Personal Finance Management App 🏦</h1>

## Project Overview 📝
This project aims to develop a user-friendly personal finance management application that enables users to have effective control over their monthly expenses and earnings. The application intends to be simple yet robust, offering features such as user registration via email, detailed financial summaries, and automatic notifications for fixed monthly expenses.

## Features 🛠️

### **1. User Registration and Authentication 🔒**
  - Allows users to sign up and authenticate using a valid email and secure password.
### **2. Email Confirmation 📧**
  - Validates the provided email address through an email confirmation system.
### **3. Expense and Earnings Logging 💰**
  - Enables users to log and categorize their monthly expenses and earnings.
### **4. Financial Dashboard 📊**
  - Offers a comprehensive overview of the user's financial situation through a dashboard with consolidated information, charts, and tables.
### **5. Fixed Expense Notifications 📅**
  - Sends automatic notifications to users at the beginning of each month, reminding them of their impending fixed expenses.

## Scope 🎯

### 1.  Data Collection and Usage from External Applications 📊

User data, including email, name is collected during the registration and login process. Authentication is managed via email-based sign-up and login.

### 2. Pre-processing and Analysis 🔍
The backend developed in C# and SQL Server processes the data collected from the users. It validates the input, performs necessary calculations for financial summaries, and returns only the necessary data to the frontend.

### 3. Interface Design 🎨
The UI/UX design has been carefully crafted using Figma, adhering to best practices in user experience and interface design. The frontend utilizes React, TypeScript, and Tailwind CSS to implement this design.

### 4. Development 👨‍💻
The backend is powered by C# with SQL Server for data persistence, offering robust and efficient data management and calculations. The API is deployed on Heroku and the SQL on AWS RDS

The frontend is developed in React and TypeScript with Tailwind CSS for styling. It provides a user-friendly interface for managing finances and is deployed on Vercel.

### 5. Quality Assurance 🧪
Quality assurance is managed through the implementation of unit tests on both the backend and frontend. The backend uses xUnit for testing, while the frontend uses Jest and React Testing Library. SonarQube is also integrated to ensure code quality.

### 6. CI/CD 🔄
The CI/CD pipeline for the backend is managed through Heroku and GitHub, with automated tests and deployments. The frontend uses Vercel and GitHub for continuous integration and deployment.

### 7. Observability 👀
Monitoring and observability are handled through DataDog, which provides real-time insights into the application's performance and health.

## Restrictions 🚫
The app does not support automatic synchronization of financial data with any digital banks. This means you will need to manually input all your transactions, including income and expenses, into the app to make use of its financial management features.

To keep the Personal Finance Management App operational, the project uses AWS RDS for database storage. Costs may vary depending on the volume of requests and data storage needs each month. It's crucial to budget for AWS RDS costs to ensure the application remains available and performs optimally.


## Trade-offs ⚖️
### 1. Portability 📱
The Personal Finance Management App is primarily a web-based application optimized for desktop use, potentially limiting its accessibility on mobile devices or offline scenarios.

Consideration: While being web-based provides a robust interface for complex financial tasks, users who are more mobile-centric may find it less convenient.

### 2. Functionality 🛠️
The app offers a comprehensive range of features, including expense tracking, income monitoring, and financial projections.

Consideration: While an extensive feature set makes the application versatile, it could also increase its complexity, potentially confusing users who are looking for a simplified experience.

### 3. Usability 🖱️
The design, done in React and TypeScript with Tailwind CSS, aims to offer an intuitive and visually pleasing experience but may not cater to all user preferences.

Consideration: High usability standards are essential for user retention, but aesthetic and navigational choices might not please everyone.

### 4. Efficiency ⏱️
Given the complex calculations and data fetching from the C# and SQL Server backend, there may be instances where the application experiences slight delays in responsiveness.

Consideration: Efficiency is crucial for a smooth user experience. However, optimizing for speed might necessitate compromises in the level of detail or the types of features offered.

### 5. Maintainability 🛠️
The backend in C# and SQL Server, along with the frontend in React and TypeScript, requires ongoing maintenance for security, bug fixes, and new features, which can be resource-intensive.

Consideration: Maintainability ensures the application's longevity and security but may divert resources from new feature development or other aspects of the project.

## C4 Model 🏗️📊
You can find the C4 Model by [clicking here!](/docs/C4Model/c4-models.md)

## Use Case 📑🎯
You can find the use case by [clicking here!](/docs/Requirements/requirements.md)

## Requirements 📋✅
You can find the requirements by [clicking here!](/docs/Requirements/requirements.md)

## Tech Stack 💻

**Front-end:** React, TailwindCSS

**Back-end:** .NET Core 6.0

**Database:** SQLServer

**Other Tools:** AWS RDS

## Repositories URLs 🌐
**Backend Repository**
 - [Backend Repository URL](https://github.com/VitorRoecker/expense-control-portfolio-backend)
 
**Frontend Repository**
 - [Frontend RepositoryUrl](https://github.com/VitorRoecker/expense-control-portfolio-frontend)


## Contact 📞
For any questions or concerns, please contact Vitor Adriel Roecker at vitoradrielroecker@gmail.com.

##
Thank you for considering or using this project! Feel free to star ⭐ the repository if you find it helpful!
