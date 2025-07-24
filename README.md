# Image-Generation-and-Variation-with-DALL-E-3-and-Stable-Diffusion
This application allows users to generate and modify images using DALL-E 3 and Stable Diffusion models through a Streamlit interface.

## Features
* **DALL-E 3 Image Generation:** Generate high-quality images from text prompts.
* **DALL-E 3 Variation:** Create variations of existing images.
* **Stable Diffusion:** Generate images using Stable Diffusion with customizable prompts.

## Installation

Clone this repository.

Set up your environment variables in a .env file:

```
openai_apikey=YOUR_OPENAI_API_KEY
stabilityai_apikey=YOUR_STABILITY_AI_API_KEY
```

Install the required Python packages:

```pip install -r requirements.txt```

## Usage

Run the Streamlit app:

```streamlit run app.py```

Use the provided tabs to either generate new images or create variations.

## Requirements

- Python 3.x
- Streamlit
- OpenAI Python client
- Requests
- Python-dotenv

## Acknowledgements

- OpenAI for the DALL-E 3 API.
- Stability AI for the Stable Diffusion API.
