
# Quality Assurance in Mendix #

## Product Testing ##

### Process ###
* [8 lightweight quality assurance practices](https://www.mendix.com/blog/8-lightweight-quality-assurance-practices/) - One of the key success factors for effective quality assurance is the ability to embed quality-enhancing practices into your projects, without burdening your team with extensive additional workload.
* [Quality Assurance Mindset in Mendix](http://ww2.mendix.com/expert-webinar-quality-assurance.html) - View this free professional training session to learn more about adopting an effective Quality Assurance mindset in a Mendix context. Topics include:
 * Testing innovative Mendix applications
 * Multiple automated testing options
 * Selenium and TestNG

### Tooling ###
* [Application Test Suite (ATS)](http://www.mansystems.com/application-test-suite/) - The Application Test Suite is a test framework that is particularly focused on efficiency and speed, built on top of the solid and mature Selenium automation technology.
* [UnitTesting module](https://world.mendix.com/display/public/howto6/Testing+microflows+using+the+UnitTesting+module) - To smarten up your app with business logic you can use microflows. To verify that your microflow works as expected you can create unit tests using the UnitTesting module. The UnitTesting module provides an easy to use interface to manage and run unit tests. The module supports unit tests that are created using microflows and unit tests that are created using JUnit.
* [SoapUI](https://world.mendix.com/display/public/howto6/Testing+web+services+using+SoapUI) - You can publish your own webservices in a Mendix application. These webservices consist of operations. Other applications can then call operations of this webservice and you can return a result. This result is based on a microflow that will be executed when the webservice is called. With SoapUI you can create (automated) tests for these webservices.
* [Selenium IDE](https://world.mendix.com/display/public/howto6/Testing+Mendix+applications+using+Selenium+IDE) - Selenium IDE is a Firefox plugin which records and plays back user interactions with the browser.
* [TestNG](https://world.mendix.com/display/public/howto6/Creating+automated+tests+with+TestNG) - TestNG is a Java testing framework that can be used to drive Selenium. In this how-to you will learn how to create an automated test with TestNG.

## Model Quality Assessment ##

### Development Standards ###
* [Naming Conventions](https://world.mendix.com/display/public/bestpractices/Naming+conventions+in+Mendix+5) - This document can be used as a guideline for using proper naming for your application sources. This will help to improve your application's maintainability, and makes it easier to read and understand.
* [Error-handling](http://ww2.mendix.com/Expert-Webinar.Error-Handling.html) - Learn Mendix Error Handling Best Practices. Topics include:
 * The four error handling configurations and what they mean
 * Database transactions within microflows
 * Conflicting error handling techniques within microflows and sub-microflows
 * How to report errors to your users
 * How to efficiently log errors in your application
* [The Root Cause of Runtime Errors and Resolving the 2 Most Common Issues](https://www.mendix.com/blog/the-root-cause-of-runtime-errors-and-resolving-the-2-most-common-issues/) - There are many reasons for getting an error message and several message variations. This post will walk you through how to find the cause of these errors, how to fix some of the more common errors, and how to minimize the potential for errors while you’re developing.

### Tooling ###
* [Application Quality Monitor (AQM)](https://www.mendix.com/application-platform-as-a-service/mendix-application-quality-monitor/) - The Mendix Application Quality Monitor offers a dashboard providing instant insight on the quality of the application models you’re building. The industry-first cloud service leverages the groundbreaking metadata-based Model API, performing static analysis of application models by a best-of-breed engine from our partner SIG.

## Production Application Monitoring ##

### Process ###
* [App Performance](http://ww2.mendix.com/Expert-Webinar.Performance.html) - Learn Mendix application performance best practices. Topics include:
 * How to identify and improve performance problems
 * Common business logic performance errors
 * Domain model improvements
 * Retrieval best practices with XPath contraint
 * Security best practices
 * UI & Widget use best practices
* [3 Tips for a Performant User Interface](https://www.mendix.com/blog/3-tips-for-a-performant-user-interface/) - Three tips to ensure your User Interface remains as fast as possible.
* [Performance Optimization II](http://ww2.mendix.com/Expert-Webinar.Performance-Level-2.html) - This webinar will expand on the best practices reviewed in the other Expert Webinar on [App Performance](http://ww2.mendix.com/Expert-Webinar.Performance.html). Topics include:
 * What the Users experience and problems they see
 * Background information on how mendix works
 * How to analyze performance problems
 * Best tools to identify and diagnose performance problems
 * How to improve Server & Browser performance
* [The developers guide to performance](http://www.stukkie.nl/mendix/the-developers-guide-to-performance/) - End-users expect fast and engaging web experiences. Yet the application landscape is becoming more complex. Your Mendix application can meet these rising expectations and impress users on both desktop and mobile devices. Learn how to locate and analyse performance issues, improve application performance and gain insight in how design decisions impact your application. This post is a comprehensive reference guide for developers to optimize their applications.
* [Top 10 Performance Improvement Tips for Mendix](http://www.mansystems.com/top-10-performance-improvement-tips-for-mendix/) -  This blog is about Bart Tolen his top 10 performance improvement tips for Mendix. This blog is technical in nature and assumes knowledge of the Mendix modeler and some infrastructure knowledge, like what a database index does or how web server compression would help.

### Tooling ###
* [Application Performance Monitor](http://www.mansystems.com/application-performance-monitor/) - APM is the monitoring and management of performance and availability of software applications. APM strives to detect and diagnose application performance issues to maintain an expected level of service.
* [Feedback Widget: Bridging The Gap Between Developers And Business Users](https://www.mendix.com/blog/feedback-widget-bridging-the-gap-between-users/) -  By using the feedback widget, business users can request new features, and provide feedback on what they want and need. Furthermore, they can use it for QA and for reporting any issues that they see. The feedback widget automatically captures important context for the development team, including the browser, page, and user role. Additionally, users can upload screenshots, if needed.