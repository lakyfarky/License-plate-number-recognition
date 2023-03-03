# License-plate-number-recognition
License plate number recognition with YOLOv5 object detection algorithm and EasyOCR

This is simple python project for license plate detection and number recognition. 

First clone github and download PyTorch 
```
git clone https://github.com/lakyfarky/License-plate-recognition.git
pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu117
```
Then install requirements and set parameters 
```
pip install requirements.txt
```
```py
yolo = Yolov5("weights_path.onnx", "classes_path.txt", "vid_example_path.mp4")
```
and run 
```
python main.py
```

