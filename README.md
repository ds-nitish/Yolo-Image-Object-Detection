# YOLO Object Detection

This repository contains a Python script that demonstrates object detection using the YOLO (You Only Look Once) algorithm with OpenCV. The script loads a pre-trained YOLO model, detects objects in an input image, and draws bounding boxes around the detected objects.

## Requirements

To run the script, you need to have the following dependencies installed:

- Python 3.x
- OpenCV
- NumPy

## Usage

1. Clone the repository to your local machine:

```
git clone https://github.com/your-username/Yolo-Image-Object-Detection.git
```

2. Change into the project directory:

```
cd Yolo-Image-Object-Detection
```

3. Download the YOLO model weights, configuration file, and class labels file. You can use the following links:

   - YOLOv3 weights: [yolov3.weights](https://pjreddie.com/media/files/yolov3.weights)
   - YOLOv3 configuration file: [yolov3.cfg](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)
   - COCO class labels: [coco.names](https://github.com/pjreddie/darknet/blob/master/data/coco.names)

4. Place the downloaded files in the project directory.

5. Run the script with the following command:

```
python Yolo-Image-Object-Detection.ipynb --image image.jpg
```

Replace `image.jpg` with the path to your own input image.

6. The script will display the input image with bounding boxes drawn around the detected objects. Press any key to close the window.

## Customization

You can customize the script by modifying the following parameters:

- Confidence threshold: Adjust the `confidence_threshold` variable to change the minimum confidence required for an object detection to be considered valid.
- NMS threshold: Change the `nms_threshold` variable to control the overlap threshold for non-maximum suppression.
- Font type, size, and color: Modify the parameters in the `cv2.putText()` function to change the appearance of the text labels.

Feel free to explore and modify the code according to your needs.

## License

This project is licensed under the [MIT License](LICENSE).

## Credits

The YOLO algorithm and the pre-trained weights used in this project are from the [Darknet](https://github.com/pjreddie/darknet) project by Joseph Redmon.

## References

- [YOLO: Real-Time Object Detection](https://pjreddie.com/darknet/yolo/)
- [OpenCV Documentation](https://docs.opencv.org/)
```

Make sure to replace the necessary sections, such as the repository URL, file download links, and license details, with the appropriate information for your project.
