# Hu-Shurui-project
RetinaNet is a model to work on object detection. Aiming at the imbalance of positive and negatives categories in the former one-stage target detection model, a Loss function called Focal Loss is proposed. It is used to reduce the weight of a large number of easy negatives in the standard cross entropy (increase the weight of hard negatives).

In this report, I filled all blanks in the Model, FPN Network, Object Detection Loss Function, Dataloader and Training Pipeline. Then, I try to improve the detection performance by changing optimizer and depth of ResNet, adding number of layers of the convolustion in regression and classification, adding factors when calculating loss. Also, tensorboard is utilised for visualisation.

training_log.txt is a recording of training process.
