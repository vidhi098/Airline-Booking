### Prerequisites:
1. Eclipse for Enterprise and Core Java installed
2. Tomcat server installed
3. MySQL server installed
4. Jenkins installed
5. Postman installed
6. NodeJS and newman installed

### Step 1: Serve dummy app
1. Extract the capstone zip folder and locate the Dummy App folder.
2. Import the flyaway.war file in Eclipse.
3. Run the script from FlyAway_DBScript file in your MySQL server command prompt to set up the database.
4. Update Maven for your project.
5. Right-click on the project in Eclipse and run it on the server.

### Step 2: Execute Jenkins jobs
1. Open Jenkins in your browser.
2. Navigate to Manage Jenkins => Manage Plugins => Available Tab, then search for "Deploy to container" Plugin and install it. 
