# Research_project
#Enhancement of a Python Reporting Framework and Integration into a DevOps Environment
#Project Overview
This project focuses on enhancing an existing Python-based reporting framework and integrating it into a DevOps environment. Key improvements include expanding log handling capabilities, implementing unit and integration tests, and integrating nUnit report parsing.

Features and Enhancements
✅ Task 1: Extend Framework to Accept Wildcard Symbols for Logs
Enhanced logging framework to support wildcard symbols (*, #) for directories and file paths, enabling flexible log management.
Replaced absolute path dependencies with relative paths and regex-like wildcards.
Updated the xrep tool to support wildcard-based log file selection.
✅ Task 2: Extend Framework with Unit Tests
Developed comprehensive unit tests using Python's unittest and mock libraries, achieving 80% code coverage.
Integrated the project with SonarQube to ensure code quality and maintainability.
Committed test cases to Bitbucket and linked xrep to SonarQube for continuous analysis.
✅ Task 3: Evaluate Options to Parse nUnit Reports with Python
Analyzed the existing xUnit report parsing process and explored options for supporting nUnit reports.
Tested and validated nUnit report parsing with sample XML reports.
Confirmed seamless integration of nUnit reports into the reporting framework.
✅ Task 4: Implement nUnit Report Parsing to xRep
Developed an nUnit report parser for the xRep framework using Python.
Designed and integrated XML-based parsing for nUnit reports.
Successfully ensured smooth incorporation into the existing framework.
✅ Task 5: Extend Framework with Integration Tests
Implemented Integration Tests, including CAT tests for validating functions, templates, reports, database initialization, and metadata.
Developed and committed a Groovy script to Bitbucket, integrating it with Jenkins for CI/CD automation.
Extended the xRep build pipeline with CAT tests to ensure continuous validation.
Technologies Used
Python (Logging, Unittest, XML Parsing)
Bitbucket (Version Control)
SonarQube (Code Quality & Coverage)
Jenkins (CI/CD Integration)
Groovy (Automation Scripting)
nUnit & xUnit (Report Parsing)
Regex & Wildcards (Log Handling)
Future Scope
Enhance logging capabilities further by supporting custom filters and handlers.
Improve performance optimizations for large-scale XML parsing.
Implement real-time monitoring dashboards for reporting frameworks.
Contact
For more details, feel free to connect with me on LinkedIn.
