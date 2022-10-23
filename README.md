# AiViReX DBase

## Steps to setup this Project and Basic Guidelines to be followed

- Download Android Studio
- Setup Git in your working system and generate SSH Key and PAT for your GitHub Account (refer [SSH Key Steps](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) and [PAT Steps](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token)
- Setup Git as Version Control System (VCS) in Android Studio and enter your SSH Key in Android Studio (refer Google or YouTube for this. It is pretty simple)
- Learn basic Git operations like push, pull, merge and learn how to create new branch and generate Pull Requests on GitHub
- Updates to Gradle Plugin should not be done without prior consent from the team as Gradle updates can break code sometimes due to deprecations
- The base project works with latest gradle and hence requires JDK 11. If you don't have JDK 11, install it in your system. Remember that Kotlin compiler too uses JVM
- Whenever you submit a Pull Request, keep checking for the Code Review comments and suggestions given by us
- If your Pull Request is rejected for some reason, make sure to correct your mistake and submit a new Pull Request
- All decisions regarding change in feature, updating dependencies, importing 3rd party libraries, etc. are to be taken with caution and prior consent from the team
- Don't edit this README file without the consent of the Team

## Basic Coding Practices to be followed

- Make sure to adhere to SOLID Principles always. Always have an abstract interface for any usecase or feature and implement the interface as concrete implementation
- Make sure to adhere to VIPER Architecture
- You should be able to defend your coding decisions and the code itself
- Avoid copying and pasting code from the Internet blindly without understanding the side effects of adding the code. Kindly understand the code before using it
- Always go for efficient algorithms. The aim should be to give a smooth experience to users
- Make sure that your code doesn't tamper the existing code. Don't give chance for code reviewers to reject your code
- For authentication and database related tasks, mock and test them in your own cloud/database during development before giving pull request
- Make the best use of common design patterns but avoid memory leaks
