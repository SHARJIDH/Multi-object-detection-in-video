```
- Install requirements with mentioned command below.
```

pip install -r requirements.txt

# for detection only

python detect_dual.py --weights 'yolov9-c.pt' --source 'testwalk.mp4' --device 0

#for detection and tracking
python detect_dual_tracking.py --weights 'yolov9-c.pt' --source 'testwalk.mp4' --device 0

- Output file will be created in the `working-dir/runs/detect/obj-tracking` with original filename
