# stable-diffusion-prompt-inpainting
This project helps you do prompt-based inpainting without having to paint the mask - using Stable Diffusion and Clipseg

<a target="_blank" href="https://colab.research.google.com/github/amrrs/stable-diffusion-prompt-inpainting/blob/main/Prompt_based_Image_In_Painting_powered_by_ClipSeg.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>



It's currently a notebook based project but we can convert it into a Gradio Web UI.

It takes 3 mandatory inputs.

1. Input Image URL
2. Prompt of the part in the input image that you want to replace
3. Output Prompt 

There are certain parameters that you can tune
1. Mask Precision
2. Stable Diffusion Generation Strength 


**Step-by-Step Tutorial - https://www.youtube.com/watch?v=bv1Wur3DvZ0**

### Requires:

* GPU (runs fine on Google Colab Tesla T4)

# Credit:

* Clipseg Model Weights - https://github.com/timojl/clipseg
* Stable Diffusion In-painting - https://www.youtube.com/watch?v=N913hReVxMM

# Sample Work:

![patttinson](https://user-images.githubusercontent.com/5347322/191103848-8f8925c7-24ff-4c72-bcc8-9da9432d13e9.gif)
