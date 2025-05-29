# QuickQ

**QuickQ** is a web application that helps users prepare for interviews by generating tailored interview questions based on the user's selected career position.

## Project Overview

- **Front-end:** Built with ReactJS, providing a modern, user-friendly, and responsive interface.
- **Back-end:** Powered by ASP.NET Core API, responsible for business logic, data management, and serving APIs for the front-end. The back-end also utilizes Google AI Studio to generate interview questions dynamically based on user input and job position.

## Features

- Allows users to select the desired job position or industry for their interview preparation.
- Automatically generates a set of interview questions relevant to the chosen position.
- Stores the history of generated questions for users to review and practice.
- Supports users in practicing and improving their interview skills effectively.

## System Architecture

- **Front-end (ReactJS):**
  - Repository: [QuickQ Front-end](https://dev.azure.com/tienhqde180656/QuickQ)
  - Communicates with the back-end via RESTful APIs.
  - Designed for easy customization and extensibility.

- **Back-end (ASP.NET Core API & Google AI Studio):**
  - Repository: [QuickQ Back-end](https://dev.azure.com/tienhqde180656/QuickQ_BE)
  - Manages user data, questions, and career positions.
  - Handles question generation logic and other business processes.
  - Integrates with Google AI Studio to automatically generate relevant interview questions tailored to the user's selected job position and requirements.

## Installation Guide

### 1. Back-end (ASP.NET Core API)

1. Clone the repository:
    ```
    git clone https://dev.azure.com/tienhqde180656/QuickQ_BE
    ```
2. Configure your database connection string in `appsettings.json`.
3. Set up Google AI Studio API credentials as required for question generation features.
4. Build and run the project:
    ```
    dotnet build
    dotnet run
    ```

### 2. Front-end (ReactJS)

1. Clone the repository:
    ```
    git clone https://dev.azure.com/tienhqde180656/QuickQ
    ```
2. Install the required packages:
    ```
    npm install
    ```
3. Update the configuration file to set the API endpoint of the back-end.
4. Start the application:
    ```
    npm start
    ```

## How It Works

1. Users visit the QuickQ website and choose the job position or field for which they want to prepare.
2. The system generates a relevant set of interview questions using Google AI Studio and a curated database with smart selection logic.
3. Users can practice with these questions, review their answers, and improve over time.
4. The question history allows users to revisit previous sessions and track their progress.

## Contribution & Development

- All contributions are welcome! Please open an issue or submit a pull request for new features or bug reports.

## Contact

- For questions or support, please contact via email or open an issue on the repository.

---

**QuickQ** – Your trusted companion for confident interview preparation!
