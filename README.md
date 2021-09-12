# webpage-automation-testing-project
Building Automation testing on a Reactjs website

This project involves a reactjs website implemented in AWS cloud (Free Tier). Git push would trigger automated builds into AWS/Netlify.

As an alternative, this can be implemented on Netlify (Free tier) if we dont need a database connectivity

https://www.netlify.com/pricing/ and https://bejamas.io/compare/netlify-vs-aws-amplify/

For the Python Selenium piece, the project would be hosted in AWS.

<h2>Reactjs project specifications:</h2>

Based on https://github.com/alexgurr/react-coding-challenges/tree/master/chatter


<h2>Requirements 📖</h2>
Most of the work needs to be done in the Messages components.

Implement hooks such as useEffect and useCallback to handle events
Scroll to the bottom of the messages list when sending/receiving a message
Show the initial Botty message by default (can be found in common/constants)
Use sockets to:
Send the user's message to Botty
Show a typing message when Botty is typing
Handle incoming Botty messages and display them


<h2>Python Selenium automation testing project specifications:</h2>

To test the chatter app using automated python scripts. 
Infastructure on AWS using 
option 1
https://aws.amazon.com/blogs/devops/integrating-aws-device-farm-with-ci-cd-pipeline-to-run-cross-browser-selenium-tests/
or
option 2
https://aws.amazon.com/blogs/devops/serverless-ui-testing-using-selenium-aws-lambda-aws-fargate-and-aws-developer-tools/
