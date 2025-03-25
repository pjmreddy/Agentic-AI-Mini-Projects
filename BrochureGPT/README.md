# BrochureGPT

BrochureGPT is a tool that automatically generates brochures for websites using OpenAI's GPT model and Gradio interface. It scrapes website content and creates informative brochures based on the provided URL.

## Features

- Web scraping functionality to extract content from target websites
- Integration with OpenAI's GPT model for intelligent content processing
- User-friendly Gradio interface for easy interaction
- Automatic link analysis and content structuring
- Real-time brochure generation with streaming output

## Prerequisites

- Python 3.11+
- OpenAI API key
- Required Python packages (listed in the notebook)

## Setup

1. Clone the repository
2. Create a `.env` file in the project root and add your OpenAI API key:
   ```
   OPENAI_API_KEY=your_api_key_here
   ```
3. Install the required Python packages using one of these methods:
   ```
   # Option 1: Install packages directly
   pip install openai gradio beautifulsoup4 python-dotenv requests ipython

   # Option 2: Install from requirements.txt
   pip install -r requirements.txt
   ```

## Usage

1. Run the Jupyter notebook `Brouchure_Creation_for_Website_Using_OpenAI_Gradio.ipynb`
2. The Gradio interface will launch, displaying two input fields:
   - Company name
   - Landing page URL (including http:// or https://)

![Gradio Interface](gradio_interface.svg)

3. Enter the company name and website URL
4. Click submit to generate the brochure
5. The generated brochure will appear in the output section

### Example Output

![Sample Brochure Output](sample_output.png)

Example of a generated brochure for Geeks for Geeks website, showcasing the tool's ability to create structured, informative content

## Implementation Details

The project uses:
- BeautifulSoup4 for web scraping
- OpenAI's GPT model for content generation
- Gradio for the user interface
- Python's requests library for HTTP requests

The main components include:
- Website class for handling web scraping
- OpenAI integration for content processing
- Gradio interface for user interaction

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is open source and available under the MIT License.