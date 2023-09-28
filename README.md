# Weather Data Analysis Project

This Ruby project is designed to process weather data files and provide various data analysis and visualizations for different time intervals, including years, months, and days. The project includes several modules that handle different aspects of data analysis and visualization.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Modules](#modules)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [Author](#author)

## Features

- Analyze and visualize weather data for specific years, months, and days.
- Generate statistics such as highest and lowest temperatures.
- Create bar charts to represent temperature data.
- Process bonus weather data for additional analysis.

## Usage

To use this project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone <repository_url>


2. Navigate to the project directory:

    cd weather-data-analysis

3. Run the main project file with the appropriate command-line arguments:

    - ruby project.rb

To analyze weather data for a specific year:
  ruby project.rb -e <year> <data_directory_path>

To analyze weather data for a specific month:
  ruby project.rb -a <year> <month> <data_directory_path>

To analyze weather data for a specific day:
  ruby project.rb -c <year> <month> <day> <data_directory_path>

To analyze bonus weather data for a specific day:
  ruby project.rb -b <year> <month> <day> <data_directory_path>

View the generated statistics and visualizations in the console.

## Modules

The project includes the following modules:

- Year: Provides methods for analyzing and displaying weather data for a specific year.
- Month: Provides methods for analyzing and displaying weather data for a specific month.
- Day: Provides methods for analyzing and displaying weather data for a specific day.
- DayBonus: Provides methods for analyzing and displaying bonus weather data for a specific day.


## Installation

Before running the project, ensure that you have Ruby installed on your system. You can download Ruby from the official website: Ruby Downloads.

## Dependencies

This project has the following dependencies:
  - Ruby (version 3.1.2)


## Contributing

Contributions to this project are welcome. If you would like to contribute, please follow these steps:

## Fork the repository.

 - Create a new branch for your feature or bug fix.
 - Make your changes and test them thoroughly.
 - Submit a pull request with a clear description of your changes.

## Author

Talha Nasir

Feel free to modify this README template to include more specific details about your project, its usage, and any additional information you want to provide to users and contributors.