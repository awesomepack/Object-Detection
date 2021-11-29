# Object-Detection

## Project Scope
Historically, object detection algorithms have been trained using iconic images, those with the object in focus, instead of natural images that occur in reality. The result, are object detection algorithms that underperform when the object is amongst clutter and other object types as is typical of nattural images. The COCO dataset aims to solve problems in scene understanding by providing images that can train algorithms to detect non-iconic views, provide contextual reasoning between objects , and pinpoint the object instances in an image and segement them. I will develop an application that recieves a user's image and segments a requested object type using an object-detection algorithm trained using the [Common Objects in Context](https://cocodataset.org/#explore) Dataset.

### Deliverables
* A python script that makes an api call to an image dataset using requested object
* A python script that performs general image processing to images
* A python script that trains an image classification model
* A web application that receives user image and object and returns an annotated image with objects circled

## Image Dataset
* [Coco](https://cocodataset.org/#download) A dataset of common objects with its own api to help parse data

## Storage
* Use a PostgreSQL instance to store image training data

## Image pre-processing
* apply paradigm pre-processing techniques on training data

## Training
* Train an object detection algorithm using processed images

## Web application
* Create a web page that requests user for target object and image
* This information will be used to generate a dataset of relevant images for the model to be trained on
* The web app will return the target image with the target objects that were found within it on the web page.


