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