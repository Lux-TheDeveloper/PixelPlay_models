# PixelPlay_models

This report contains the models  which I have trained for the Problem statement of PixelPlay'25
I have uploaded 2 ipynb files in this repo
1)60_PixelPlay.ipynb(60% accuracy)
2)96_PixelPlay.ipynb(96% accuracy)
60_PixelPlay uses ResNet50 pre trained model modified according to the problem's needs and uses VSE loss function on newly added predicates layer and Smoothlabelling Cross entropy loss function for classes's layer and uses AdamW as optimizer 
90_PixelPlay uses ViT based CLIP as its pre trained model , I have given given 5 text prompts and then aggregated them (accuracy increased from 90-96 when I used 5 text prompts in place of 1 prompt which I was earlier using).
