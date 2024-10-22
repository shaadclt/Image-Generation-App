# Image Generation App with DALL-E and Huggingface Diffusers"
This project is a Streamlit-based web app that enables users to generate AI-generated images using text prompts. The app integrates two powerful image generation models: OpenAI's DALL-E and Huggingface's Diffusion models.

## Features
- **DALL-E Integration:** Generates images using OpenAI's DALL-E model.
- **Huggingface Diffusers Integration:** Generates images using Huggingface's Stable Diffusion model.
- **Simple UI:** Intuitive user interface to input text prompts and view generated images.
- **CUDA Support:** Utilizes GPU for faster image generation using Huggingface's Diffusers.

## Setup Instructions
1. **Clone the Repository**

```bash
git clone https://github.com/shaadclt/Image-Generation-App.git
cd Image-Generation-App
```

2. **Install Dependencies**

Use the requirements.txt file to install the necessary packages:

```bash
pip install -r requirements.txt
```

3. **Set Up API Keys**

Create a `.env` file in the root directory and add your OpenAI API key:

```bash
OPENAI_API_KEY=your_openai_api_key
```

4. **Run the App**

Run the Streamlit app:

```bash
streamlit run app.py
```

5. **CUDA Setup** (Optional for Diffusers)

Ensure you have the necessary GPU drivers and libraries for running Stable Diffusion with CUDA. This improves image generation performance.

## Usage
1. Select the model you want to use from the sidebar (`DALL-E` or `Huggingface Diffusers`).
2. Input your text prompt in the provided field.
3. Click the "Generate Image" button.
4. View the generated image in the app interface.

## Contributing
Feel free to contribute by opening issues or submitting pull requests.

## License
This project is licensed under the [MIT License](LICENSE.txt).
