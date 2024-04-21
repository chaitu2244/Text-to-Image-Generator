# Text-to-Image-Generator
This codebase demonstrates the generation of images based on textual prompts. It utilizes the Stable Diffusion model for image generation and Transformers library for text processing.

Key Components
1) Stable Diffusion Pipeline: The StableDiffusionPipeline from the diffusers package is employed for image generation. It is initialized with pre-trained weights (image_gen_model_id) and configured with parameters such as torch_dtype, revision, and guidance_scale.
2) Text Processing: Text prompts are fed into the model to generate corresponding images. The generate_image function processes the textual input, conducts inference, and retrieves the generated image.
3) Prompt and Image Parameters: Various parameters such as image_gen_steps, image_gen_size, and image_gen_guidance_scale are configurable to control the image generation process.
4) Device Configuration: The code supports GPU acceleration (device = "cuda") for faster computations.
Usage

To generate images, simply call the generate_image function with a textual prompt. For example:
"generate_image("Giant Lizard attacking city", image_gen_model)"

Dependencies
1) diffusers: For Stable Diffusion model implementation.
2) transformers: For utilizing pre-trained models and text processing.
3) torch: PyTorch framework for deep learning computations.
4) matplotlib, pandas, numpy, cv2: Additional libraries for data handling and visualization.

Contributors
Chaitanya Bagwe(https://github.com/chaitu2244)
Feel free to contribute, report issues, or suggest improvements!
