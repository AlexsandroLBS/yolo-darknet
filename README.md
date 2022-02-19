# yolo-darknet
yolov4.cfg - 245 MB: yolov4.weights (Google-drive mirror yolov4.weights ) paper Yolo v4 just change width= and height= parameters in yolov4.cfg file and use the same yolov4.weights file for all cases:

width=608 height=608 in cfg: 65.7% mAP@0.5 (43.5% AP@0.5:0.95) - 34(R) FPS / 62(V) FPS - 128.5 BFlops
width=512 height=512 in cfg: 64.9% mAP@0.5 (43.0% AP@0.5:0.95) - 45(R) FPS / 83(V) FPS - 91.1 BFlops
width=416 height=416 in cfg: 62.8% mAP@0.5 (41.2% AP@0.5:0.95) - 55(R) FPS / 96(V) FPS - 60.1 BFlops
width=320 height=320 in cfg: 60% mAP@0.5 ( 38% AP@0.5:0.95) - 63(R) FPS / 123(V) FPS - 35.5 BFlops
