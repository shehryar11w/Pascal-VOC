# Pascal VOC — Object Detection

Object detection on the **Pascal VOC 2012** dataset (20 classes), comparing two different detection approaches: a two-stage **Faster R-CNN** model and a one-stage **YOLOv8** model.

## Contents

| Notebook | Description |
|---|---|
| `model-yolo.ipynb` | Converts Pascal VOC's XML annotations into YOLO format, then trains a YOLOv8 (`yolov8n.pt`) model on the converted dataset using the `ultralytics` library. |
| `model-faster-rcnn.ipynb` | Trains and evaluates a Faster R-CNN model on the Pascal VOC dataset. |

## Dataset

**Pascal VOC 2012**, with the standard 20 object classes (aeroplane, bicycle, bird, boat, bottle, bus, car, cat, chair, cow, diningtable, dog, horse, motorbike, person, pottedplant, sheep, sofa, train, tvmonitor). Class/path configuration is in `voc.yaml`.

## Technologies

- Python
- PyTorch / TorchVision
- Ultralytics YOLOv8
- Weights & Biases (W&B) for experiment tracking

## Getting Started

```bash
git clone https://github.com/shehryar11w/Pascal-VOC.git
cd Pascal-VOC
pip install torch torchvision ultralytics wandb
```

Open either notebook in Jupyter or VS Code and run.

## License

Educational / personal use.
