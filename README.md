# Travel Tracker

Travel Tracker is an application that lets users fill-in the countires that they have visited. Users can add new people and see each person's visited countires.

## Features

- **Itinerary Management**: Create, edit, and delete travel destinations.
- **Responsive Design**: Fill your and your frineds destinations and comapre them. Each user's destinations are filled with different color for easier comparison.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js with Express.js
- **Database**: PostgreSQL

## Getting Started

Follow these steps to set up and run the application locally:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/LyuboPetkov/Travel-Tracker.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd Travel-Tracker
   ```

3. **Install Dependencies:**
   ```bash
   npm install
   ```

4. **Set Up the Database:**
   - Ensure PostgreSQL is installed and running on your machine.
   - Create a new database named `travel_tracker`.
   - Execute the SQL commands in `queries.sql` to set up the necessary tables.

5. **Configure Environment Variables:**
   - Create a `.env` file in the root directory.
   - Add the following variables:
     ```
     DB_USER=your_database_username
     DB_PASSWORD=your_database_password
     DB_HOST=localhost
     DB_PORT=5432
     DB_NAME=travel_tracker
     ```

6. **Run the Application:**
   ```bash
   npm start
   ```

7. **Access via Web Browser:**
   Open your browser and go to `http://localhost:3000` to use the application.

## Project Structure

- `index.js`: Main application script
- `views/`: EJS templates for rendering web pages
- `public/styles/`: CSS stylesheets
- `queries.sql`: SQL queries for database setup

## Contributions

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
