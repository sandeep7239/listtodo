# listtodo

# Todo List Web Application

This repository contains the source code for a simple todo list web application built using the Express.js framework. The application follows the Model-View-Controller (MVC) architecture and allows users to manage their tasks effectively.

## Features

- Add new tasks to the todo list or work list.
- View the current date and tasks for the day on the homepage.
- Separate work list for managing work-related tasks.
- Static files (CSS, images) served from the "public" directory.
- About page providing information about the application.

## Technologies Used

- Node.js
- Express.js
- EJS (Embedded JavaScript) as the templating engine
- body-parser for handling URL-encoded data

## Getting Started

To run the application locally, follow these steps:

1. Clone the repository: `git clone https://github.com/sandeep7239/todo-list.git`
2. Navigate to the project directory: `cd todo-list`
3. Install the dependencies: `npm install`
4. Start the server: `node app.js`
5. Open your browser and visit `http://localhost:3000`

## File Structure

- `app.js`: The main server-side JavaScript file that sets up the Express application, defines routes, and starts the server.
- `views/`: Directory containing EJS templates for rendering views.
  - `list.ejs`: Template for rendering the todo list view.
  - `about.ejs`: Template for rendering the about page.
- `public/`: Directory containing static files such as CSS stylesheets and images.
- `date.js`: Module providing date-related functions.
- `README.md`: Documentation file providing an overview of the application and instructions for running it.

## Contributing

Contributions to the project are welcome. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and modify the code as per the terms of the license.

## Acknowledgements

- This project was inspired by various todo list applications and tutorials available online.
- Special thanks to the contributors and maintainers of the dependencies used in this project.

