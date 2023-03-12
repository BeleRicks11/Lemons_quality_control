# Lemons quality control 🍋
In this work, we have tried to address the product quality control problem, by implementing a neural network for performing the semantic segmentation of images
containing lemons. In order to have performances near to real-time, for this particular task, we decided to use the SFNet model on top of a lightweight ResNet-18
backbone. We experimented with different configurations of this architecture, applying simple modifications to the model, in order to increase the performance. In the
end, we’ve been able to archive around 39% of mIoU with our best configuration.
