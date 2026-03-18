# OOD-Project

## Project Overview
This project is a structured, menu-driven console application designed to manage products and reusable materials while calculating their environmental impact. The goal is to promote sustainable consumption and production patterns by providing clear recycling guidance and impact transparency.

The system is built using **Object-Oriented Design (OOD)** principles, featuring a layered architecture and a Strategy Pattern for interchangeable impact calculation logic.

---

## Team Roles
- **[Pavlos Antoniou]**: TODO 
- **[Layth Al Mardini]**: TODO
- **[Rabie Al Khoja]**: TODO


---

## Requirements Analysis

### Functional Requirements
- **Product Management**: Create products with name, category, estimated lifespan, and one or more materials  
- **Material Management**: Define reusable materials with environmental impact values and recycling instructions  
- **Product Listing**: List all registered products and view detailed product information  
- **Impact Calculation**: Calculate total environmental impact using at least two interchangeable strategies (Strategy Pattern)  
- **Recycling Guidance**: Provide instructions for disposal based on material composition, including mixed-material handling  

### Non-Functional Requirements
- **Layered Architecture**: Implementation of Presentation (Console UI), Application (Use Cases/Services), and Domain (Core Logic) layers  
- **Logic Separation**: Input/output must be strictly separated from business logic  
- **Testability**: Core domain logic must be verified using JUnit tests with no console/UI code in tests  
- **Continuous Integration**: A CI pipeline must build the project and run all tests automatically  
- **Design Standards**: Adherence to SOLID principles, specifically SRP, OCP, and DIP  

---

## Professional Git Workflow
To maintain high code quality and project stability, the following workflow is used:

- **Main Branch Protection**: The `main` branch is protected; no direct commits are allowed  
- **Branching Strategy**: All development is performed on dedicated feature branches  
- **Merge Requirements**: Code is merged via Pull Requests only after the CI build passes and tests are successful  
- **Commit Quality**: Commits must be meaningful and clearly reflect the changes made  