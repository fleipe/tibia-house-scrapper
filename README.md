# Tibia House Scraper

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

This Python script utilizes Selenium to scrape information about rented houses in the popular online game Tibia. It allows users to specify a world and town, navigate to the Tibia website, and extract details about houses marked as "moving out" or any other relevant information.

## Features

- **Modular Structure:** The code is organized into functions, making it easy to understand and modify.
- **Web Scraping with Selenium:** Leverages Selenium for navigating web pages and extracting relevant data.
- **Configurable:** Users can input worlds and towns from external files to automate the process for multiple locations.

## Prerequisites

- Python 3.x
- Selenium
- Chrome WebDriver

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/tibia-house-scraper.git

2. Install dependencies:

   ```bash
   pip install -r requirements.txt

3. Download Chrome WebDriver and add it to your system's PATH.

## Usage
1. Create files named Towns and Worlds, each containing a list of towns and worlds, respectively.

2. Run the script:

   ```bash
   python tibia_house_scraper.py

### Feel free to contribute and open issues for any suggestions or improvements!
## WARNING: Do not push to Master Branch!!