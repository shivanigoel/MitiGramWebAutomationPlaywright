<!DOCTYPE html>
<html>

<head>
  Mitigram Assignment - Playwright Test Scenarios
</head>

<body>

  <h1>Introduction</h1>
  <p>This repository contains Playwright test scenarios to validate the Login flow of the Mitigram portal, the Careers page, and the Newsletter section.</p>

  <h2>Supported Operating Systems</h2>
  <ul>
    <li>Windows</li>
    <li>Linux</li>
    <li>Mac</li>
  </ul>

  <h2>Folder Structure</h2>
  <ul>
    <li><strong>src:</strong> Root package of the core components of the framework.</li>
    <li><strong>pages:</strong> Page Classes following the Page Object Model (POM) design pattern.</li>
    <li><strong>steps:</strong> Steps classes containing methods encapsulating interactions and validations.</li>
    <li><strong>test:</strong> Test cases.</li>
    <li><strong>utils:</strong> Utility classes.</li>
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

  <h2>Configure Test Suite (Before Run)</h2>
  <p>Open the file <code>config/config.json</code>.</p>
  <p>Adjust the following configurations:</p>
  <ul>
    <li><code>PLAYWRIGHT_TIMEOUT:</code> Timeout configurations used in Playwright.</li>
    <li><code>BROWSER:</code> Browser configuration (e.g., 'chromium', 'firefox'). Default is 'chromium'.</li>
  </ul>

  <h2>Build and Run Locally</h2>

  <h3>Install Dependencies</h3>
  <p>Run the command <code>npm install</code> in a terminal from the project root directory to install the dependencies.</p>

  <h3>Execute Testcases</h3>

  <h4>Execute Full Suite</h4>
  <p>Run the command <code>npm test</code> in a terminal from the project root directory.</p>

  <h4>Execute Specific Test Cases</h4>
  <p>Run the command <code>npx playwright test {path to the test file}</code> in a terminal from the project root directory. Update <code>{path to the test file}</code> according to the test case you want to run.</p>
  <p>Example: <code>npx playwright test src/test/careersPageTests.ts</code></p>

  <h3>View Test Results Report</h3>
  <p>Open the file <code>testReports/testResults.html</code> in a web browser to view the HTML test results report.</p>

  <h3>View Test Logs</h3>
  <p>Open the file <code>logs/mitigram-playwright-test.log</code> to view the outputs logged to the file.</p>

</body>

</html>
