# Tracking by detection algorithm based on YOLOv3 and SORT algorithms.

In this exercise we study the following papers, and answer some questions on them:

- [You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/pdf/1506.02640.pdf)
- [YOLOv3: An Incremental Improvement](https://arxiv.org/pdf/1804.02767.pdf)
- [SIMPLE ONLINE AND REALTIME TRACKING](https://arxiv.org/pdf/1602.00763.pdf%5D)

Also, we provide an implementation of the algorithm and experiment with the hyperparameters confidence threshold and non-max suppression threshold.

## Questions

The following questions are answered in the notebook (in greek):

1. What is the difference between the bounding box and the anchor box in YOLO? (Explain briefly)
2. What will the dimensions of the output (prediction) table y_hat of the YOLO algorithm be, assuming we have three anchor boxes and 4 classes? Also indicate the role for each element of this table.
3. How do the different settings for the threshold and the overlap parameter affect the performance of the Non-max suppression method?
4. What are some of the key advantages of using the SORT algorithm for object tracking?
5. How is the tracking-by-detection method defined and how does it work?

## Files

The exercise was implemented in a Jupyter Notebook, but a pdf of the notebook is provided (`IVP_lab3.pdf`), as the file was very big (~380MB).
