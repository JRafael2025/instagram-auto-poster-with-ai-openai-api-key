# LinkedIn Auto Post (APIs Linkedin + OpenAI)

This project allows users to automatically post content to LinkedIn using the LinkedIn API and integrate OpenAI for generating content. The script handles token management, folder reading, and OpenAI integration for seamless posting on LinkedIn.

## Purpose and Main Features

The main purpose of this project is to streamline the process of posting content on LinkedIn by automating the posting process and utilizing OpenAI for content generation. Key features include:
- Token management for LinkedIn API
- Reading folders for content
- Integration with OpenAI for content generation
- Seamless posting to LinkedIn

## File Structure Explanation

- `LinkedIn Auto Post (APIs Linkedin + OpenAI)_.ipynb`: Jupyter notebook containing the script for automating LinkedIn posts using the LinkedIn API and OpenAI integration.
- `linkedin_token_meta.json`: File storing token metadata for LinkedIn API.

## Key Functions/Classes

- `import os`, `json`, `requests`: Importing necessary libraries.
- `datetime`, `timedelta`: Handling date and time functions.
- `openai_client = OpenAI(api_key=OPENAI_API_KEY)`: Initializing the OpenAI client.
- `load_configuration()`: Function to load configuration.
- `post_to_linkedin(content)`: Function to post content to LinkedIn.
- `generate_content()`: Function to generate content using OpenAI.
- `main()`: Main function to drive the automation process.

## Usage Instructions

1. Set your API keys for OpenAI, LinkedIn, client ID, and client secret in the script.
2. Run the script and ensure the configuration is successfully loaded.
3. Use the `generate_content()` function to generate content using OpenAI.
4. Use the `post_to_linkedin(content)` function to post the generated content to LinkedIn.

Ensure you have the necessary permissions and tokens for LinkedIn API access before running the script.