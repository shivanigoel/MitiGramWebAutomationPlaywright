<!DOCTYPE html>
<html>

<head>
  Mitigram Assignment - Playwright Test Scenarios
</head>

<body>

  <h1>Introduction</h1>
  <p>This repository contains Playwright test scenarios to validate the Login flow of the Mitigram portal, and the Careers page.</p>


  <h2>Folder Structure</h2>
<ul>
  
  ![image](https://github.com/shivanigoel/MitigramWebAutomation/assets/27926245/ac9c137c-24d7-4a88-980b-6381f8d43c26) 
  
</ul>


  <h2>Prerequisites</h2>
  <p>Ensure the following dependencies are installed before building and running the test suite:</p>
  <ul>
    <li>Node.js</li>
    <ul>
      <li><a href="https://nodejs.org/">Check Node.js Installation</a></li>
      <li>Run the command <code>node -v</code> in a terminal. It should display the installed Node.js version (e.g., v21.5.0).</li>
    </ul>
  </ul>

  <h3>Execute Testcases</h3>

  <h4>Execute Full Suite</h4>
  <p>Run the command <code>npm test</code> in a terminal from the project root directory.</p>

  <h4>Execute Specific Test Cases</h4>
  <p>Run the command <code>npx playwright test {path to the test file}</code> in a terminal from the project root directory. Update <code>{path to the test file}</code> according to the test case you want to run.</p>
  <p>Example: <code>npx playwright test careerTest.spec.js --project chromium</code></p>

  <h3>View Test Results Report</h3>
  <p>Open the file <code>testReports/testResults.html</code> in a web browser to view the HTML test results report.</p>

  <h3>View Test Logs</h3>
  <p>Open the file <code>logs/mitigram-playwright-test.log</code> to view the outputs logged to the file.</p>

</body>

</html>
