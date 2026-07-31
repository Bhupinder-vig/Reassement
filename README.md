# Code Review 1 – Project Setup & Workflow

## 🚀 Project Setup & Workflow

This repository contains the initial setup for my Population Reporting System coursework project.

For Code Review 1, the main aim was to create a strong foundation for the project by setting up the development environment, version control workflow, and deployment tools. As this is an individual project, I have organised my work using Agile practices by splitting tasks into smaller sprints and tracking progress using project management tools.

The main tools and methods used for this project are:

| Tool/Method     | Purpose                                                                          |
| --------------- | -------------------------------------------------------------------------------- |
| IntelliJ IDEA   | Used as the main environment for developing and testing the Java application     |
| Maven           | Used to manage dependencies, build the project, and create the final JAR file    |
| Docker          | Used to create a consistent environment for running the application and database |
| GitHub Actions  | Used for automated building, testing, and Docker validation                      |
| GitFlow         | Used to manage different stages of development using branches                    |
| GitHub Projects | Used for tracking tasks, issues, and project progress                            |

---

# 📦 Build & Deployment

## Maven Build

The project uses Maven to manage the build process.

The application can be built using:

```bash
mvn clean install
```

This command:

* Downloads required dependencies
* Compiles the Java source code
* Runs the automated tests
* Generates the application JAR file

The completed JAR file is created inside the `/target` directory.

Example:

```
target/
└── PopulationReportingSystem.jar
```

---

## Docker Setup

Docker is used to make sure the application can run in the same environment regardless of where it is deployed.

The project contains:

* A Dockerfile for building the application image
* Docker Compose configuration for setting up required services

The Docker image can be created using:

```bash
docker build -t population-reporting-system .
```

The container setup has been tested locally to ensure the application can be built and run successfully.

---

## GitHub Actions CI/CD Pipeline

GitHub Actions is used to automatically check the project whenever changes are pushed to GitHub.

The workflow performs the following steps:

1. Builds the project using Maven
2. Runs automated tests
3. Creates the JAR file
4. Builds the Docker image

This helps identify any issues early and ensures that the project remains in a working state.

---

# 🔀 GitFlow Branching Strategy

This project follows the GitFlow workflow to keep development organised.

The main branches used are:

| Branch  | Purpose                                          |
| ------- | ------------------------------------------------ |
| master  | Contains the final stable version of the project |
| release | Used for final testing before the final version  |
| develop | Used for implementing and combining new features |

Development work is completed on the `develop` branch. Once features are complete and tested, changes are moved into the `release` branch before being merged into `master`.

---

# 📊 Project Management & Documentation

To organise the development process, the project uses:

* Product Backlog
* User Stories
* Kanban Board
* GitHub Issues
* Sprint Planning

Tasks are broken down into smaller pieces of work to make progress easier to track.

Documentation included in the project consists of:

* Use Case Diagram
* Use Case Descriptions
* Testing Documentation
* Code Review Information
* Project Reports

---

# 📈 Reflection

During the initial setup of the project, I gained experience with configuring a complete development workflow.

Some important lessons learned include:

* Maven provides a structured way to manage dependencies and automate builds.
* Docker makes the project easier to run consistently across different environments.
* GitHub Actions reduces manual testing by automatically checking changes.
* Using GitFlow helps keep development organised and separates unfinished work from the final version.

Setting up these tools at the beginning provides a reliable base for implementing the required population reporting features.

---

# 📄 License

This project is licensed under the APACHE 2.0 License.
