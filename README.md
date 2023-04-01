# Flutter clean architecture - Posts app 


This is a Flutter app built using Test-driven development and Clean Architecture. The app displays a list of posts fetched from an API, and allows the user to view the details of each post.

# Architecture
The app is built using Clean Architecture, which separates the app into layers based on the functionality they provide. The layers are as follows:

Presentation layer: The UI layer that displays the data and handles user input.
Domain layer: The business logic layer that defines the entities and use cases of the app.
Data layer: The layer that provides the implementation of the repositories and data sources.
This architecture allows for a clear separation of concerns, making the code more maintainable and testable.

# Test-driven development
The app is built using Test-driven development (TDD), which involves writing tests before writing the actual code. This ensures that the code is testable and that it meets the requirements set out in the tests. TDD helps to catch bugs early and ensures that the code is of high quality.

# Dependencies
The app uses the following dependencies:

cupertino_icons: ^1.0.2
dartz: ^0.10.1
equatable: ^2.0.5
flutter_bloc: ^8.0.1
get_it: ^7.2.0
http: ^0.13.4
internet_connection_checker: ^0.0.1+3
logger: ^1.2.2
shared_preferences: ^2.0.13
Running the app
To run the app, clone the repository and run flutter run in the terminal. Make sure you have Flutter installed on your system.

Running tests
To run the tests, run flutter test in the terminal. This will run all the tests in the project.

# Conclusion
This app is a great example of how Test-driven development and Clean Architecture can be used to build a high-quality Flutter app. The code is easy to maintain, test, and extend, making it a great choice for building production-ready apps.

# Architecture




![Clean Architecture](/images/clean-architecture-2.png)

![Posts App Screenshot](/images/clean-architecture.jpg)








