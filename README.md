🌍 World MySQL Database



Welcome to the World MySQL Database! This dataset contains information about countries, cities, and languages from around the globe. Perfect for practicing SQL queries, learning database management, or just exploring world data! 🌎✨

📌 Features

🌆 Cities: Major cities with population and district details.

🏳️ Countries: Country-specific details like name, continent, and population.

🗣️ Languages: Spoken languages and their percentage in each country.

🔗 Relationships: Foreign keys linking country codes to cities and languages.

🚀 Getting Started

📥 Installation

Ensure you have MySQL installed.

Clone this repository:

git clone https://github.com/yashriful/world-mysql-db.git
cd world-mysql-db

Import the database:

mysql -u root -p < world.sql

🔎 Sample Queries

🌆 Get Top 10 Most Populated Cities:

SELECT Name, Population FROM city ORDER BY Population DESC LIMIT 10;

🏳️ List All Countries in Asia:

SELECT Name FROM country WHERE Continent = 'Asia';

🗣️ Find Most Spoken Languages:

SELECT Language, SUM(Percentage) as TotalPercentage FROM countrylanguage GROUP BY Language ORDER BY TotalPercentage DESC LIMIT 5;

📜 License

This project is open-source. Feel free to use and modify it!

🌍 Made with ❤️ for data enthusiasts!
