# ConvertDOC - File Conversion Utility

**ConvertDOC** is a powerful, user-friendly application built with Streamlit to simplify file management and conversion tasks. It enables users to convert files between various formats (e.g., CSV, Excel, PDF, images, text, JSON), process multiple files in batches, visualize data with charts, and extract text from documents. Ideal for developers, data analysts, and anyone needing efficient file processing solutions.

## Features
- **File Converter:** Convert between formats like CSV, Excel, PDF, PNG, JPG, JPEG, TXT, DOCX, MD, and JSON. Includes data visualization (bar, line, scatter charts) and image processing (filters, resizing).
- **Batch Processing:** Handle multiple files simultaneously, merging or converting them into a single ZIP file or merged document.
- **Text Extraction:** Extract text from PDFs, DOCX, TXT, MD, and HTML files, with the option to download as a TXT file.

## Installation

### Prerequisites
- Python 3.8–3.12 (Python 3.13 support may require dependency updates, currently tested up to 3.12)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Riaz-Hussain-Saifi/Python-Growth-Mindset.git
   cd Python-Growth-Mindset
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage
- Upload a file using the file uploader in the app.
- Select the desired conversion or processing option (e.g., convert to CSV, visualize data, extract text).
- Download the processed file or view the visualization as needed.

## Project Structure
```
ConvertDOC/
│
├── app.py                 # Main Streamlit application code
├── README.md             # Project documentation
├── requirements.txt      # Dependency list
├── pyproject.toml        # Project configuration (Poetry/Hatchling)
└── LICENSE               # MIT License file
```

## Dependencies
- `streamlit>=1.24.0`
- `pandas>=1.5.0`
- `numpy>=1.21.0`
- `Pillow>=9.0.0`
- `docx2txt==0.15.0`
- `PyPDF2==3.0.1`
- `reportlab>=4.1.0`
- `markdown==3.5.2`
- `xlsxwriter>=3.0.0`

## License
This project is licensed under the [MIT License](LICENSE). See the `LICENSE` file for details.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## Author
**Riaz Hussain**
- GitHub: [@Riaz-Hussain-Saifi](https://github.com/Riaz-Hussain-Saifi)
- LinkedIn: [Riaz Hussain Saifi](https://www.linkedin.com/in/riaz-hussain-saifi)
- Facebook: [RiazSaifiDeveloper](https://www.facebook.com/RiazSaifiDeveloper)
- WhatsApp: [Contact Me](https://wa.me/+923000321640)

## Acknowledgments
- Thanks to Streamlit for providing an excellent framework for building web applications.
- Gratitude to all contributors who help improve this project.

## Support
For issues or feature requests, please open an issue on the [GitHub Issues page](https://github.com/Riaz-Hussain-Saifi/Python-Growth-Mindset/issues).

## Python Version Notes
- This project is tested and compatible with Python 3.8–3.12. For Python 3.13, some dependencies may require updates or patches, which will be addressed in future releases.
