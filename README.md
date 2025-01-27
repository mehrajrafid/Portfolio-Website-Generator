# Portfolio Website Generator

A customizable command-line interface (CLI) tool to create a personalized portfolio website. This tool allows users to dynamically customize their portfolio's theme, add skills, projects, and social links, as well as upload images like logos and banners for a professional presentation.

## Features

- **Dynamic Customization**: Input your name, bio, theme color, and more to create a personalized portfolio.
- **Skills Section**: Add skills with optional icons for each.
- **Projects Section**: Include projects with a title, description, and a link to showcase your work.
- **Banner Slider**: Add an image with a personalized message for the portfolio banner.
- **Logo Support**: Upload a logo to represent your brand or identity.
- **Footer Links**: Add social links with icons to connect with your audience.

## How It Works

1. Run the Python script from the command line.
2. The CLI will prompt you for inputs to customize your portfolio:
   - Name
   - Bio
   - Theme color
   - Logo and slider images
   - Skills and icons
   - Projects and descriptions
   - Footer social links
3. The tool generates an HTML file with your customized portfolio in a folder named `portfolio`.

## Prerequisites

- Python 3.6 or later.
- A basic understanding of file paths for image upload.

## Installation

1. Clone this repository:
   bash
   git clone <repository-url>
   cd portfolio-generator

2. Install required libraries (if any):

   pip install -r requirements.txt
(No external libraries are required for this tool.)
3. Run the script:
python portfolio_generator.py
# Usage
1. Run the script and follow the prompts to:

Enter personal details like your name and bio.
Select a theme color (default provided).
Add a logo image path.
Enter skills, projects, and contact information.
Add optional footer links.
2. After completing all inputs, the script will generate the HTML file in the portfolio directory.

3. Open the index.html file in any web browser to view your portfolio.

# Example Output
Header with a logo and bio.
Banner slider with an image and custom message.
Skills list with optional icons.
Projects section with clickable links.
Footer links with social media icons.

# Future Improvements
Add image preview support in the CLI.
Include additional styling options like font selection.
Support for multiple pages (e.g., About Me, Resume).

# Contributing
Contributions are welcome! Please fork the repository and create a pull request with your enhancements.

# License
This project is licensed under the MIT License.
