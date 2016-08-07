# Front End Testing  

## Unit Testing
   - Unit tests ensure that individual components of the app work as expected. Assertions test the component API.  (quality of ingredients using cooking analogy)
   - Realtime developer feedback

### tools

- **Jasmin**:  has almost everything built into it including assertions/expectations and test double utilities 
- **Mocha**:  a test runner, use in conjunction with below
   - **Chai** - for assertions etc
   - **Sinon** - for test doubles etc
    
   #### Links 
   - http://thejsguy.com/2015/01/12/jasmine-vs-mocha-chai-and-sinon.html


## Functional Testing
ensure that the app works as expected from the user’s perspective. Assertions primarily test the user interface.

### Tools
- Selenium
- CasperJS

(food doesn't taste like crap using cooking analogy)

## Integration Testing
ensure that component collaborations work as expected. Assertions may test component API, UI, or side-effects (such as database I/O, logging, etc…)

-*Karma** - a brower test runner (http://stackoverflow.com/questions/26032124/karma-vs-testing-framework-jasmine-mocha-qunit)

https://www.sitepoint.com/javascript-testing-unit-functional-integration/
https://www.helpscout.net/blog/functional-testing-casperjs/
http://stackoverflow.com/questions/11741738/frontend-testing-what-and-how-to-test-and-what-tool-to-use
