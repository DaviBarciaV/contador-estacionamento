------- Smart Parking Spot Detection --------
This project demonstrates a practical application of computer vision for smart parking management. 
It was developed to detect and count available parking spots in real-time from surveillance video, using Python and OpenCV.

- Key highlights -
Computer vision: Detects and tracks parking space occupancy using adaptive thresholding, filtering, and contour analysis.
Manual annotation tool: Enables quick configuration for any parking layout via interactive ROI selection.
Real-Time feedback: Continuously updates parking availability on video with visual indicators.
Scalable logic: Easily adaptable to other camera feeds or parking lots with minimal code changes.

- Why it matters -
This project shows my ability to:
Apply image processing techniques in real-world scenarios
Build tools from scratch for data labeling and automation
Handle OpenCV workflows for video frame analysis
Work with serialized data and basic ML-friendly formats (Pickle)

- Project Structure -

File	-  Purpose
capturarVagas.py	- Selects and saves parking spot coordinates (.pkl file)
contadorVagas.py	- Detects occupied vs. free spots in a video feed
video.mp4 - 	Sample footage of the parking lot
vagas-mangabeirashopping.pkl -	Coordinates of parking spots

- How to run (Recommended use: Anaconda Prompt) -
Run capturarVagas.py to annotate parking spaces.
Run contadorVagas.py to start the detection system.
The program will highlight free spots in green, occupied in red, and show the total count.

- Requirements -
Python 3.x
OpenCV
Numpy
Pickle (for data serialization)
