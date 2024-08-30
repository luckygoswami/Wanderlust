# Wanderlust

Wanderlust is a dynamic web application designed to help users explore and share exciting travel destinations. Users can browse, review, and share their own experiences at different locations, creating a community-driven travel platform.

## Table of Contents

- [Screenshots](#screenshots)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [Contact](#contact)

## Screenshots

![Homepage](https://github.com/luckygoswami/assets/blob/main/Wanderlust/homepageView.png?raw=true)
![Login page](https://github.com/luckygoswami/assets/blob/main/Wanderlust/loginView.png?raw=true)
![create listing page](https://github.com/luckygoswami/assets/blob/main/Wanderlust/createView.png?raw=true)
![Lisitng details page](https://github.com/luckygoswami/assets/blob/main/Wanderlust/listingView.png?raw=true)

## Features

- **User Authentication**: Secure login and registration using Passport.js.
- **Listings**: Users can browse through various travel listings and share their own.
- **Reviews**: Leave reviews for different listings, rate them, and share feedback with other users.
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Flash Messages**: Display success and error messages for user actions.

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/luckygoswami/Wanderlust.git
   ```

2. Navigate to the project directory:

   ```
   cd Wanderlust
   ```

3. Install dependencies:

   ```
   npm install
   ```

4. Set up the `.env` file in the root directory:

   ```env
   ATLASDB_URL=<your database url>
   CLOUD_NAME=<your cloud name>
   CLOUD_API_KEY=<your cloud api key>
   CLOUD_API_SECRET=<your cloud api secret code>
   SECRET=<your secret key>
   ```

5. Start the MongoDB server:

   ```
   mongod
   ```

6. Run the server:

   ```
   npm .\app.js
   ```

7. Access the app by visiting `http://localhost:8080`.

## Usage

- **Listings**: Browse and add new travel listings by navigating to the Listings section.
- **Reviews**: View reviews for a listing or add your own review if you have visited the destination.
- **Authentication**: Log in to access user-specific features like adding new listings and leaving reviews.
- **Responsive Interface**: Enjoy a mobile-first design, ensuring a smooth experience on all devices.

## Technologies Used

- **Backend**: Node.js, Express, MongoDB
- **Frontend**: EJS, Bootstrap, CSS
- **Authentication**: Passport.js
- **Storage**: MongoDB with Mongoose
- **Session Management**: express-session, connect-mongo
- **Error Handling**: Custom error classes and flash messages

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m "Add some feature"`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a new Pull Request.

## Contact

If you have any questions or suggestions, feel free to open an issue on GitHub or contact me directly via [GitHub Issues](https://github.com/luckygoswami/Wanderlust/issues).
