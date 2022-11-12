# RockersSoftwareAssessment

Steps for execution:
--------------------

1. Open Project directory
2. Open Command Window
3. Launch Selenium Server using commands 
'npm install selenium-standalone -g'
'selenium-standalone install && selenium-standalone start'
4. Open Terminal in IDE and execute the case using below command
'npm test -- --executiontype=web --provider=local --browser=chrome --testSpec='./web/RocketSoftwareAssessment.ts' --allureResults='./allure-results''
