## Overview
This project presents a unified perception system that integrates object detection, vision–language scene captioning, and a rule-based decision engine to interpret traffic scenes using only a camera feed.
It combines YOLOv10m for robust traffic-object detection with BLIP-Traffic, a domain-adapted captioning model, to generate accurate, context-aware scene descriptions.
A fusion layer merges spatial detections and semantic captions to produce human-like driving recommendations such as Stop, Slow Down, Keep Speed, and Caution.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Dataset
### BDD100K

* Used for training YOLO models

* Includes diverse weather, lighting, and traffic conditions

* Label formats converted to YOLO and COCO structures

### Custom Caption BDD100K Dataset

* Traffic-specific captions curated for BLIP fine-tuning

* Includes objects, actions, traffic signals, and scene context

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Key Features

* End-to-end pipeline using only a camera

* YOLOv10m-based traffic-object detection

* Traffic-aware BLIP caption generation

* Rule-based fusion for interpretable decision-making

* Per-frame recommendations for driver assistance systems

## Team
[Vaishnavi_Kulkarni](https://www.linkedin.com/in/vaishnavi-kulkarni-4ab628b7/)

## Contact
Created by [@VaishnaviK711](https://github.com/VaishnaviK711)- feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->