# Front End Testing - Work in Progress 
When it comes to testing in JavaScript, I would say that there are two types of tests: unit tests and end to end tests, which are also referred to as integration tests or functional tests depending on who you talk to and what articles you read. 

## Unit Testing
   - Unit tests ensure that individual components of the app work as expected. Assertions test the component API.  (quality of ingredients using cooking analogy)
   - Realtime developer feedback


   ![Unit Testing Eg](https://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2016/04/1461566883dev-console-animated-small.gif)

### Tools

- **Jasmin**:  has almost everything built into it including assertions/expectations and test double utilities 
- **Mocha**:  a test runner, use in conjunction with below
   - **Chai** - for assertions etc
   - **Sinon** - for test doubles etc
   - **Karma** - a browser test runner
   - **Chutzpah* - a test runner
- **Tape** - 
- **Jest** - by  Facebook, built on top of Jasmine
    
#### Links 
- http://thejsguy.com/2015/01/12/jasmine-vs-mocha-chai-and-sinon.html
- http://stackoverflow.com/questions/26032124/karma-vs-testing-framework-jasmine-mocha-qunit
- https://medium.com/javascript-scene/why-i-use-tape-instead-of-mocha-so-should-you-6aa105d8eaf4#.csqt37otm
- **Proponent of Unit testing over functional** - http://martinfowler.com/bliki/TestPyramid.html


## Functional Testing / End to end testing
ensure that the app works as expected from the user’s perspective. Assertions primarily test the user interface.

###Tools
- **Selenium**
- **Watir**
- **Cucumber - Cucumber is a software tool that computer programmers use for testing other software. It runs automated acceptance tests written in a behavior-driven development (BDD) style
- **CasperJS / PhantomJS**
- **nightwatch.js**

####Links
- http://www.algoworks.com/blog/choosing-your-automated-testing-frameworks-phantomjscasperjs-vs-selenium/
- **Proponent of Functoinal Testing over Unit** https://www.helpscout.net/blog/functional-testing-casperjs/
- http://thejsguy.com/2015/02/28/end-to-end-testing-with-phantomsjs-and-casperjs.html


(food doesn't taste like crap using cooking analogy)

## Integration Testing
ensure that component collaborations work as expected. Assertions may test component API, UI, or side-effects (such as database I/O, logging, etc…)


## Other Tests


## CSS Regression Testing
### Tools
- **BackstopJS**

## Smoke Tests
It’s important to maintain a suite of automated functional tests that act like smoke tests for your newly deployed releases. Test all the critical functionality in your app: The stuff that most users will encounter in a typical session.


**General Intro** 
https://www.sitepoint.com/javascript-testing-unit-functional-integration/
http://www.slideshare.net/sethmcl/testing-web-apps-33612391

**Opinion on both types of tests** - http://stackoverflow.com/questions/11741738/frontend-testing-what-and-how-to-test-and-what-tool-to-use
http://martinfowler.com/bliki/TestPyramid.html

**misc**
https://www.toptal.com/react/how-react-components-make-ui-testing-easy

http://www.slideshare.net/sethmcl/testing-web-apps-33612391

