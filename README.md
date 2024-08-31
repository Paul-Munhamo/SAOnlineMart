SA Online Mart
Overview
SA Online Mart is an online platform designed to promote local South African products by providing a seamless shopping experience for customers nationwide. The platform features a diverse range of products, from handcrafted jewelry to locally-produced clothing. It supports South African artisans and small businesses, helping them reach a wider audience and boost their sales. This README provides all the necessary steps to set up, develop, test, and release the application.
Local Setup - Creating the Application
Steps
Clone the Repository:
git clone https://github.com/PaulM-Tec/SAOnlineMart.git
Navigate to the Project Directory:
cd SAOnlineMart
Set Up the Back-End:
Navigate to the backend directory:
cd backend
Restore .NET packages:
dotnet restore
Update the database connection string in appsettings.json:
"ConnectionStrings": { "DefaultConnection": "your_connection_string" }
Run the back-end server:
dotnet run
Set Up the Front-End:
Navigate to the frontend directory:
cd ../frontend
Install dependencies:
npm install
Start the development server:
npm start
Local Development - Developer Workflow
Steps
Clone the Repository:
git clone https://github.com/PaulM-Tec/SAOnlineMart.git
Navigate to the Project Directory:
cd SAOnlineMart
Install Dependencies:
For the back-end:
cd backend
dotnet restore
For the front-end:
cd ../frontend
npm install
Recommended VS Code Extensions:
C# (for .NET development)
ESLint (for JavaScript/React development)
Start Development Servers:
Back-end:
cd backend
dotnet run
Front-end:
cd ../frontend
npm start
Local Testing
Steps for Visual Studio Code
Open the Project in VS Code:
Open your terminal in VS Code or use the integrated terminal.
Serve the Application Locally:
For the back-end:
cd backend
dotnet run
For the front-end:
cd ../frontend
npm start
Inspect the Application:
Once the webpage loads, right-click and select “Inspect”.
On the developer tools bar, select the “>>” icon to expand the options.
Click on “Console” to view any logs or errors.
Local Release - Building and Deploying
Steps for Building and Deploying the Application
Build the Back-End:
cd backend
dotnet publish -c Release -o ./publish
Build the Front-End:
cd ../frontend
npm run build
Deploy the Application:
Deploy the back-end from the backend/publish directory to your server.
Deploy the front-end from the frontend/build directory to your web server.
This README should help you set up, develop, test, and release your SA Online Mart application.