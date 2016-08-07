# Front End Testing  

## Unit Testing
   - Unit tests ensure that individual components of the app work as expected. Assertions test the component API.  (quality of ingredients using cooking analogy)
   - Realtime developer feedback

### Tools

- **Jasmin**:  has almost everything built into it including assertions/expectations and test double utilities 
- **Mocha**:  a test runner, use in conjunction with below
   - **Chai** - for assertions etc
   - **Sinon** - for test doubles etc
   - **Karma** - a browser test runner 

    
   #### Links 
   - http://thejsguy.com/2015/01/12/jasmine-vs-mocha-chai-and-sinon.html
   - http://stackoverflow.com/questions/26032124/karma-vs-testing-framework-jasmine-mocha-qunit


## Functional Testing / End to end testing
ensure that the app works as expected from the user’s perspective. Assertions primarily test the user interface.

###Tools
- **Selenium**
- **CasperJS / PhantomJS**

   ####Links
   http://www.algoworks.com/blog/choosing-your-automated-testing-frameworks-phantomjscasperjs-vs-selenium/
   https://www.helpscout.net/blog/functional-testing-casperjs/


(food doesn't taste like crap using cooking analogy)

## Integration Testing
ensure that component collaborations work as expected. Assertions may test component API, UI, or side-effects (such as database I/O, logging, etc…)


https://www.sitepoint.com/javascript-testing-unit-functional-integration/
http://stackoverflow.com/questions/11741738/frontend-testing-what-and-how-to-test-and-what-tool-to-use
