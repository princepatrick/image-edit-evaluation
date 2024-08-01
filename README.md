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
  
The image dataset we developed consists of 10 image domains with 5 images per domain. We have developed 5 prompts exclusively for each image. 

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

Please find the prompts in Prompts_Final.csv file and the input and output images in the /images folder
