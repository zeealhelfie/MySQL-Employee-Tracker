# Employee Tracker

Employee Tracker is a command-line application designed to streamline employee management within an organization. This intuitive tool allows users to view, add, and update employee details effortlessly. The application is built on Node.js and utilizes a MySQL database for storing and managing employee information.

![Employee Tracker Demo](./Assets/employee-tracker.gif)

## Key Features

- **View Employees:** Easily access a comprehensive list of all employees in the organization.
  
- **Filter by Department or Manager:** Organize and view employees based on departments or managers, enhancing data visibility.
  
- **Add New Employees:** Simplify the onboarding process by quickly adding new members to the team.
  
- **Remove Employees:** Maintain an up-to-date record by removing employees who have left the organization.
  
- **Update Roles and Managers:** Adapt to organizational changes by updating employee roles and managers as needed.

## Technologies Used

- **Node.js:** Powering the command-line interface and application logic.
  
- **MySQL:** Storing and managing the relational database for employee information.
  
- **Inquirer.js:** Facilitating interactive command-line prompts for a user-friendly experience.

## Getting Started

To get started, clone the repository, install the necessary dependencies, and set up the MySQL database using the provided schema and seed data. Follow the instructions in the [Getting Started](#getting-started) section of the README.

## Installation:

1- Clone the repository:
`git clone https://github.com/your-username/employee-tracker.git`

2- Navigate to the project directory:
`cd employee-tracker`

3- Install dependencies:
`npm install`

4- Set up the database by importing the schema and seed data:
`mysql -u your-username -p employees < schema.sql`
`mysql -u your-username -p employees < seed.sql`


## Usage

Run the application using the provided npm script, and follow the prompts to interact with the Employee Tracker.

`npm run start`

## Database Schema

The database schema includes the following tables:

* `department`
* `role`
* `employee`
For more details, refer to schema.sql.

![Database Schema](Assets/schema.png)

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1- Fork the project
2- Create your feature branch (`git checkout -b feature/your-feature`)
3- Commit your changes (`git commit -m 'Add some feature`)
4- Push to the branch (`git push origin feature/your-feature`)
5- Open a pull request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to [Inquirer.js](https://www.npmjs.com/package/inquirer) for providing a robust command-line user interface for Node.js.



