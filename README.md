# Tashtib

*Tashtib* is a project management tool specifically designed for civil engineers. It provides a comprehensive platform to manage construction projects, track progress, collaborate with teams, and ensure that all aspects of a project are efficiently handled.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Overview

Civil engineering projects require meticulous planning, coordination, and execution. Tashtib is built to cater to these needs, offering civil engineers a tool to manage their projects from inception to completion. Whether it's overseeing the construction of a building, managing a team of engineers, or ensuring that projects meet deadlines and budgets, Tashtib provides the tools necessary to achieve these goals.

## Features

- *Project Management*: Easily create, manage, and track construction projects.
- *Task Allocation*: Assign tasks to team members and monitor their completion.
- *Resource Management*: Manage resources, including materials, equipment, and manpower.
- *Documentation*: Keep all project documents, drawings, and reports organized and accessible.
- *Progress Tracking*: Visualize project progress with Gantt charts, timelines, and progress reports.
- *Collaboration*: Enable effective communication among team members with built-in messaging and file sharing.
- *Reporting*: Generate detailed reports on project status, resource usage, and budget tracking.

## Installation

To set up and run Tashtib on your local machine, follow these steps:

1. *Clone the repository*:
    
git clone https://github.com/ZahwaKhaled/Tashtib.git

2. *Navigate to the project directory*:
    
cd Tashtib

3. *Install the necessary dependencies*:
    
npm install
    *(or use yarn install if you prefer yarn)*

4. *Set up environment variables*:  
   Create a .env file in the root directory with the following variables:
    
REACT_APP_API_URL=<your_api_url>
REACT_APP_API_KEY=<your_api_key>
   Replace <your_api_url> and <your_api_key> with the actual values relevant to your setup.

5. *Run the application*:
    
npm start
    *(or use yarn start if you prefer yarn)*

6. *Access the application*:  
   Open your browser and go to http://localhost:3000.

## Usage

Once you have Tashtib running, you can start managing your civil engineering projects:

1. *Create a New Project*:  
   - Navigate to the "Projects" section.
   - Click on "Create Project."
   - Enter the project details, including name, location, and start/end dates.

2. *Manage Resources*:  
   - Allocate resources like materials, equipment, and workforce.
   - Track usage and ensure that resources are available when needed.

3. *Assign Tasks*:  
   - Divide the project into tasks.
   - Assign tasks to team members and set deadlines.

4. *Track Progress*:  
   - Use Gantt charts to visualize the timeline of the project.
   - Monitor the progress of each task and adjust plans as necessary.

5. *Collaborate with Your Team*:  
   - Use the built-in messaging system to communicate with your team.
   - Share documents, drawings, and reports directly within the platform.

6. *Generate Reports*:  
   - Create detailed reports on the project's progress, resource usage, and financials.
   - Use these reports to ensure the project stays on track and within budget.

## Project Structure

The project is organized as follows:

Tashtib/
├── public/
├── src/
│ ├── assets/
│ ├── components/
│ ├── pages/
│ ├── services/
│ ├── App.js
│ ├── index.js
│ └── ...
├── .env
├── package.json
└── README.md

- *public/*: Contains static files like images, HTML templates, and icons.
- *src/*: Contains the main source code for the application.
- *assets/*: Holds stylesheets, images, and other static assets.
- *components/*: Reusable React components.
- *pages/*: Pages of the application (e.g., Project Dashboard, Resource Management).
- *services/*: API services for interacting with the backend.

## Technologies Used

- *React.js*: For building the user interface.
- *Node.js & Express.js*: Backend server and API development.
- *MongoDB*: Database for storing project-related data.
- *Bootstrap*: Responsive design framework for a consistent look and feel.
- *JWT*: Authentication and authorization.
- *Axios*: HTTP client for API requests.

## Contributing

We encourage civil engineers, software developers, and project managers to contribute to Tashtib. Whether it's adding new features, improving existing ones, or fixing bugs, your contributions are welcome.

### How to Contribute

1. *Fork the repository*:
    - Click the "Fork" button at the top of the GitHub page.

2. *Create a new branch*:
    
git checkout -b feature-branch-name

3. *Make your changes* and commit them:
    
git commit -m "Detailed description of the changes"

4. *Push your changes*:
    
git push origin feature-branch-name

5. *Submit a pull request*:
    - Go to the original repository and open a pull request.


## Acknowledgements

This project was made possible thanks to the hard work and dedication of the following individuals:

- *Ahmed Samy*: [Describe Ahmed’s role or contributions]
- *Emad Mohamed*: [Describe Emad’s role or contributions]
- *Esraa Taha*: [Describe Esraa’s role or contributions]
- *Yasmin Emad*: [Describe Yasmin’s role or contributions]
- *Ramy Menassa*: [Describe Ramy’s role or contributions]

