# YOLOv8-SCS

> **YOLOv8-SCS: Improved Object Detection for Autonomous Driving Under Adverse Weather Conditions**  
> Y. Lee and J. Kang, *IEEE Access*, vol. 13, pp. 149933-149946, 2025  
> [📄 Paper](https://doi.org/10.1109/ACCESS.2025.3602211)

**YOLOv8-SCS** is a model that integrates Swin Transformer, CBAM, and SCDown modules into YOLOv8 to enhance object detection performance under adverse weather conditions.

The main architectural modifications can be found in the `conv.py` and `task.py` files.

## abstract

Adverse weather conditions significantly impact the performance of autonomous driving object detection systems, leading to reduced detection accuracy and an increased false detection rate. Limited annotated data further restricts performance improvement. Hence, improving detection performance under adverse weather conditions is a challenge that remains to be solved. In this paper, we develop an improved object detection model, named YOLOv8-SCS, by incorporating the Swin Transformer, Convolutional Block Attention (CBAM), and Spatial-Channel Decoupled Downsampling (SCDown) modules. YOLOv8-SCS aims to enhance feature extraction from objects and emphasize important features in the feature map, both of which are affected by adverse weather conditions, without compromising model efficiency for real-time applications. Experimental results verify that on the DAWN dataset, YOLOv8-SCS achieves performance improvements of 3.22%, 2.22%, 2.63%, 2.90%, and 0.72% in terms of Precision, Recall, F1-Score, mAP50, and mAP50-95 compared to the original YOLOv8. Furthermore, its lightweight variant, YOLOv8-SCS-light, also shows gains of 1.72%, 1.48%, 1.60%, 2.18%, and 0.4% in the same metrics, while enhancing model efficiency by reducing the number of parameters and GFLOPs, and increasing FPS. In addition, the generalization ability of the proposed model under clear weather conditions is verified using the BDD100K dataset.



## Citation
If you use **YOLOv8-SCS** in your research, please cite:

```bibtex
@ARTICLE{11135491,
  author={Lee, Younggyu and Kang, Jinho},
  journal={IEEE Access}, 
  title={YOLOv8-SCS: Improved Object Detection for Autonomous Driving Under Adverse Weather Conditions}, 
  year={2025},
  volume={13},
  pages={149933-149946},
  doi={10.1109/ACCESS.2025.3602211}
}
