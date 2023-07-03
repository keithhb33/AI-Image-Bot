# AI_Image
Sends a request to Craiyon AI Image Generator to generate images in Base64 code from a chosen prompt. The program then parses and assembles the Base64 code into JPG files.

<h4>Here are some examples:</h4><br />

<p float="center">
  <img src="images/spongebobandpatrickjellyfishing.jpg" width="190" />
  <img src="images/starrynightcubism.jpg" width="190" /> 
  <img src="images/riverstyx.jpg" width="190" />
  <img src="images/satanhome.jpg" width="190" />
  
  <img src="images/spongebobandpatrickjellyfishing2.jpg" width="190" /> 
  <img src="images/starrynightcubism2.jpg" width="190" />
  <img src="images/riverstyx2.jpg" width="190" />
  <img src="images/satanhome2.jpg" width="190" />
</p>

<p align="center">
  <img src="images/ai_files.JPG" width="600" alt="ai_images">
</p>

<h1>Usage:</h1>

```python
#Installation:
python3 -m pip install ai_image

#Implementation:
from ai_image.ai_image import ai_images

prompt = "example prompt"
directory = "images/"

ai_images(prompt, directory)
#Returns 9 images to directory
```
