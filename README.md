# Traffic-Management

### Navigate into the yolov7 folder
  cd yolov7

### Install the weights trained by the COCO Dataset
  wget "https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7.pt"

### Install all the Requirements
  pip install -r requirements.txt
  
### Run the Code and add the video for detection (--weights <PATH OF THE WEIGHT>  --source <PATH OF THE VIDEO OR IMG FILE>)
  python detect_and_count.py --weights /yolov7/yolov7.pt --conf 0.1 --source //yolov7/inference/video.mp4
  
### Find the Output in the figure folder inside yolov7
