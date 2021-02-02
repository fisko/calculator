[![Board Status](https://fisko.visualstudio.com/89dbd02f-9235-41db-948a-ba143c9ed159/86bc0833-c3d1-4bc9-acd9-b58a0ace5b23/_apis/work/boardbadge/73190900-4094-4ce5-91ea-802d65af90ed)](https://fisko.visualstudio.com/89dbd02f-9235-41db-948a-ba143c9ed159/_boards/board/t/86bc0833-c3d1-4bc9-acd9-b58a0ace5b23/Microsoft.RequirementCategory)
Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

