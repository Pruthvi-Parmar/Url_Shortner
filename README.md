# SnapLink

SnapLink is a URL shortening service that transforms lengthy URLs into concise, shareable links. This project includes both frontend and backend components to ensure a seamless user experience.

## Features

- **URL Shortening**: Simplify long URLs into short, manageable links.
- **User-Friendly Interface**: Intuitive design for easy navigation and usage.
- **Backend API**: Robust backend to handle URL processing and storage.

## Project Structure

The repository is organized into the following main directories:

- **url-shortener-react**: Contains the React-based frontend application.
- **url-shortener-sb**: Houses the Spring Boot backend service.

## Prerequisites

- **Node.js**: Required to run the React application.
- **Java**: Necessary for running the Spring Boot backend.
- **Maven**: For building and managing Java project dependencies.

## Getting Started

### Frontend (React Application)

1. **Navigate to the React project directory**:
   ```bash
   cd url-shortener-react
   ```
2. **Install dependencies**:
   ```bash
   npm install
   ```
3. **Start the development server**:
   ```bash
   npm start
   ```
   The application will be accessible at `http://localhost:3000`.

### Backend (Spring Boot Application)

1. **Navigate to the Spring Boot project directory**:
   ```bash
   cd url-shortener-sb
   ```
2. **Build the project using Maven**:
   ```bash
   mvn clean install
   ```
3. **Run the application**:
   ```bash
   java -jar target/url-shortener-sb-0.0.1-SNAPSHOT.jar
   ```
   The backend service will run on `http://localhost:8080`.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

Special thanks to Sumit Mishra for his invaluable resources and support.
