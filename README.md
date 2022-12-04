# YOLO_v7_pose_estimation_keypoints
This notebook public url

https://www.kaggle.com/code/akashrayhan/yolo-v7-pose-keypoints

Dataset:
1. Images (1269 images)
2. labels.csv (3 labels - running, sitting, sleeping)


Passed every image to a pose detection library (yolov7), extracted the body keypoints and finally write each
image’s keypoints to a csv (unbalanced_keypoints.csv) with the exact label
(from labels.csv).


As the dataset is imbalanced, it might cause low generalization in training.Created another csv file (balanced_keypoints.csv) by balancing
the generated data (unbalanced_keypoints.csv) using
relevant techniques such as upsampling, SMOTE .
