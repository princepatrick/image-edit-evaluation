The research work focuses on evaluating image editing models, and metrics through a human evaluation-based benchmark.

We have worked on the following image editing models. All the models' implementations uses the Stable Diffusion model.

- Instructpix2pix
- Plug and Play
- ControlNet
- Grounded-Instruct-Pix2Pix

The metrics we are considering for analysis are:

- CLIP (3 versions)
- DINOv2
- LPIPS
- MUSIQ
- VILA

The image dataset we developed consists of 20 image domains with 5 images per domain. We have developed 5 prompts exclusively for each image.

The image domains used are:

- Face
- Full Portraits
- Cityscape
- Land Animals
- Marine Animals
- Cars and Trucks
- Ships
- Landscape
- Marine Landscape
- Food and Drinks
- Adventure Sports
- Cultural Contexts
- Flowers
- Fruits and Vegetables
- Household Items and Places
- Mythology and Fantasy
- People with Emotions
- Space and Astronomy
- Surreal Images
- Underrepresented Contexts

Please find the prompts in Prompts_Final.csv file and the input and output images in the /images folder for the first 10 image domains and /phase-2 folder for the latter 10 image domains

All the prompts are listed in /image-rating-instructions/Prompts_Final_Categories.csv

If you wish to reuse our manual rating for your research, please use the template found at /image-rating-instructions/Rating_Template_Final.xlsx and brief introduction on each category and rating criteria is listed in /image-rating-instructions/ImageChallengeCategories_RatingInstruction.txt

The scripts used to generate the auto rating metrics and other visualizations are present in the image-rating-instuctions/scripts along with instruction for the docker image
