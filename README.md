# English to Multiple Language Translator

## Description
This is an application that translates English text into various languages. It uses OpenAI's GPT-3 model to perform the translations.

Features include:
- Support for numerous languages
- Ability to set a default translation language
- Translation history
- Option to clear translation history

## Setup & Installation

To set up and run this application locally:

1. Clone the repository

```bash
git clone https://github.com/lcharleslaing/english-to-any-language-app.git
```
2. Navigate into the project directory

```bash
cd translation-app
```
3. (Optional) Create a virtual environment and activate it

```bash
python -m venv env
source env/bin/activate # On Windows use env\Scripts\activate
```
4. Install the required Python packages

```bash
pip install -r requirements.txt
```
5. Set up your OpenAI API key. You can do this by creating a .env file in the project root and adding your key like so:

```bash
OPENAI_API_KEY=your-api-key-here
```
6. Run the Streamlit app

```bash
streamlit run app.py
```


## Deployment

The application can also be hosted on Streamlit Sharing, which is a platform by Streamlit that lets you deploy, manage, and share your Streamlit apps with the world.

Here's how to do it:
1. Push your application to a public GitHub repository
2. Visit [Streamlit sharing](https://share.streamlit.io/) and click on the "New app" button
3. Enter the link to your GitHub repository and select the branch
4. Finally, select the file path of your Streamlit application and click "Deploy"

That's it! Your application will now be live and can be accessed via the provided URL.

## Contributions

We welcome contributions to this project. Please feel free to open a pull request or get in touch if you have any questions or suggestions.
