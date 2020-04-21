# CannyEdgeDetection

## Theory
The Canny Edge detector was developed by John F. Canny in 1986. Also known to many as the optimal detector, Canny algorithm aims to satisfy three main criteria:
- **Low error rate**: Meaning a good detection of only existent edges.
- **Good localization**: The distance between edge pixels detected and real edge pixels have to be minimized.
- **Minimal response**: Only one detector response per edge

## Algorithm

Canny Edge Detection is based on the following steps:

    1.Grayscale Conversion
    2.Noise Reduction
    3.Determining Intensity Gradients
    4.Non-Maximum Suppression
    5.Edge Tracking by Double Threslholding Hysteresis

## References

  - https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_canny/py_canny.html
  - http://justin-liang.com/tutorials/canny/
  - https://medium.com/@ssatyajitmaitra/what-canny-edge-detection-algorithm-is-all-about-103d94553d21
  - https://www.ijcsi.org/papers/IJCSI-9-5-1-269-276.pdf
  - https://aishack.in/tutorials/canny-edge-detector/
  - https://github.com/MadhavEsDios/Canny-Edge-Detector
  - https://www.hackerearth.com/practice/notes/thethunder666/canny-edge-detection/
  - https://towardsdatascience.com/canny-edge-detection-step-by-step-in-python-computer-vision-b49c3a2d8123
