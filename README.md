
# text-to-image-tool

 Documenting the journey to creating AI-generated portraits of me! 

## Why put this together?

I saw an article about how you can use AI to generate an image of yourself in various styles and it would be fun to try out. I also wanted to learn more about AI and how it works. I spent a few days getting it working and scoured the internet to troubleshoot all the errors I ran into. I thought it would be cool to document my journey and share what I learned, and if it helps others, that would be great!

## What is it?

Automatic1111 is a tool that uses AI to generate an image of you in various styles. It uses a pre-trained model to generate the image. You can also train your own model if you want to, which is what I did in this demo by leveraging the Huggingface community and the Dreambooth extension.  

Huggingface is a community of people who share their AI models. You can use their models to generate images, text, etc. For this demo, the `runwayml/stable-diffusion-v1-5`, `v1-5-pruned-emaonly.ckpt` model was used.  

Once all of this (plus some tweaks here & there) was set up, I could build my own AI model and generate an image of myself in various styles.  

## Tools used

**Automatic1111**; [link to repo](https://github.com/AUTOMATIC1111/stable-diffusion-webui)  \
**Dreambooth extension**; This can be downloaded from the AUTOMATIC1111 web-UI once that is set up  \
**Huggingface**; [Stable Diffusion](https://huggingface.co/runwayml/stable-diffusion-v1-5)  \
**Olivio Sarikas, Youtube**; [Installing Automatic1111](https://www.youtube.com/watch?v=3cvP7yJotUM) | [Installing and Training with Dreambooth](https://www.youtube.com/watch?v=9Nu5tUl2zQw)  \
**Reddit**, Stable Diffusion; [Lots of questions and informative answers on here](https://www.reddit.com/r/StableDiffusion/search/?q=automatic1111&cId=dd328b81-294f-4a07-868f-fbddf63c274f&type=link)  \
**Stackoverflow**; [Especially good for getting the initial setup working](https://stackoverflow.com)  \
**DXdiag**; Understanding your own computer specs is important for understanding the errors you may get from the console  \
**Super helpful Cheat sheet**; [@supaGuren's stable diffusion cheat is awesome](https://github.com/SupaGruen/StableDiffusion-CheatSheet)

## Get it learning

1. Take some selfies, I used 10 images with the 'Square' style from my phone camera. I resized these to 512x512 and saved them as .jpg files.  
2. Rename the images to something unique, for example, `firstname_lastname(x).jpg`  

3. Install Automatic1111; this was achieved by following the guide and links in the description of Olivio's video "Installing Automatic1111"  
4. Add the dreambooth extension to Automatic1111, follow the guide and links in the description of Olivio's video (this has been linked above)  
5. Now, you train the model with your subject of choice. In my case, it was me, but as long as you provide enough source material, you can train the model to generate images of anyone or anything  
    a. I suggest following Olivio's video as closely as possible, and if/when you encounter issues, refer to the links in this readme and use some Google Ninja skillzz to find the answers you need - you will get it working eventually!  
6. You should now have a trained model and can start generating images

## What went wrong, and what did I learn?

I encountered challenges in the following areas:

- AI Training
- Memory & GPU errors
- Prompt issues

The main things that I learned were patience and persistence. This was a completely new concept, and I had to learn many new things to get it working. Following the guided videos was enough for much of the process, but when I ran into issues, I had to research to find the answers I needed.  
This is because everyone's computer is different, and the errors I was getting were specific to my hardware. Anyone else trying to do this will likely run into different issues, but the process of finding the answers will be the same.  

I learnt that I may need to upgrade my 2070 super card if I want to do this again :P  
The model training process is very GPU intensive, and my 2070 super was not up to the task with the default config settings. I had to find methods to reduce the load on the GPU.  
I had to make some changes to the configuration of the web GUI. This worked well and was simple to achieve with the help of Reddit and StackOverflow. 

I also learnt that the prompt you use to generate the image is very important. I had to experiment with different prompts to get the results I wanted. 
Once again, I went to the internet to find my needed answers. I found a very helpful cheat sheet (linked above), and I also found a few Reddit posts that were very informative too.  

## Credits

**Olivio Sarikas**; Olivio's videos were very helpful, and I would not have gotten this working without them.  
**Automatic1111**; The Automatic1111 team have done great with this tool, and I am very grateful for their work.  
**Huggingface**; The Huggingface community is awesome, and I am very grateful for their work.  
**Reddit**; The Reddit community is awesome, and I am very grateful for their work.  
**Stackoverflow**; The Stackoverflow community is awesome, and I am very grateful for their work.  
**SupaGruen**; The Stable Diffusion Cheat Sheet is awesome, and I am very grateful for their work.  
**Myself**; I am awesome, and I am very grateful for my work :P  

Check out what I generated in the `output` folder! Yes, some of them are completely botched, I kept these in for balance!  
