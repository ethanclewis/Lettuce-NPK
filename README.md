# FNNPK
*Lettuce NPK Dataset* image files.
- Fully Nutritional **(FN)**: 12 images
- Nitrogen Deficient **(-N)**: 58 images
- Phosphorus Deficient **(-P)**: 66 images
- Potassium Deficient **(-K)**: 72 images

# Fine-Tuning Iterations
Indivudal notebooks detailing training loop and model parameters, as well as results, for each progressive, fine-tuning iteration in between the **Initial Model** and the **Final Model**.  
A summary of all relevant parameters are listed at the top of each notebook.  
All models trained on Nvidia GeForce GTX 1660 Ti GPU.

# Initial Model
### *Initial Model.ipynb*
Notebook detailing training loop and model parameters for initial model training attempt, as well as results.  
Useful for direct comparison to the **Final Model**.  
Trained on Apple M1 Chip.
### *mpk_model_v3.pth*
Saved model.  
The **Initial Model** was trained on Apple M1 Chip, rather than Nvidia GeForce GTX 1660 Ti GPU, hence the alternative saved model path.

# EDA
Notebook provides basic visualization of the *Lettuce NPK Dataset* and its class distribution.  
The *Transformation Playground* details our process of deriving an appropriate image augmentation pipeline.

# Final Model.ipynb
Notebook detailing training loop and model parameters for final model training attempt, as well as results.  
Useful for direct comparison to the **Initial Model**.  
Trained on Nvidia GeForce GTX 1660 Ti GPU.
