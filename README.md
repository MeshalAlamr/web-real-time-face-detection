# web-real-time-motion-detection
This project is an implementation of [this tutorial](https://www.pyimagesearch.com/2019/09/02/opencv-stream-video-to-web-browser-html-page/) by Adrian Rosebrock with some modifications. 

The implementation is done for the summer training offered by Smart Methods.

## Prerequisites
- Python
- [Flask](https://palletsprojects.com/p/flask/)
- [OpenCV](https://opencv.org/)
- [NumPy](https://numpy.org/)
- imutils

The required Python libraries can be simply installed as so:
```
$ pip install flask
$ pip install opencv-contrib-python
$ pip install numpy
$ pip install imutils
```

## Procedure
1. Run "singlemotiondetector.py".
2. Run "webstreaming.py" through command line arguments like so:
```
$ python webstreaming.py --ip <IP> --port <PORT>
```
Where `<IP>` is the IP address of the system (127.0.0.1 for example if hosted locally) and `<PORT>` is the the port number for Flask to use (typically 8000).

3. The stream will be populated to the specified IP address.

## Output
