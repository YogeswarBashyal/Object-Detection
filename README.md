# Object detection
The SkyFusion dataset is designed for detecting tiny objects in satellite images. While most datasets emphasize larger objects or structures, SkyFusion focuses on small-scale targets such as:

Vehicles
Ships
Aircraft

This dataset combines and refines two sources:
AiTOD v2 (for vehicles & ships)
Airbus Aircraft Detection (for aircraft balance)
Dataset Details
Dataset Base: AiTOD v2 + Airbus Aircraft Detection
Classes: Vehicles, Ships, Aircraft
Annotation Format: MS-COCO (.json)
Annotation Type: Horizontal Bounding Boxes (HBB)
The original AiTOD v2 dataset contained:
28,036 images
700,621 objects
8 classes
All annotated with Horizontal Bounding Boxes (HBB)
However, due to the massive size, it was impractical for training on free-tier or low-resource machines
