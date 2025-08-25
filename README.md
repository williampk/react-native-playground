# My Monolithic App

This is a monolithic application structured with Yarn workspaces, containing a React Native demo package and a shared package for common functionalities.

## Project Structure

```
my-monolithic-app
├── packages
│   ├── react-native-demo       # React Native application
│   └── shared                   # Shared utilities and components
├── package.json                 # Root package configuration
├── yarn.lock                    # Dependency lock file
└── README.md                    # Project documentation
```

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd my-monolithic-app
   ```

2. **Install dependencies:**
   ```
   yarn install
   ```

3. **Run the React Native demo:**
   Navigate to the `react-native-demo` package and start the application:
   ```
   cd packages/react-native-demo
   yarn start
   ```

## Shared Package

The `shared` package contains common utilities and components that can be used across different packages in the monolithic application. You can add shared functionalities here to keep your code DRY.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.