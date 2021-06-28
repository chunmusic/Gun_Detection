# Gun Detection (Yolov5)

- This repository is created for gun detection application.

- The model was trained based on Yolov5.

## How to use

- Please run the following command to run the demo.

```python
python detect.py --weights runs/train/exp13/weights/best.pt --source gun.mp4 --conf-thres 0.7 --view-img
```

## Preview

![Image1](https://raw.githubusercontent.com/chunmusic/Gun_Detection/master/output.gif)

### Reference

https://github.com/ultralytics/yolov5