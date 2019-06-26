# Image-capturing-for-deep-learning-dataset-using-API
API using google-images-download to fetch images automatically from google search. I used google colab to run the code but can be run in any IDE. In this case images regarding yoga pose has been demostrated.

However, to run the code successfully, frozen_inference_graph.pb needs to be located from coco dataset. It can be downloaded from the this github [link](https://github.com/floydhub/object-detection-template/tree/master/models/ssdlite_mobilenet_v2_coco_2018_05_09).

However, to simplify I have kept a copy of frozen_inference_graph.pb in this repository. 

To download preferred images from google search simply change the name of the search files in the complete_list and make corresponding adjustment in both download_image and detect_persons_and_save_crops functions.

The final result would look something like this:

