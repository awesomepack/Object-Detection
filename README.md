# Object-Detection
An application that receives a user's target object and image and returns a processed image with the user's object higlighted if present.

## Project Scope

### Statement of Work
Develop an application that identifies a requested object within a user's uploaded image.

### Deliverables
* A python script that makes an api call to an image dataset using requested object
* A python script that performs general image processing to images
* A python script that trains an image classification model
* A web application that receives user image and object and returns an annotated image with objects circled

## Image Dataset
* [Image Net](https://image-net.org/about.php) Provides a dataset of images representing the synsets (concepts) represented in the WordNet heirarchy
* [Coco](https://cocodataset.org/#download) A dataset of common objects with its own api to help parse data

## Storage
* Determine the best way to store a dataset of image files for computer vision

## Image pre-processing
* apply paradigm pre-processing techniques on training data

## Training
* Train an object detection algorithm using processed images

## Web application
* Create a web page that requests user for target object and image
* This information will be used to generate a dataset of relevant images for the model to be trained on
* The web app will return the target image with the target objects that were found within it on the web page.


