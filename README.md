# AutomationTests

Variable values can be replaced as per desirable. Variables are declared at the start of the script.

Sahi tests are stored under the path:
sahi_pro\userdata\scripts\

To run Sahi tests:
1. Launch SahiPro application
2. Open cmd on your desktop
3. Navigate to path : sahi_pro\userdata\bin
4. Run below command: testrunner.bat testname.sah startUrl browser
  
  Example:
  testrunner.bat LoginTest.sah http://jt-dev.azurewebsites.net/#/SignUp chrome
