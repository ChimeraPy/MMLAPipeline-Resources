# MMLAPipeline-Resources
Demos, posters and other resources related to the [`ChimeraPy`](https://github.com/oele-isis-vanderbilt/ChimeraPy.git) MMLA Pipeline ecosystem for EngageAI Institute site visit 2023.

## Posters
1. [ChimeraPy and the MMLAPipeline](./posters/ChimeraPyPoster.pdf)

## Demos
1. [multi-camera.json](./demos/multi-camera.json): [`ChimeraPyOrchestrator`](https://github.com/oele-isis-vanderbilt/ChimeraPyOrchestrator.git) config streaming multiple web cameras. This requires 2 external webcams (along with the native webcams) connected to a `linux` and `windows` machine. In the manager, we also run a [`webrtc-chimerapy-node`](https://github.com/oele-isis-vanderbilt/webrtc-chimerapy-node.git).

The architecture is as follows:
 ![multicamera.png](./images/multicamera.png)

2. [gaze-camera-screen.json](./demos/gaze-camera-screen.json): [`ChimeraPyOrchestrator`](https://github.com/oele-isis-vanderbilt/ChimeraPyOrchestrator.git) configuration for capturing screen and webcam images on a remote machine, feeding it to a gaze detection network ([L2CS-Net](https://github.com/Ahmednull/L2CS-Net)) and displaying results in a local machine. The architecture is as follows:

![gaze-detection.png](./images/gaze-detection.png)


https://github.com/oele-isis-vanderbilt/MMLAPipeline-Resources/assets/11476842/416fe124-72c7-4ddb-bb5e-cd5052b488c0



3. [multi-video-tracking.json](./demos/multi-video-tracking.json): [`ChimeraPyOrchestrator`](https://github.com/oele-isis-vanderbilt/ChimeraPyOrchestrator.git) configuration for tracking multiple objects in multiple videos. The architecture is as follows:
![multi-video-tracking.png](./images/multi-video-tracking.png)


## Useful Links
- [`ChimeraPy`](https://github.com/oele-isis-vanderbilt/ChimeraPy): Distributed computing framework for Multimodal data written in Python

- [`ChimeraPyOrchestrator`](https://github.com/oele-isis-vanderbilt/ChimeraPyOrchestrator): Reusable Nodes and Orchestration Scheme/ Dashboard Application for ChimeraPy with JSON configuration

- [`MMLAPIPE`](https://github.com/oele-isis-vanderbilt/MMLAPIPE): Repository of shareable `ChimeraPy` pipelines
