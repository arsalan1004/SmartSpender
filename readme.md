# SmartSpender -- Personal Finance Manager

SmartSpender is a powerful personal finance tracker web application built using React and Node.js. It empowers users to manage their finances effectively, track expenses, monitor income, and gain valuable insights into their spending habits.

With SmartSpender, users can effortlessly create and manage their financial transactions, including income, expenses, and subscriptions. Transactions can be categorized using predefined categories such as groceries, transportation, dining, entertainment, and more. The application provides clear visualizations and charts to help users analyze their budget and make informed financial decisions.

# use this credentials for demo:
    - email: dummy@g.com
    - password: 12121212

## SmartSpender Development Journey with Copilot's Assistance

The development of SmartSpender was a unique and innovative experience, fueled by the remarkable capabilities of GitHub Copilot. This cutting-edge AI-powered code generation tool significantly transformed our development process and opened up exciting new possibilities. Here's a glimpse into how we leveraged Copilot's potential and the remarkable advantages it brought to our project:

1. **Intelligent Code Generation**: Copilot served as our intelligent coding partner, assisting us in generating complex code structures, implementing intricate algorithms, and producing boilerplate code. By understanding the context of our project, it offered relevant and precise code snippets, substantially reducing development time and effort.

2. **Adapting to our Coding Style**: Copilot seamlessly integrated with our established coding conventions and best practices, promoting a consistent coding style throughout the project. By adhering to industry-standard formatting, naming conventions, and indentation rules, Copilot ensured that our code was well-structured and easy to follow for developers working on the project.

3. **Precise Code Suggestions**: Copilot's code suggestions were accurate and contextually relevant, enhancing the readability and understandability of our code. It provided us with intuitive variable names, clear function and method signatures, and concise yet descriptive comments, ensuring that the purpose and functionality of our code were crystal clear.

4. **Enhanced Code Readability**: Copilot proved invaluable in our code refactoring efforts, suggesting improvements to our existing codebase. It helped identify redundant code, eliminate unnecessary complexity, and propose more concise and efficient implementations. These automated refactoring suggestions significantly improved code readability by making it more streamlined and focused.

5. **Error-free Code**: Copilot's advanced machine learning algorithms analyzed our code context and provided accurate suggestions to prevent common errors. It helped us catch syntax mistakes, undefined variables, and other common coding pitfalls before they caused issues. Copilot generated code snippets that efficiently handled error scenarios. It offered suggestions for try-catch blocks, error handling mechanisms, and error logging, ensuring robust error handling in our application.

SmartSpender's development journey was uniquely shaped by our collaboration with GitHub Copilot. The amalgamation of human creativity and AI-powered code generation propelled us towards building an exceptional personal finance tracker that exceeds expectations.

# Work Proof

More detailed information such as screenshots (./screenshots.md), a demo video (./media/hackathon_video.webm) showcasing the application's extensive features ([Features](./userguide.md#features)), and intuitive usage instructions can be found in the User Guide ([User Guide](./userguide.md)) and Screenshots ([Screenshots](./screenshots.md)) files.

## Architecture and Technical Details

The project is built using the following MERN technologies and frameworks:

- Frontend: ReactJs, Redux, JavaScript, HTML, CSS
- Backend: Node.js with Express
- Database: mongoDB

## Mongo Database Models

The application consists of the following entities:

1. Transaction:
   - ID: String or Number
   - Description: String
   - Amount: Number
   - Type: String (income or expense or subscription)
   - Category: String
   - Cycle: String (monthly, quarterly, or annual)
   - Status: Boolean
   - Auto: Boolean
   - Date: Date

2. User:
   - First Name: String
   - Last Name: String
   - Date of Birth: Date
   - Salary: Number
   - Email: String (required, unique)
   - Image: String
   - Password: String (required)
   - Currency: String (default: "INR")
   - Expense: Number (default: 0)
   - Expense List: Array (default: [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0])
   - Income: Number (default: 0)
   - Income List: Array (default: [0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0])
   - OTP: String (default: "")
## Installation and Usage

### 1. Grabbing the Code:

   - Fire up your command-line interface (CLI) or terminal.
   - Use the `cd` command to navigate to your desired directory for the project.
   - Once you're in the right spot, utilize the `git clone` command followed by the repository URL to clone the project.
   - Sit back and relax while the cloning process does its magic.
   - Congratulations, you've got the code!

### 2. Setting Up Dependencies:

#### Prerequisites

   - Make sure you have Node.js ([https://nodejs.org/en](https://nodejs.org/en)) and npm (Node Package Manager) installed on your system. You can find them at the provided link.

#### Steps

 1. Double-check that the cloning process from step 1 finished successfully without any errors.

 2. In your command-line interface (CLI) or terminal, navigate to the project's root directory.

 4. Switch directories to `SmartSpenderServer` and run the following commands to install the project's dependencies and start the API server:

     ```bash
     npm install
     npm start
     ```

 5. Now, switch directories to `SmartSpender` and run these commands to install the project's dependencies and start the UI server:

     ```bash
     npm install
     npm start
     ```

### 3. Starting the API Server:

   - Create a file named `.env` in the root directory of the `SmartSpenderServer` folder. This file will store some sensitive information. Add the following lines to the `.env` file, replacing the placeholders with your actual values:

     ```
     #Mongo Auth value
     db_USERNAME = ""
     db_PASSWORD = ""

     JWT_SECRET = ""
     EMAIL = ""
     PASSWORD = ""

     PORT = 5000
     ```

   - Now, in the `SmartSpenderServer` folder, run the following command to start the API server:

     ```bash
     npm start
     ```

### 4. Launching the UI Server:

   - Switch directories to `SmartSpender` and run this command to start the UI server:

     ```bash
     npm start
     ```

### 5. Accessing the Application:

   - Open your favorite web browser and navigate to http://localhost:3000 to access the SmartSpender application.


## User Guide

For detailed instructions on using SmartSpender and exploring its features, refer to the [User Guide](./userguide.md) file.
