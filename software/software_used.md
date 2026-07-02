# Software Stack

Technologies referenced in the system design and prototype for the Vigilant fall detection project.

| Technology | Description |
|------------|-------------|
| **Python** | Primary programming language used for prototyping the detection logic. |
| **OpenCV** | Computer vision library used for image processing on frames captured after a potential fall is flagged. |
| **YOLO** | Object detection model referenced for person detection as part of the vision pipeline. |
| **OpenPose** | Pose estimation library referenced for optional visual confirmation of a fall. |
| **RPLIDAR SDK** | Vendor SDK used to communicate with the RPLIDAR A1 sensor and read point-cloud data. |
| **JetPack** | NVIDIA's SDK for the Jetson Nano, providing the OS image, CUDA, and drivers needed for on-device processing. |
| **SMTP** | Email protocol used for sending fall-alert notifications. |
| **Ubuntu** | Linux distribution running on the Jetson Nano (via JetPack). |
| **Jetson Nano SDK** | NVIDIA's developer SDK/tools for building and deploying software on the Jetson Nano platform. |

This list reflects the technologies the prototype was designed around, as documented in the project's system design. It is not a `requirements.txt` for a maintained software package — see [code/README.md](../code/README.md) for the code availability statement.
