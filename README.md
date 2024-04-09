# Resume Generator

This Python script generates a professional resume in Microsoft Word (.docx) format using the `python-docx` library. The resume is structured with customizable styles and sections, making it easy to modify and adapt to your specific needs.

## Features

- Customizable styles for different sections of the resume
- Automatic formatting of sections, including name, contact information, summary, technical skills, professional experience, education, certifications, and additional experience
- Easy addition of bullet points for professional experience and skills
- Generated resume is saved as a Word document (`KeenanFinkelstein_Resume.docx`)

## Requirements

- Python 3.x
- `python-docx` library

## Installation

1. Clone the repository or download the script file.

2. Install the required `python-docx` library using pip:

   ```
   pip install python-docx
   ```

## Usage

1. Open the script file in a text editor.

2. Modify the resume content in the script, including:
   - Name and contact information
   - Summary
   - Technical skills
   - Professional experience (job titles, company names, locations, dates, and bullet points)
   - Education and certifications
   - Additional experience

3. Save the script file after making the necessary changes.

4. Run the script using Python:

   ```
   python resume_generator.py
   ```

5. The generated resume will be saved as `KeenanFinkelstein_Resume.docx` in the same directory as the script.

## Customization

- To modify the styles of different sections, adjust the font size, boldness, and other properties in the `document.styles.add_style()` method calls.
- To add or remove sections, use the `add_section()` function with the desired section title and style.
- To add or remove bullet points, modify the lists passed to the `add_bullet_points()` function.

## Contributing

Feel free to fork the repository, make improvements, and submit pull requests. If you find any issues or have suggestions for new features, please open an issue on the GitHub repository.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Credits

The script was created by Keenan Finkelstein and is based on the `python-docx` library.
