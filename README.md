# Email Account App

This project allows users to create email accounts without requiring a phone number. It provides a seamless experience for users to register and verify their email accounts through verification codes sent to their email addresses.

## Features

- User registration without phone number verification.
- Email verification through unique verification codes.
- Simple and intuitive API for account management.

## Project Structure

```
email-account-app
├── src
│   ├── app.ts               # Entry point of the application
│   ├── controllers          # Contains controllers for handling requests
│   │   └── index.ts
│   ├── routes               # Defines application routes
│   │   └── index.ts
│   ├── services             # Business logic and services
│   │   └── emailService.ts
│   ├── models               # Data models
│   │   └── user.ts
│   └── types                # Type definitions
│       └── index.ts
├── package.json             # NPM package configuration
├── tsconfig.json            # TypeScript configuration
└── README.md                # Project documentation
```

## Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd email-account-app
   ```
3. Install the dependencies:
   ```
   npm install
   ```

## Usage

To start the application, run:
```
npm start
```

## API Endpoints

- `POST /create-account`: Create a new email account.
- `POST /verify-email`: Verify the email using the verification code.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.