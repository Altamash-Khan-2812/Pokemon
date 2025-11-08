# Pokemon Finder

Welcome to Pokemon Finder, an interactive web app built using React that allows you to search for Pokémon, view detailed information like their abilities, stats, types, and more! Powered by the official Pokémon API, this app pulls data dynamically, so you can browse through various Pokémon and their stats seamlessly.

## Demo

You can see the live demo <a href="https://pokemon-kappa-lac.vercel.app/">Here</a>

## Features

- Search Pokémon: Quickly search for any Pokémon by name using the search bar.
- Detailed Info: View detailed information about each Pokémon including height, weight, abilities, stats, and types.
- Responsive Design: The app is mobile-friendly and adapts to all screen sizes.
- Fetching Data: The app fetches data from the official Pokémon API and presents it in a neat and organized way.
- User-Friendly Interface: A clean and attractive interface with easy navigation.

## Technologies Used

- **React**: For building the interactive UI.
- **JavaScript (ES6+)**: For functionality and handling state and side effects.
- **CSS**: For styling and creating a responsive design.
- **Pokémon API**: To fetch detailed data about Pokémon.

## How It Works

- **Fetching Data**: The app makes an API request to the Pokémon API to fetch the list of Pokémon (100 Pokémon by default). It then fetches detailed information for each Pokémon, like stats, abilities, and images.

- **Search Functionality**: A search bar allows users to filter the Pokémon based on the name. The search is case-insensitive.

- **Display**: Each Pokémon is displayed in a card with details such as its type, abilities, stats, height, weight, and base experience. The data is fetched asynchronously to ensure the app remains responsive.

- **Error Handling**: If there's an issue with the API request or data fetching, the app displays an error message to the user.

## Installation & Setup

Follow these steps to run the project locally:

1. **Clone the repository**

   ```bash
   git clone https://github.com/Altamash-khn/Pokemon.git
   ```

2. **Navigate to the project folder**

   ```bash
   cd Pokemon
   ```

3. **Install dependencies**

   ```bash
   npm install
   ```

4. **Start the development server**

   ```bash
   npm run dev
   ```

5. **Open the app in your browser**
   ```
   http://localhost:5173
   ```
