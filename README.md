# WebAssembly-OpenCV
This repository is a demo for a combination of WebAssembly and OpenCV.

The code detects the face shown in front of the camera in real-time,
and push a mask on the faces. The mask will follow the faces when people
move their heads. 
%-------------------------------------------------------------------------------------

#Running the demo

*If you want to run the demo in your personal computer. You should firstly set up 
a simple HTTP server on your computer:

python -m SimpleHTTPServer 8000(port_num)

And then you should visit 'http://localhost:8000' in your browser, and run 
'js_imgproc_camera.html'

After running the demo, you should kill the process of SimpleHTTPServer, which would
remain if you do not explicitly kill it. You can use 'ps' and 'kill -9 PID' to do that



%-------------------------------------------------------------------------------------
For more details for OpenCV, you could directly reach out ot https://opencv.org/

%-------------------------------------------------------------------------------------
For more details for WebAssembly, you can check out https://webassembly.org/
