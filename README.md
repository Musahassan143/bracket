# 🎉 Bracket: A Self-Hosted Tournament System 🏆

Welcome to the **Bracket** repository! This project provides a robust and flexible self-hosted tournament management system. Whether you're organizing local sports events or large-scale competitions, Bracket simplifies the process of managing tournament brackets, schedules, and participant information.

[![Download Releases](https://img.shields.io/badge/Download%20Releases-Click%20Here-blue)](https://github.com/Musahassan143/bracket/releases)

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **User-Friendly Interface**: Designed with simplicity in mind, allowing users to easily navigate and manage tournaments.
- **Flexible Bracket Creation**: Supports various tournament formats including single elimination, double elimination, and round-robin.
- **Real-Time Updates**: Participants and organizers receive instant updates on match results and schedules.
- **Customizable Settings**: Adjust tournament settings to fit your needs, including match duration, scoring systems, and participant limits.
- **Multi-User Support**: Multiple users can access and manage the tournament simultaneously.
- **Statistics and Analytics**: Track player performance and tournament progress with built-in analytics tools.

## Technologies Used

Bracket is built using a combination of modern technologies:

- **Backend**: 
  - FastAPI: A fast web framework for building APIs with Python.
  - PostgreSQL: A powerful relational database for storing tournament data.
  
- **Frontend**: 
  - React: A JavaScript library for building user interfaces.
  - Mantine: A React component library for faster and easier web development.
  - Next.js: A React framework for server-rendered applications.

- **Containerization**: 
  - Docker: Used for creating, deploying, and running applications in containers.

- **Documentation**: 
  - Docusaurus: A tool for building documentation websites easily.

- **Package Management**: 
  - Yarn: A package manager for JavaScript.

## Getting Started

To get started with Bracket, follow these steps:

### Prerequisites

Make sure you have the following installed:

- Docker
- Node.js
- Yarn
- Python 3.8 or higher
- PostgreSQL

### Installation

1. **Clone the Repository**

   Use the following command to clone the repository:

   ```bash
   git clone https://github.com/Musahassan143/bracket.git
   cd bracket
   ```

2. **Set Up Environment Variables**

   Create a `.env` file in the root directory and set the necessary environment variables. You can find an example in `.env.example`.

3. **Build and Run the Application**

   Use Docker to build and run the application:

   ```bash
   docker-compose up --build
   ```

4. **Access the Application**

   Open your web browser and navigate to `http://localhost:3000` to access the Bracket interface.

### Running Migrations

To set up the database, run the following command:

```bash
docker-compose exec web alembic upgrade head
```

## Usage

After setting up the application, you can start creating tournaments. Here’s how:

1. **Create a Tournament**: Navigate to the "Tournaments" section and click on "Create Tournament." Fill in the necessary details such as name, format, and participant limit.

2. **Add Participants**: Once the tournament is created, you can add participants either manually or by importing a list.

3. **Manage Matches**: As matches are played, update the results in real-time. The bracket will update automatically.

4. **View Statistics**: Check the statistics section for insights on player performance and tournament progress.

## API Documentation

Bracket provides a RESTful API for developers. You can access the API documentation [here](https://github.com/Musahassan143/bracket/releases). This will guide you through the available endpoints, request formats, and response structures.

## Contributing

We welcome contributions! If you want to contribute to Bracket, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature/YourFeature`).
6. Open a pull request.

Please ensure your code adheres to our coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or feedback, feel free to reach out:

- **Email**: your-email@example.com
- **GitHub**: [Musahassan143](https://github.com/Musahassan143)

Thank you for checking out Bracket! We hope it helps you manage your tournaments effectively. 

For the latest releases, visit [here](https://github.com/Musahassan143/bracket/releases) to download the latest version and execute it for your needs.