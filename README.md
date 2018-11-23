# gaze_detection
Project for auto-judgement of whether a subject's gaze is appropriate from other's view.

Reference:

Face detection:

[Darknet](https://github.com/AlexeyAB/darknet)

[azFace](https://github.com/azmathmoosa/azFace)


After compiling the darknet under the darknet directory, it can be tested through the following command:
```bash
./darknet detector test azFace/net_cfg/azface.data azFace/net_cfg/tiny-yolo-azface-fddb.cfg azFace/weights/tiny-yolo-azface-fddb_82000.weights face_detection_test.jpg
```
