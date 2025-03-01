# Yum Finder

## Description

Yum Finder is a web application designed to help users discover and locate restaurants based on their preferences. Users can search for restaurants, view details, and get recommendations tailored to their tastes.

## Features

- Restaurant Search: Find restaurants based on location, cuisine, and other filters.
- Detailed Views: Access comprehensive information about each restaurant, including menus, reviews, and ratings.
- User Recommendations: Receive personalized restaurant suggestions based on user preferences and past interactions.

## File Structure

```
yum-finder/
├── frontend/
│   ├── public/
│   │   └── index.html
│   └── src/
│       ├── components/
│       │   └── [ComponentFiles].jsx
│       ├── App.js
│       └── index.js
├── src/
│   ├── controllers/
│   │   └── [ControllerFiles].js
│   ├── models/
│   │   └── [ModelFiles].js
│   ├── routes/
│   │   └── [RouteFiles].js
│   └── index.js
├── Procfile
├── package.json
└── README.md
```

- **frontend/**: Contains the client-side code of the application.
  - **public/**: Holds static files and the main HTML file.
  - **src/**: Includes React components and entry points.
    - **components/**: Reusable UI components.
    - `App.js`: Main React component.
    - `index.js`: Entry point for the React application.
- **src/**: Server-side code of the application.
  - **controllers/**: Handles the logic for different routes.
  - **models/**: Defines data schemas and interacts with the database.
  - **routes/**: Defines API endpoints and associates them with controllers.
  - `index.js`: Entry point for the server application.
- `Procfile`: Specifies commands that are executed by the app on startup, primarily for deployment on platforms like Heroku.
- `package.json`: Lists dependencies and scripts for the Node.js application.
- `README.md`: Provides information about the project.

## Technologies Used

- **Frontend**: React, HTML, CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/shivam200413/yum-finder.git
   cd yum-finder
   ```

2. **Install server dependencies:**

   ```bash
   npm install
   ```

3. **Navigate to the frontend directory and install dependencies:**

   ```bash
   cd frontend
   npm install
   ```

4. **Set up environment variables:**

   Create a `.env` file in the root directory and add the necessary environment variables (e.g., database connection strings, API keys).

5. **Run the application:**

   - **Backend:**

     In the root directory:

     ```bash
     npm start
     ```

   - **Frontend:**

     In the `frontend` directory:

     ```bash
     npm start
     ```

6. **Access the application:**

   Open your browser and navigate to `http://localhost:3000` to view the frontend. The backend API runs on `http://localhost:5000`.

## Usage

- **Search Restaurants:** Use the search bar to find restaurants based on your criteria.
- **View Details:** Click on a restaurant to see detailed information, including menus and reviews.
- **Get Recommendations:** Visit the recommendations section to receive personalized suggestions.

## Contributing

We welcome contributions! Please follow these steps:

1. **Fork the repository.**
2. **Create a new branch:**

   ```bash
   git checkout -b feature/YourFeatureName
   ```

3. **Make your changes and commit them:**

   ```bash
   git commit -m 'Add some feature'
   ```

4. **Push to the branch:**

   ```bash
   git push origin feature/YourFeatureName
   ```

5. **Open a pull request.**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
