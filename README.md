# Gemini Pro - ChatBot

This project implements a chatbot using Google's Gemini-Pro AI model integrated with Streamlit.

## Getting Started

### Prerequisites

Make sure to have Python installed on your machine.

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-OmBirari/gemini-pro-chatbot.git
    cd gemini-pro-chatbot
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Set up your environment variables by creating a `.env` file and adding your Google API key:

    ```env
    GOOGLE_API_KEY=your_google_api_key
    ```

2. Run the Streamlit app:

    ```bash
    streamlit run app.py
    ```

3. Open your browser and go to [http://localhost:8501](http://localhost:8501) to interact with the Gemini Pro ChatBot.

## Configuration

You can customize the Streamlit page settings, such as the page title and layout, by modifying the `st.set_page_config` section in `app.py`.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
