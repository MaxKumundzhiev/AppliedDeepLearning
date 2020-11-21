## Mask R-CNN based on keypoint detector model using Detectron2. [CAT dataset](https://www.kaggle.com/crawford/cat-dataset)

#### Description
- The CAT dataset includes over 9,000 cat images. For each image, there are annotations of the head of cat with nine points, two for eyes, one for mouth, and six for ears.
- Detectron2 was written in PyTorch and contains many state-of-the-art obejct detection models with pretrained weights.

#### Agenda
First, we will preprocess and then convert the Cats Dataset to COCO format. After that, finetune a pretrained keypoint model (which was trained on COCO dataset) to predict cat keypoints. Finally, to see the results, run it on some videos.

**Number of points (default is 9):**
```
Left Eye
Right Eye
Mouth
Left Ear-1
Left Ear-2
Left Ear-3
Right Ear-1
Right Ear-2
-Right Ear-3
```

#### Notes
[KeyPointsDetection Kaggle NoteBook](https://www.kaggle.com/maximkumundzhiev/tf-keras-keypointdetection-within-cat-dataset)
[Detectron2 Guidance]( https://colab.research.google.com/drive/16jcaJoc6bCFAQ96jDe2HwtXj7BMD_-m5)
[Hungarian algorithm](https://towardsdatascience.com/computer-vision-for-tracking-8220759eee85)

