# nvr
# Network Video Recorder
This version of the recorder shall be implemented as C++, shadowing and improving the existing network video recorder, the latter is implemented in Python + OpenCV.

# Specification
- Resolution: 3840 x 2160 pixels
- Speed: 4 fps
- Prototype: Python 3.9 interpreter + OpenCV 4.6.0.66
- CPU load: 80% peak (open output), 40% average (write output)
- CPU type: MacBook, 2.5 GHz Qua-Core Intel i7 (mid 2015)

# Targets
- The output files witten by the network video recorder shall be smaller, however having the same resolution as in the Python + OpenCV version.
- The network video recorder shall use less CPU resources, than the Python + OpenCV version.
