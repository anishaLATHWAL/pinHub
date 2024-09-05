# PinHub

PinHub is a web application similar to Pinterest, where users can upload and view pins shared by others. It's built using Express.js with EJS as the view engine.

## Flow of the App

- `/login`: Login page for users.
- `/register`: Registration page for new users.
- `/profile`: User profile page displaying their boards.
- `/feed`: Feed page displaying different pins from the community.
- `/save/:pinid`: Endpoint to save a pin to a user's board.
- `/delete/:pinid`: Endpoint to delete a pin.
- `/logout`: Logout functionality.
- `/edit`: Edit user profile.
- `/upload`: Upload pins.

## Installation

1. Clone the repository:

```bash
git clone <repository_url>
```

2. Install dependencies:

```bash
npm install
```

3. Install required packages:

```bash
npm install passport express-session mongoose passport-local multer
```

4. Start the server:

```bash
npm start
```

5. Visit `http://localhost:3000` in your browser to access PinHub.

## Technologies Used

- Express.js
- EJS (Embedded JavaScript) for templating
- Node.js
- Passport.js for authentication
- Express Session for session management
- Mongoose for MongoDB object modeling
- Multer for handling file uploads

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).