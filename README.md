
[![Website](https://i.ibb.co/C1v2F9q/chipling.png)](https://Chipling.xyz/)

## Run Locally

Clone the project

```bash
  git clone https://github.com/meet447/Chipling-AI.git
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  pip install -r requirements.txt 
```

Start the server

```bash
  python wsgi.py
```


# Chipling-AI



## Roadmap

- Create API Routes and Endpoints

- Add more Models

- Add Music Gen models


## Available Models


| Name      | Type     | Description                |
| :-------- | :------- | :------------------------- |
| meta/llama-2-70b-chat | Text |A 70 billion parameter language model from Meta, fine tuned for chat completions
mistralai/mistral-7b-instruct-v0.1|Text|An instruction-tuned 7 billion parameter language model from Mistral
|ai-forever/kandinsky-2.2|Image|multilingual text2image latent diffusion model
|stability-ai/sdxl|Image|A text-to-image generative AI model that creates beautiful images
|stability-ai/stable-diffusion|Image|A latent text-to-image diffusion model capable of generating photo-realistic images given any text input
|lucataco/animate-diff|Video|Animate Your Personalized Text-to-Image Diffusion Models
|anotherjesse/zeroscope-v2-xl|Video|Zeroscope V2 XL & 576w|
|fofr/latent-consistency-model|Image|Super-fast, 0.6s per image. LCM with img2img, large batching and canny controlnet|
|meta/codellama-13b|Text|A 13 billion parameter Llama tuned for code completion|
|anything/anythingv5|Image|Anything V5 is a popular choice among users for generating high-quality images from text prompts.|
|lykon/dreamshaper8|Image|One of the best models|
|lykon/absolutereality|Image|Genrate Realistic Images|
|stability-ai/stable-video-diffusion|Video|Animate your fav images to short vids|


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Tech Stack

**Client:** Html

**Server:** Python, Flask

