# Company Budget Allocation Application

A React-based web application for managing and tracking company department budget allocations.

## Features

- Set and modify total company budget
- View remaining budget and total expenses
- Track budget allocations across different departments:
  - Marketing
  - Finance
  - Sales
  - Human Resource
  - IT
- Increase/decrease department allocations
- Delete department allocations
- Real-time budget validation and alerts

## Technologies Used

- React 18.2.0
- Bootstrap 5.2.2
- React Icons 4.4.0
- Context API for state management

## Getting Started

### Prerequisites

- Node.js
- npm or yarn

### Installation

1. Clone the repository
```sh
git clone [repository-url]
```

2. Install NPM packages
```sh
npm install
```

3. Start the development server
```sh
npm start
```

The application will open in your default browser at `http://localhost:3000`

### Building for Production

To create a production build:
```sh
npm run build
```

## Usage

1. The initial budget is set to £2000
2. View current allocations in the table
3. Use the allocation form to:
   - Select a department
   - Choose to Add or Reduce budget
   - Enter the amount to modify
4. Click the '+' button to increase a department's budget by £10
5. Use the delete icon to remove a department's allocation

## Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.