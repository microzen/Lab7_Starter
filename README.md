# Lab 7
Yezhi Wu.

---

### Check your understanding
1). Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.  
A: Within a GitHub Action that runs whenever code is pushed. While local testing is important and a must-have skill for developers, CI is the reliable tool for a stable environment in a development pipeline. It provides a great safety net for collaboration.

2). Would you use an end to end test to check if a function is returning the correct output?  
A: Yes

3). What is the difference between navigation and snapshot mode?  
A: **Navigation Mode**: This is the status while the test is running, for example, clicking a button and submitting a form. 
**Snapshot Mode**: This is used to check static files after the test is completed. 

4). Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results.
1. Correct url for `img` element.
2. Include `lang` into <html>
3. Minifying JavaScript files and reduce unused JavaScript.