# Deep-Learning-Based-Car-Damage-Detection-Classification-and-Severity

In the accident insurance industry, settling the claim is a
time-consuming process since it is a manual process and there
is a gap between the optimal and the actual settlement. Using
deep learning models, we are not only trying to speed up the
process but also provide better customer service and increase
the profitability of insurance companies. In this paper we are
using various pretrained models such as VGG 16, VGG 19,
Resnet50 and Densenet and based on these models, selecting
the best performing models. We initially check whether the
car is damaged or not using the Resnet50 model and if it’s a
damaged one we use the WPOD-net model to detect the
license plate. To identify the damaged region, we use the
YOLO model. At last, comes the damage severity which is
implemented using the Densenet model. After implementing
various models, we find out that transfer learning gives better
results than fine-tuning. In addition to that we propose a
framework that integrates all of this into one application and
in turn helps in the automation of the insurance industry.
