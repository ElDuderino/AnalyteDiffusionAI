# AnalyteDiffusionAI
Experimental notebooks for generative AI for analyte diffusion

These experiments are meant to answer the question: can we create a generative AI to create heatmaps for various diffusion functions (such as inverse square law for light) using multiple sources (measurements) at x/y/z locations in space.

For the first experiments, we created training datasets with inverse square law heatmaps. The input to the NN was the x, y and intensity of the sources. Loss was computed as the difference between the AI generated heatmap and the inverse square law heatmaps. 

For fixed locations and varying intensities, the MSE is very low and results very good. For random location and varying intensities, the results are promising / decent, but the architecture clearly needs refinement. 

![image](https://github.com/ElDuderino/AnalyteDiffusionAI/assets/585401/bd4ed0cd-7b09-4eca-b64b-54d0094833b5)

