# Awesome-Computer-Vision-Object-Detection

# Awesome-Computer-Vision-Object-Detection

# Top Computer Vision Object Detection Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Visual Detection, Instance Segmentation & Real-Time Inference*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Computer Vision Object Detection**. These tools enable developers and organizations to build, train, and deploy models that locate and classify objects within images and video — powering use cases from autonomous vehicles to retail analytics, industrial inspection, and medical imaging.

**Examples** include Salesforce Einstein Object Detection, Roboflow, Ultralytics HUB, Google Cloud Vertex AI Vision, AWS Rekognition, Azure Custom Vision, LandingLens, Clarifai, SuperAnnotate, and Supervisely (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom model training, and production inference pipelines — ideal for researchers, ML engineers, and developers seeking transparent, vendor-independent object detection solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Einstein Object Detection](https://developer.salesforce.com/)**  
  Einstein Platform Service (now retired in Summer '23) that enabled developers to train models to recognize multiple unique objects within a single image, including location, size, and quantities. Used for inventory management, share-of-shelf analysis, and customer service . Training required annotated bounding boxes provided via `annotations.csv` with x/y coordinates, width, and height .

- **[Roboflow](https://roboflow.com/)**  
  Dataset preparation and deployment platform with versioning and managed annotation workflows. Supports object detection, classification, and segmentation with traceable training exports and controlled label iteration.

- **[Ultralytics HUB](https://hub.ultralytics.com/)**  
  No-code end-to-end ML platform for training and deploying YOLOv5 and YOLOv8 models. Features cloud training with Nvidia T4 GPU instances, dataset management, model selection, and REST API access. Training options include Ultralytics Cloud, Google Colab, and local GPU agents . Pro plan adds extra storage, cloud training, and Teams collaboration .

- **[Google Cloud Vertex AI Vision](https://cloud.google.com/vertex-ai)**  
  End-to-end platform for building and deploying computer vision applications. Supports stream video analysis and Vision Warehouse storage for traffic monitoring, occupancy analysis, and congestion detection . Provides pre-trained specialized models for vehicle and person counting at specific lines or fixed areas .

- **[AWS Rekognition](https://aws.amazon.com/rekognition/)**  
  Deep learning-based image and video analysis service. Features object/scene detection, text detection, unsafe content moderation, celebrity recognition, and Custom Labels for training classifiers on proprietary objects.

- **[Azure Custom Vision](https://azure.microsoft.com/en-us/products/ai-services/ai-vision)**  
  Prebuilt and customizable models for image analysis, tagging, and domain-specific detection. Supports custom model training with your own images for object detection tasks.

- **[LandingLens](https://landing.ai/)**  
  Computer vision platform focused on data-centric AI. Provides tools for visual inspection, defect detection, and model deployment for industrial and enterprise use cases.

- **[Clarifai](https://www.clarifai.com/)**  
  Production tagging platform with model training and customization. Supports versioned models for repeatable inference baselines and configurable threshold governance for audit-ready deployments.

- **[SuperAnnotate](https://www.superannotate.com/)**  
  Platform supporting the full lifecycle of AI data development. Provides annotation for images, video, text, audio, and documents with AI-assisted labeling, quality assurance workflows, and Python SDK/REST API. Supports bounding boxes, segmentation masks, and keypoints . Consistently praised for intuitive interface and collaboration tooling .

- **[Supervisely](https://supervisely.com/)**  
  Computer vision platform with advanced video and 3D point cloud labeling. Features tracking-by-detection using pretrained detectors (YOLO, RT-DETRv2) combined with DeepSORT/BoT-SORT algorithms . Supports first-frame initialized trackers (XMem, SAM 2, MixFormer, CoTracker) and pretrained 3D models (CenterPoint, PV-RCNN, PointPillars) for LiDAR data . The 3D AI assistant enables class-agnostic detection, ground segmentation, and 2D-to-3D annotation transfer .

## Open-Source GitHub Projects

- **[Ultralytics YOLO](https://github.com/ultralytics/ultralytics)**  
  The most widely used object detection framework (AGPL-3.0). YOLOv8 features anchor-free design supporting detection, segmentation, pose estimation, and classification . YOLOv9 introduced GELAN backbone and programmable gradient information . YOLOv10 removed NMS for end-to-end inference . YOLOv11 improved small-object detection with multitasking . YOLOv12 added region attention, R-ELAN, and FlashAttention . Foundation for countless production detection systems.

- **[MMDetection](https://github.com/open-mmlab/mmdetection)**  
  OpenMMLab detection toolbox (Apache-2.0) with comprehensive configs and pretrained models. 85 FPS inference on V100. Part of the OpenMMLab CV ecosystem with unified interfaces for detection, segmentation, and classification .

- **[Detectron2](https://github.com/facebookresearch/detectron2)**  
  Modular detection and segmentation framework by Facebook AI Research (Apache-2.0). Includes classification backbones and utilities. Foundation for many production CV systems.

- **[YOLOv5](https://github.com/ultralytics/yolov5)**  
  PyTorch implementation (AGPL-3.0) with modular design, multiscale support, and auto-anchor generation . Slightly weaker detection performance compared with YOLOv4 in some benchmarks but vastly more popular due to ease of use .

- **[YOLOv7](https://github.com/WongKinYiu/yolov7)**  
  Introduced E-ELAN and unified architecture achieving state-of-the-art performance at release (GPL-3.0). Complex structure with high training demands .

- **[YOLOv6](https://github.com/meituan/YOLOv6)**  
  Meituan's EfficientRep and RepOpt architecture (GPL-3.0) optimized for real-time industrial applications. High training cost and reduced accuracy in dense scenes .

- **[PaddleDetection](https://github.com/PaddlePaddle/PaddleDetection)**  
  Object detection and segmentation toolkit by PaddlePaddle (Apache-2.0). Includes PP-YOLO, PP-YOLOv2, and other efficient detectors with deployment tools for production.

- **[MMDetection3D](https://github.com/open-mmlab/mmdetection3d)**  
  OpenMMLab 3D object detection toolbox (Apache-2.0). Supports CenterFormer, CenterPoint, PV-RCNN, Part-A2, 3DSSD, PointPillars, and other LiDAR detection architectures .

- **[FiftyOne](https://github.com/voxel51/fiftyone)**  
  Open-source tool (Apache-2.0) for curating high-quality datasets and refining visual AI models. Features dataset visualization, model evaluation, and embedding analysis. Essential for dataset-centric detection workflows.

- **[SAHI (Slicing Aided Hyper Inference)](https://github.com/obss/sahi)**  
  Framework (MIT) for small object detection via tiling and slicing. Particularly effective for aerial and remote sensing imagery where small objects are prevalent .

- **[SuperGradients](https://github.com/Deci-AI/super-gradients)**  
  Training library for computer vision models (Apache-2.0). Provides recipes for detection, classification, and segmentation with automatic hyperparameter tuning and hardware-aware optimization.

- **[OpenCV DNN](https://github.com/opencv/opencv)**  
  OpenCV's deep neural network module (Apache-2.0) for running inference with pretrained detection models (YOLO, SSD, Faster R-CNN) on CPU and GPU. Widely used for deployment without full training frameworks.

### Additional Strong Open-Source Options

- **[TensorFlow Object Detection API](https://github.com/tensorflow/models)** — Comprehensive framework for training and deploying detection models (Apache-2.0).
- **[TorchVision Detection](https://github.com/pytorch/vision)** — Pretrained Faster R-CNN, RetinaNet, FCOS, and SSD models with PyTorch (BSD license).
- **[Label Studio](https://github.com/HumanSignal/label-studio)** — General-purpose labeling platform (Apache-2.0) for building detection training datasets.
- **[CVAT](https://github.com/cvat-ai/cvat)** — Computer vision annotation tool (MIT) for image and video object labeling with tracking support.
- **[FujiCV](https://github.com/fujicv/fujicv)** — Python package for detection/classification/regression with backbone factory, 15 loss functions, and ONNX export.
- **[MMYOLO](https://github.com/open-mmlab/mmyolo)** — OpenMMLab YOLO series toolbox (Apache-2.0) with unified benchmark and deployment support.
- Community **HuggingFace** model hubs for pretrained detection models and **Weights & Biases** for experiment tracking.

**Frameworks for building custom systems**: Combine **Ultralytics YOLO** or **MMDetection** for model training with **SAHI** for small-object tiling, **FiftyOne** for dataset curation and evaluation, **CVAT** or **Label Studio** for annotation, and **ONNX Runtime** or **TensorRT** for optimized inference — creating a fully self-hosted, production-grade object detection stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Object detection systems must comply with privacy, surveillance, and data protection regulations (GDPR, BIPA, CCPA, etc.).
- Self-hosted open-source solutions require proper GPU provisioning, model versioning, and ongoing maintenance for production reliability.

---

**Made for ML engineers, data scientists, researchers, and developers building transparent computer vision solutions.**  
Let's make object detection more open, data-driven, and accessible.
