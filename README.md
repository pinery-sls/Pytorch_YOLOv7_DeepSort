# Pytorch_YOLOv5_Deepsort
 YOLOv5 and Deepsort



![demo](demo_yolov7_deepsort.gif)

## Download
### Deepsort
Download [ckpt.t7](https://drive.google.com/drive/folders/1xhG0kRH1EX5B9_Iz8gQJb7UNnn_riXi6) and copy to deep_sort_pytorch/deep_sort/deep/checkpoint/

### YOLOv7
Downlod Yolov7 model and copy to yolov7/weights/

[assets]: https://github.com/WongKinYiu/yolov7/releases/tag/v0.1

|Model |
| ------ |
|[YOLOv7][assets] |
|[YOLOv7-X][assets] |
|[YOLOv7-W6l][assets] |
|[YOLOv7-E6][assets] |
|[YOLOv7-D6][assets] |
|[YOLOv7-E6E][assets] |

## Tracking sources

Tracking can be run on most video formats

```bash
python3 track.py --source ... --show-vid  # show live inference results as well
```

- Video:  `--source file.mp4`
- Webcam:  `--source 0`
- RTSP stream:  `--source rtsp://170.93.143.139/rtplive/470011e600ef003a004ee33696235daa`
- HTTP stream:  `--source http://wmccpinetop.axiscam.net/mjpg/video.mjpg`
