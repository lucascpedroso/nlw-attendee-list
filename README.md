# Attendee List Application

This application is designed to display the attendees registered for an event. It allows users to search for attendees and view details such as ID number, full name, email, registration date, and check-in status. The application retrieves attendee details from an API and is built using Vite, React, Tailwind CSS, Day.js, and TypeScript.

## Features

- Display a list of attendees registered for an event.
- Search functionality to find attendees by name or other criteria.
- Show details for each attendee including ID, name, email, registration date, and check-in status.
- Navigate through pages of attendees with pagination controls.
- Ability to check attendees in.

## Technologies Used

- **Vite**: Fast, opinionated web dev build tool that serves your code via native ES modules.
- **React**: A JavaScript library for building user interfaces.
- **TypeScript**: A superset of JavaScript that adds static types to the language.
- **Tailwind CSS**: A utility-first CSS framework for rapidly building custom designs.
- **Day.js**: A minimalist JavaScript library that parses, validates, manipulates, and displays dates and times.

## Component Overview

- Utilizes React state hooks to manage search query, pagination, and attendee data.
- Fetches attendee data from the API using `fetch` and updates state accordingly.
- Displays a table of attendees with columns for ID, name, email, registration date, and check-in status.
- Implements pagination controls to navigate through multiple pages of attendees.
- Provides search functionality to filter attendees by name.

## Usage

1. Clone the repository:
   git clone https://github.com/lucascpedroso/nlw-attendee-list

2. Install dependencies:
    npm install

3.  Run the application in development mode:
    npm run dev

## How to Contribute

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Submit a pull request to the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
