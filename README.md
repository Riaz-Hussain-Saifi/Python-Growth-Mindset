# Growth-Mindset

**A powerful file conversion utility with batch processing capabilities**

Growth-Mindset is a Streamlit-based application designed to simplify file management and conversion tasks. Whether you need to convert files between formats, process batches of files, or extract text from documents, this tool has you covered. It’s perfect for developers, data analysts, and anyone looking for an efficient way to handle files.

## Features

- **File Converter**: Convert files seamlessly between formats such as CSV, Excel, PDF, images (PNG/JPG), text files (TXT/DOCX/MD), and JSON. Includes data visualization (charts) and image processing (filters, resizing).
- **Batch Processing**: Upload multiple files of the same type and process them into a single ZIP file for convenience.
- **Text Extraction**: Extract text from PDFs, DOCX, TXT, MD, and HTML files, with downloadable TXT output.
- **User-Friendly Interface**: Built with Streamlit for an intuitive, web-based experience.
- **Responsive Design**: Vibrant, animated UI with CSS styling for desktops and mobile devices.

## Installation

### Prerequisites
- Python 3.12 or higher
- Git (optional, for cloning the repository)

### Steps
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Riaz-Hussain-Saifi/Python-Growth-Mindset.git
   cd Python-Growth-Mindset
   ```

2. **Install Dependencies**:
   Using `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```
   Or, if using `pyproject.toml` with a tool like Poetry:
   ```bash
   poetry install
   ```

3. **Run the App**:
   ```bash
   streamlit run app.py
   ```
   Open your browser to `http://localhost:8501` to access the app.

## Usage

1. **Launch the App**: Start the app using the command above.
2. **Navigate the Sidebar**:
   - **File Converter**: Upload a single file and choose conversion options.
   - **Batch Processing**: Upload multiple files to process them into a ZIP.
   - **Text Extraction**: Upload a document to extract and download its text.
   - **About**: Learn more about the app and its developer.
3. **Follow On-Screen Instructions**: Each section provides guidance on supported file types and actions.

### Supported File Types
- **Data**: CSV, XLSX, XLS, JSON
- **Images**: PNG, JPG, JPEG
- **Documents**: PDF, DOCX, TXT, MD, HTML

## Dependencies

- `streamlit>=1.42.2`
- `pandas>=2.2.3`
- `numpy>=2.2.3`
- `Pillow>=11.1.0`
- `python-docx>=0.8.11`
- `PyPDF2==3.0.1`
- `reportlab>=4.3.1`
- `markdown>=3.7`
- `xlsxwriter>=3.2.2`

See `requirements.txt` or `pyproject.toml` for the full list.

## Deployment

To deploy on Streamlit Cloud:
1. Push your repository to GitHub.
2. Log in to [Streamlit Cloud](https://streamlit.io/cloud).
3. Create a new app, linking it to your repository.
4. Specify `app.py` as the entry point and ensure `requirements.txt` or `pyproject.toml` is included.
5. Deploy and access your app online!

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "Add your feature"`).
4. Push to your fork (`git push origin feature/your-feature`).
5. Open a Pull Request.

Please report issues or suggest features via the [Issues](https://github.com/Riaz-Hussain-Saifi/Python-Growth-Mindset/issues) tab.

## Developer

**Riaz Hussain**  
- **Email**: infosaifideveloper@gmail.com  
- **LinkedIn**: [Riaz Hussain Saifi](https://www.linkedin.com/in/riaz-hussain-saifi)  
- **GitHub**: [Riaz-Hussain-Saifi](https://github.com/Riaz-Hussain-Saifi)  
- **Facebook**: [RiazSaifiDeveloper](https://www.facebook.com/RiazSaifiDeveloper)  
- **WhatsApp**: [+923000321640](https://wa.me/+923000321640)  

A senior student at GIAIC (Governor-Sindh Initiative of Artificial Intelligence and Computing), currently in Quarter 3, pursuing Python, AgentAI, and Full Stack Development.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Built with [Streamlit](https://streamlit.io/), an amazing tool for creating data apps.
- Thanks to the open-source community for the libraries powering this project.

© 2025 ConvertDOC. All rights reserved.