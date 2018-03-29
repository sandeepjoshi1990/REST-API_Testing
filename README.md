# REST-API_Testing
https://smartbear.com/learn/api-testing/rest-testing-for-beginners/
What Is API Testing?


In order to discuss API and Web services testing, we need to first identify what is an API and how it works. An application programming interface, or API, works to connect an application to the web and to other APIs.

An application is made of three essential parts that ideally should be able to work and communicate in a segmented way, so one could be swapped out for another:

Data Tier: Where data is retrieved from the database and file system and then stored.
Logic Tier: The brain of the application, this processes the data between the layers, coordinating the application, processing commands, and making logical decisions. This layer is made of the API.
Presentation Tier: This top layer of the app is the user interface, which translates tasks into something the user understands.
In other words the API is the brain of our connected world. It is the set of tools, protocols, standards and code that glues our digital world together. APIs allow for companies to become more agile, for things to go mobile, and everything to work together in a streamlined, integrated way.

Therefore, API testing is testing that APIs and the integrations they enable work in the most optimal manner. This form of testing concentrates on using software to make API calls in order to receive an output before observing and logging the system’s response. Most importantly, this tests that the API returns a correct response or output under varying conditions. This output is typically one of these three:

A Pass or Fail status
Data or information
A call to another API
However there also could be no output at all or something completely unpredicted occurs. This makes the tester’s role crucial to the application development process.And because APIs are the central hub of data for many applications, data-driven testing for APIs can help increase test coverage and accuracy.

In testing the API directly, specifying pass/fail scenarios is slightly more challenging. However in comparing the API data in the response or in comparing the behavior after the API call in another API would help you setup definitive validation scenarios.



API testing is one of the most challenging parts of the whole chain of software testing and QA testing because it works to assure that our digital lives run in an increasingly seamless and efficient manner. While developers tend to test only the functionalities they are working on, testers are in charge of testing both individual functionalities and a series or chain of functionalities, discovering how they work together from end to end.

Why is API testing important?
All forms of software is essential to identify bugs and inconsistencies both when you are releasing a product and as you make sure it continues to work when it’s out in the wild. It’s very clear that the risk of putting a bad and especially insecure product on the market is greater than the cost to test it.

Here are just some of the examples of common security tests that your API could be vulnerable to:



The API is what gives the value to the application. It’s what makes our phones “smart” and it’s what streamlines business processes. If any API doesn’t work efficiently and effectively, it will never be adopted, regardless if it is a free and open API or one that you charge per call or group of calls. What’s worse, if an API breaks because errors weren’t detected, it could not only break a single application but a chain of business processes hinged to it.

What You Need to start API testing
The first part of API testing involves setting up a testing environment, with the required set of parameters around the API. This involves configuring the database and server for the application’s requirements. Once you’ve set up your API testing environment, make an API call right away to make sure nothing is broken before you go forward to start your more thorough testing.

You can start combining your application data with your API tests to ensure that the API performs as expected against possible known input configurations. See this REST Testing example for beginners to help with the visualization.



Next, you need to organize yourself around the API test. Start by asking yourself these questions:

Who is your target audience? Who is your API consumer?
What environment/s should the API typically be used?
What aspects are you testing?
What problems are we testing for?
What are your priorities to test?
What is supposed to happen in normal circumstances?
What could potentially happen in abnormal circumstances?
What is defined as a Pass or a Fail? What data is the desired output? What is the chain of events?
What other APIs could this API interact with?
Who on your team is in charge of testing what?
After you’ve created these testing boundaries and requirements, you need to decide what you want to test your API for. These are some of the common kinds of API testing:

Functionality testing — the API technically works.
Usability testing — the API is easy to work with.
Reliability testing — the API can be consistently connected to and lead to consistent results.
Load testing — the API can handle a large amount of calls.
Creativity testing — the API can handle being used in different ways.
Security testing — the API has defined security requirements including authentication, permissions and access controls. See some API security tips for protectiving vital data.
Proficiency testing — the API increases what developers are able to do.
API documentation testing — also called discovery testing, the API documentation easily guides the user.
Tests will surely vary but here are common API test examples:

Checking API return values based on the input condition.
Verifying if the API doesn’t return anything at all or the wrong results.
Verifying if the API triggers some other event or calls another API.
Verifying if the API is updating any data structures.
Start Testing Your APIs Now with SoapUI Pro START FREE TRIAL
Manual Testing vs. Automation Testing: What's right for your API?
What is API Automation Testing versus Manual Testing? API automation testing is when you use a tool, while API manual testing is writing your own code to test the API. API testing is one of the areas where automation testing is highly recommended, particularly in the world of DevOps, agile development and continuous delivery cycles.

Where can API testing can be automated?

API functional testing.
Creating loads of dynamic data to throw into your API testing.
Repeated test design.
Analyzing your functional test coverage to know what you're missing.
Ad-hoc testing.
Using the command-line to hook your tests to your build system.
Flipping between multiple environments quickly, including development, testing, and staging environments.
Testing protocols in a single, unified framework.
Using multiple data sets at the same time to cover different test scenarios.
As with all automation, speeding up the overall testing process.
Error testing, where you throw forced errors at the API to understand how it will react.
Testing in multiple languages.
Of course, automated API testing can be performed in many conditions, particularly when you are pressed for time, making it compelling when you are following continuous software development release cycles. API testing automation even allows you to test in tandem with development.

However, in certain situations, like where APIs are connecting the Internet of Things, it’s nearly impossible to perform only testing automation. It’s good to automate if the API calls are giving back the correct responses, but, at least for now, you still need a human to make sure that connected light really turned on. Surely the Internet of Things will lead us to greater levels of machine learning, but it’s highly unlikely that a machine or even a human could predict all use cases, all security risks, and all attempted integrations. That’s why the job of the tester could never be fully automated as manual testing will always play an important part.

Similarly, API usability testing should also continue be a manual testing priority, as you work to dogfood your API, making sure to create a better, simpler developer experience.

What are some API Testing best practices?
You’ve created your own API testing plan. Now it’s good to have a list of rules of thumb to follow in order to help make the test as successful as possible:

Test first for the typical or ordinary results, for what happens consistently and what doesn’t.
Add stress to the system through a series of API load tests. 
Test for failure. Keep working and working until you get a Fail output, making sure the API fails consistently and gracefully.
Group test cases by test category.
Parameters selection should be explicitly mentioned in the test case itself.
Prioritize API function calls so that it will be easy for testers to test in a timely fashion.
Limit the tests from as many variables as possible by keeping it as isolated as possible.
Automate API documentation creation with a standard like Swagger, but then run through the tests, making sure the documentation makes sense for all levels of user experience.
Throw anything you can at the API to test for how it handles unforeseen problems and loads.
Perform well-planned call sequencing.
Later on, get creative! For complete test coverage, create test cases for all possible API input combinations.
Automate whatever you can.
But trust your instincts if something seems off!
Are you ready to start API testing? What are you waiting for?
https://smartbear.com/learn/api-testing/what-is-api-testing/?utm_source=medium&utm_medium=blog#_ga=2.203261905.1342606900.1522306740-1074218591.1522306740

