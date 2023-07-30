# News Portal React Website

This is a news portal website built using React that allows users to read news articles of their preferred categories. The website includes features such as a registration and login page, news categories, and an admin panel to manage posts. The user data and news articles are stored in a MySQL database. Additionally, the website supports image uploads for article thumbnails.

## Prerequisites

- Node.js and npm installed on your machine
- MySQL server and database setup

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/aakash-sharma-github/Code_Clause_NEWS_Portal.git
   ```
2. Navigate to the project directory:

   ```bash
   cd Code_Clause_NEWS_Portal
   ```
3. Install the project dependencies:

   ```bash
   npm install
   ```
4. Create a `.env` file in the root folder and populate it with the necessary environment variables, including database connection details:

   ```plaintext
   DB_HOST=localhost
   DB_USER=username
   DB_PASSWORD=password
   DB_DATABASE=news
   ```

## Database Setup

1. Create a MySQL database called `news`:

   ```sql
   CREATE DATABASE news;
   ```
2. Create the necessary tables:

   ```bash
   CREATE TABLE uesrs ();
   CREATE TABLE posts ();
   ```

## Usage

1. Run the React development server:

   ```bash
   npm start
   ```
2. Open your web browser and navigate to `http://localhost:3000` to access the News Portal website.
3. Register a new user account or use an existing account to log in.
4. Browse the different news categories, read articles, and submit comments on articles.
5. Access the admin panel by logging in as an admin user.
6. From the admin panel, you can create, edit, and delete news articles. You can also manage user accounts.

## Customization

- To customize the categories or article types, modify the data in the MySQL database table `categories`.
- To update the UI or add new features, modify the React components in the `src` directory.

## Contributing

Pull requests and contributions are always welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open source.
