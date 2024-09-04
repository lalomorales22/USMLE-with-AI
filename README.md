# USMLE Prep Conversational AI
<img width="1097" alt="Screenshot 2024-09-04 at 4 15 29 PM" src="https://github.com/user-attachments/assets/af9ad5fc-ec71-45c7-b999-9bfcf26cfdc0">


## Description
The USMLE Prep Conversational AI is a Streamlit-based application designed to assist medical students in preparing for the United States Medical Licensing Examination (USMLE). It leverages AI models from both OpenAI and Ollama to provide intelligent assistance, answer questions, and offer explanations across various medical topics covered in the USMLE.

## Features
- AI-powered assistance for USMLE preparation
- Support for multiple AI models (OpenAI GPT models and Ollama models)
- Covers a wide range of USMLE categories including Anatomy, Behavioral Science, Biochemistry, and more
- Ability to focus on specific categories
- Dark/Light theme toggle
- Conversation saving and loading functionality
- Token usage tracking

## Requirements
- Python 3.7+
- Streamlit
- OpenAI Python library
- Ollama Python library
- python-dotenv (for environment variable management)

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/usmle-prep-conversational-ai.git
   cd usmle-prep-conversational-ai
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

4. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your OpenAI API key to the `.env` file:
     ```
     OPENAI_API_KEY=your_api_key_here
     ```

5. Ensure Ollama is installed and running on your system (if you plan to use Ollama models)

## Usage

1. Run the Streamlit app:
   ```
   streamlit run app.py
   ```

2. Open your web browser and go to the URL provided by Streamlit (usually http://localhost:8501)

3. Use the sidebar to:
   - Select an AI model
   - Choose USMLE categories to focus on
   - Customize the AI instructions
   - Toggle between light and dark themes
   - Save or load conversations

4. Enter your questions or study topics in the chat input at the bottom of the page

5. The AI assistant will provide responses to help you prepare for the USMLE

## USMLE Categories
The application covers the following USMLE categories:
- Anatomy
- Behavioral Science
- Biochemistry
- Biostatistics
- Embryology
- Genetics
- Histology
- Immunology
- Microbiology
- Pathology
- Pathophysiology
- Pharmacology
- Physiology

## Customization

- To modify the AI's behavior or add specific instructions, adjust the `custom_instructions` text in the `app.py` file
- To add or modify USMLE categories, edit the `USMLE_CATEGORIES` list in the `app.py` file

## Contributing

Contributions to improve the USMLE Prep Conversational AI are welcome. Please feel free to submit pull requests or open issues to discuss potential changes or enhancements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This application is designed as a study aid and should not be considered a substitute for comprehensive USMLE preparation. Always refer to official USMLE preparation materials and consult with medical education professionals for a complete study plan.
