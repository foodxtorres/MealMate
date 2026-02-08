# MealMate

[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

## Overview

MealMate is an intelligent meal planning application designed to help users create personalized weekly meal plans and generate optimized grocery lists based on dietary preferences and restrictions. Powered by AI, MealMate simplifies meal prep and reduces food waste.

## Features

- AI-powered weekly meal plan generation
- Customizable dietary preferences and allergy filters
- Automatic grocery list creation
- Recipe suggestions with step-by-step instructions
- Save and share meal plans

## Tech Stack

- Frontend: React.js
- Backend: Node.js, Express
- Database: MongoDB
- AI Integration: OpenAI GPT-4 API

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/foodxtorres/MealMate.git
   ```

2. Navigate into the project directory:

   ```bash
   cd MealMate
   ```

3. Install dependencies for backend and frontend:

   ```bash
   cd backend && npm install
   cd ../frontend && npm install
   ```

4. Create a `.env` file in the `backend` folder and add your API keys:

   ```env
   OPENAI_API_KEY=your_openai_api_key_here
   MONGODB_URI=your_mongodb_connection_string
   ```

5. Start the backend server:

   ```bash
   cd backend && npm start
   ```

6. Start the frontend development server:

   ```bash
   cd ../frontend && npm start
   ```

7. Open your browser and visit `http://localhost:3000`

## Usage

- Sign up or log in to your MealMate account.
- Set your dietary preferences and any allergies.
- Generate a weekly meal plan with one click.
- Review and customize your meals.
- Download or print the automatically generated grocery list.
- Save your meal plans for future use.

## Screenshots

![MealMate Dashboard Placeholder](https://via.placeholder.com/800x400?text=MealMate+Dashboard)

![Grocery List Placeholder](https://via.placeholder.com/800x400?text=Grocery+List)

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Make your changes and commit: `git commit -m 'Add some feature'
4. Push to your branch: `git push origin feature/your-feature-name`
5. Open a pull request.

Please ensure your code adheres to the existing style and includes tests where applicable.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

© 2024 [foodxtorres](https://github.com/foodxtorres)
