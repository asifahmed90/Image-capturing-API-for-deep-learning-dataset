# Image-capturing-for-deep-learning-dataset-using-API
A simple API using google-images-download to fetch images automatically from google search. I used google colab to run the code but can be run in any IDE. In this case images regarding yoga pose has been demostrated.

### Dependency:
1. Tensorflow
2. google-images-download
3. OpenCV

However, to run the code successfully, frozen_inference_graph.pb needs to be located from coco dataset. It can be downloaded from the this github [link](https://github.com/floydhub/object-detection-template/tree/master/models/ssdlite_mobilenet_v2_coco_2018_05_09).

To simplify the steps I have kept a copy of frozen_inference_graph.pb in this repository. Clone the repo and point out the .pb file location in the code.

To download preferred images from google search simply change the name of the search files in the complete_list and make corresponding adjustment in both download_image and detect_persons_and_save_crops functions.

The final result would look something like this:

![image](https://user-images.githubusercontent.com/45178199/60221052-d70ea900-983d-11e9-9eb8-b91008839cb2.png)

To contrubite please fork the file and create a pull request.

Thank you for using this. Let me know if you face any issues.

