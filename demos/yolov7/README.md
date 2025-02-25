# YOLOv7 Example

Simplest possible example of tracking generic objects. Based on [YOLOv7](https://github.com/WongKinYiu/yolov7).

## Instructions

1. Build and run the Docker container with `./run_gpu.sh`.
2. Copy a video to the `src` folder.
3. Within the container, run with the default parameters:

   ```bash
   python demo.py <video>.mp4
   ```

For additional settings, you may display the instructions using `python demo.py --help`.

## Explanation

This example tracks objects using a single point per detection: the centroid of the bounding boxes around objects returned by YOLOv7.

![Norfair YOLOv7 demo](../../docs/videos/yolov7_cars.gif)
