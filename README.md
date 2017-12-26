# Certifier Project

This project generates a certificate. It runs on Vert.x, and is built on the Gradle build system.


## Features
* Students can generate certificates of completion for a variety of courses.
* Mentors can generate certificates for students from data in CSV files.


## Setting up the project

* ***Fork*** ![](https://camo.githubusercontent.com/ba881041f4d7c96895e8466eece0c43317919f56/68747470733a2f2f696d6167652e6962622e636f2f667953745a6d2f666f726b2e706e67) this git repository and ***clone*** the fork to a local directory or download [.zip](https://github.com/jboss-outreach/certifier/archive/master.zip) file.
* If you prefer using an IDE, install [Intellij IDEA](https://www.jetbrains.com/idea) or another preferred IDE that supports Java Code.


###### If using an IDE like Intellij IDEA, Eclipse or any that can run Java Code :
1. [Download JDK 8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) (JDK 8, as 9 won't work)
2. [Configure Intellij project defaults](https://www.jetbrains.com/help/idea/defining-a-jdk-and-a-mobile-sdk-in-intellij-idea.html), project structure, to set the project SDK to java version 1.8 
    ```configure --> Project Defaults --> Project Structure --> Select JDK 1.8 location```
3. Import the cloned repository into your IDE
4. After importing there should be a notification in the bottom right, asking you to link the project to gradle. Click on it and it will occur automatically.
5. Right click the **App** class
6. Right click on the vertx at the top of the code and use the suggested help from intellij to link it to the project
7. Click **Run App.main()**

### If using on terminal in Linux/Unix,
```sh
./gradlew run         # pwd should be project home dir
```
* If permission is denied then use ```chmod +x ./gradlew```
### If using on Command Prompt in Windows
```sh
gradlew run           # pwd should be project home dir & open cmd as admin
```
## Running the app
* Open http://localhost:4000 in your browser

## Help/Reference

If you are stuck anywhere or need any help, you can refer the following:

1. [Git Handbook](https://guides.github.com/introduction/git-handbook)
2. [Introduction](https://guides.github.com/introduction/flow)
3. [Chat](https://gitter.im/jboss-outreach/gci)
4. [Terminal Handbook](http://linuxcommand.org/)
5. [Command Prompt Handbook](http://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/)

## Contributing to the project

```Step 1: Fork this project.```: 
Go to the top right of the project page and click on "Fork". A clone of this repo will be created on your GitHub account.

```Step 2: Code your changes```: 
Create a new branch, and create/edit files as per your coding requirements. Ensure that your code is clean and efficient, and avoid redundancies. It is also advised to follow naming conventions as and where specified. Also make sure that your code is your own, and is not closed-source or stolen.

```Step 3: Commit and send a Pull Request (PR)```: 
Once you are done coding the changes, commit the files and create a PR. Click on "Compare across forks" when creating the PR, and select the master branch of this repo as the base. Set the head to your branch on your fork. Click on the button "Create Pull Request". Give your PR a meaningful title and a brief message explaining the purpose of your commits.

```Step 4: Ensuring code quality```: 
Once a PR has been created, check if it can be merged without any issues. If there are any issues, repeat from ```Step 2```. Wait for a reviewer to cross check your changes, and then merge your changes.

Keep contributing!
