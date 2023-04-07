# Clean Architecture Cryptocurrency App
This repository contains a cryptocurrency app built using Clean Architecture principles and written in Jetpack Compose, a modern toolkit for building Android user interfaces. The app is an example of how to structure your code in a clean and maintainable way, and how to use Use Cases to separate business logic from presentation logic.

## Getting Started
To run the app, you need to have Android Studio installed on your computer. Once you have Android Studio installed, follow these steps to run the app on your device or emulator:

Clone the repository to your local machine using the following command:
git clone https://github.com/ArtemZolotukh1n/CryptocurrencyApp

Open Android Studio and select "Open an existing Android Studio project" from the welcome screen.

Navigate to the location where you cloned the repository and select the Clean-Architecture-Cryptocurrency-App folder.

Once the project is loaded, click on the "Run" button in the toolbar or press the Shift + F10 key combination to run the app on your device or emulator.

## Features
The app has the following features:

View a list of cryptocurrencies.
View detailed information about each cryptocurrency, volume, active or not e.t.c.
Dark mode support.
## Architecture
The app is built using the Clean Architecture pattern, which separates the code into different layers that have their own responsibilities. The layers are as follows:

Presentation: This layer is responsible for displaying the UI to the user. It uses Jetpack Compose to build the UI and follows the MVVM architecture pattern.
Domain: This layer contains the business logic of the app. It defines the Use Cases that perform the various operations needed by the app, such as getting the list of cryptocurrencies or searching for a specific cryptocurrency.
Data: This layer is responsible for fetching data from external sources, such as an API or a database. It uses Retrofit and Room to handle network and database operations, respectively.
Contributing
If you want to contribute to this project, feel free to fork the repository and submit a pull request with your changes. We welcome any contributions that improve the app or add new features.

## Acknowledgments
This project was inspired by the Clean Architecture principles and the videos of Philipp Lackner's YouTube channel.
We fixed an error in one of the videos by adding a missing provideGetCoinsUseCase method, so that the app can run properly.
The app was built using Jetpack Compose, a modern toolkit for building Android user interfaces.
