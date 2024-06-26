# polo_tracking

**Objectives:** Keeping track of water polo frame by frame in polo games. Performing real-time object detection of teams, water polo ball, and cage. Built up and annotated 100+ images from LEN Championships and NCAA Division I water polo games on Roboflow. Trained on YOLO-V9 model for object detecion. 

**Initial Performances:** <br />
V1: Dataset Splits (Training - 75, Valid - 21, Test - 11), Trained on batch size 22, 30 epochs on Colab T4 GPU

![Unknown](https://github.com/richardyun03/polo_tracking/assets/98052432/f6164b71-eec9-40c2-b133-04801adda1d5)



Inference Output: <br />
![Unknown-2](https://github.com/richardyun03/polo_tracking/assets/98052432/69115c94-f71e-45f5-9f1c-fc642afedef3)
![Unknown-3](https://github.com/richardyun03/polo_tracking/assets/98052432/bdd5caf8-9836-4581-b4a5-7e407a4be510)


**Further Developments:**
- Continue building up dataset to fine-tune model on players in the presence of noise (ie. splashing, swimming). Error on dark caps also high.
- Expand into other sport domains -- basketball, volleyball, etc. -- to incorporate a more general-purpose game tracking model.
- Build up generalized dataset
- Develop into real-time video object tracking

