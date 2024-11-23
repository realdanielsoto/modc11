# SVG Logo Maker

## Description

The **SVG Logo Maker** is a command-line application that allows users to quickly generate simple SVG logos for their projects. This tool prompts the user to specify text, a text color, a shape, and a shape color, and then generates an SVG file (`logo.svg`) based on the inputs. This ensures users can create custom logos without needing advanced graphic design skills.

## User Story

As a freelance web developer,  
I WANT to generate a simple logo for my projects,  
SO THAT I don't have to pay a graphic designer.

## Acceptance Criteria

- **GIVEN** a command-line application that accepts user input:  
  - **WHEN** I am prompted for text,  
    - **THEN** I can enter up to three characters.  
  - **WHEN** I am prompted for the text color,  
    - **THEN** I can enter a color keyword (e.g., `red`, `blue`) or a hexadecimal number (e.g., `#FFFFFF` for white).  
  - **WHEN** I am prompted for a shape,  
    - **THEN** I am presented with a list of shapes to choose from: `circle`, `triangle`, and `square`.  
  - **WHEN** I am prompted for the shape's color,  
    - **THEN** I can enter a color keyword (e.g., `green`, `yellow`) or a hexadecimal number (e.g., `#000000` for black).  
  - **WHEN** I have entered input for all the prompts,  
    - **THEN** an SVG file is created named `logo.svg`.  
    - **AND** the output text `"Generated logo.svg"` is printed in the command line.  
  - **WHEN** I open the `logo.svg` file in a browser,  
    - **THEN** I am shown a 300x200 pixel image that matches the criteria I entered.

## Mock-Up

Below is a sample mock-up of the expected output:

- **User Inputs:**  
  - Text: `SVG`  
  - Text Color: `white`  
  - Shape: `circle`  
  - Shape Color: `green`  

- **Generated SVG Example:**

![Sample SVG Mock-Up](./path-to-image.png)  
*(Replace with the actual image or link to the generated logo in your repository.)*

## Installation

1. Clone the repository:  
   ```bash
   git clone https://github.com/realdanielsoto/modc11.git
