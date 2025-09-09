%run train.py
Configure parameters such as batch size and pre-trained weights according to Table 1 in the paper.
The file of yolov5s.pt is the pre-train weight for GS-YOLO training.

The two main contributions of this work are:

C3Ghost-S: The activation function in GhostConv is replaced with SiLU, resulting in Ghost-S, which is then integrated into the C3 feature extraction module to form C3Ghost-S.

GA-SPPF: Two branches—Global Max Pooling (GMP) and Global Average Pooling (GAP)—are introduced into the SPPF module, while the activation function of the final 1×1 convolution is replaced with LReLU.
