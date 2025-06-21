# image-captioning-and-segmentation

## 📁 Dataset Overview
### JSON files covering splits for:

MS COCO (2014 subset) <br>
Flickr8k <br>
Flickr30k 

### Each JSON contains:
### images: with fields like:
filename — path to the image <br>
split — labeled as "train", "val", "test" (or "restval") <br>
sentences — an array of caption objects: <br>
tokens: list of lowercased caption words <br>
raw: full caption string <br>
image and sentence IDs 
