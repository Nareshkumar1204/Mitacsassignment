# Project Setup

1. Extract .zip file
2. Open the project folder in an IDE(Preferred VS code) of your choice
3. Open the terminal inside that project folder and run command `npm install`
4. Make sure you see the `node_modules` folder and `package-lock.json` file in your directory.
5. Run `npx cypress run --browser chrome --headed --reporter mochawesome` to open cypress runner
6. Select the spec file "PwdGenerator.js" and click on it
7. The approach used here is Data driven approach where the data gets fed to test case from the excel sheet "uploader.xlsx" under fixture
8. PwdLength, PwdType, PwdContent, the data for these three paramets needs to be configured in the above excel sheet
9. Once the execution is completed open the "uploader.xlsx" file under fixture to retrieve all the generated passwords
