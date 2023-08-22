# Spotify Clone App

This is a Spotify clone app built using PHP, MySQL, HTML, CSS, and JavaScript. The app allows users to browse and listen to albums that have been manually added to the database. Users can set up the code on their local systems and run it using the XAMPP server.

## Features

- Browse and listen to albums.
- Manually added albums stored in a MySQL database.
- User-friendly interface resembling the Spotify app.

## Getting Started

To get a copy of this project up and running on your local machine, follow these steps:

**Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/spotify-clone.git
   cd spotify-clone
   ```

## Set Up Your Environment:

1. Make sure you have XAMPP or a similar server environment installed.
2. Start the Apache and MySQL servers in XAMPP.

## Import the Database:

1. Open phpMyAdmin (usually accessible at [http://localhost/phpmyadmin](http://localhost/phpmyadmin)) and create a new database named `spotify_clone`.
2. Import the provided SQL file (e.g., `spotify_clone.sql`) into the database. This file contains the necessary tables and data for the app.

## Configure Database Connection:

1. Open the `config.php` file in the `includes` directory.
2. Modify the database connection settings according to your MySQL setup.

## Access the App:

Open a web browser and navigate to [http://localhost/spotify-clone](http://localhost/spotify-clone).

## Technologies Used
1. HTML
2. CSS
3. JavaScript
4. PHP
5. MySQL

## Contributing
Contributions are welcome! If you find a bug or want to add a new feature, please create an issue or submit a pull request.

## License
This project is licensed under the MIT License.
