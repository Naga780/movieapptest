
1. Project Overview (Introduction)


“In this project, I tested a Movie Streaming App similar to Netflix. My goal was to ensure the app’s core functionalities like user registration, login, searching for movies, adding them to a watchlist, and movie playback worked smoothly. I used both manual and automated testing techniques to cover different aspects of the app.”



---

2. Manual Testing


“For manual testing, I first identified the key features and created test scenarios, such as user registration, login, movie search, adding movies to the watchlist, and playback. I created detailed test cases to validate these scenarios, such as testing user login with valid and invalid credentials, checking movie search results, and ensuring that users could manage their watchlists.”

“Each test case had clear steps and expected results, ensuring the app functioned as intended for different types of users.”


“For login, I manually tested both valid and invalid login attempts to ensure proper redirection or error handling. For movie playback, I tested whether the player responded to various actions like play, pause, and checking the quality adjustment under different network conditions.”



---

3. Automation Testing Approach


“After completing manual testing, I automated the core functionalities using Java, Selenium WebDriver, and TestNG, with a POM (Page Object Model) design to improve code reusability and maintainability. This helped me run regression tests efficiently whenever there were updates or changes in the application.”


Tools & Technologies:

Page Object Model (POM):

“For automation, I followed the Page Object Model (POM) design pattern. I created separate classes for each page, such as LoginPage, MoviePage, and WatchlistPage. Each page class contained the web elements and methods needed to interact with the UI elements. This made my tests more modular, reusable, and easy to maintain.”

“For example, in the LoginPage.java, I defined methods to enter the username, password, and click the login button. These methods were then used in my test cases to simulate the user’s login behavior.”


TestNG:

“I used TestNG as my test framework for structuring and executing test cases. This allowed me to organize my tests, run test suites, and implement assertions to validate the expected outcomes.”

“For example, in my login test, I used TestNG to verify if the user was successfully redirected to the homepage after logging in with valid credentials.”


Maven:

“I used Maven as the build tool to manage dependencies like Selenium, TestNG, and Cucumber. It also helped in running the tests from the command line, generating reports, and ensuring a smooth integration with CI/CD pipelines.”




---
4. Execution and Results

“Once the automation suite was ready, I executed the tests using Maven. The automated tests ran on different browsers to ensure cross-browser compatibility, and I used TestNG to generate detailed test reports that showed the test execution status. This ensured that any defects were caught early, and new features didn’t break the existing functionality.”

“Using automated tests for regression allowed us to quickly validate the app after every new feature or bug fix. Additionally, the modular structure made it easy to extend or update tests when new pages or functionalities were added.”


