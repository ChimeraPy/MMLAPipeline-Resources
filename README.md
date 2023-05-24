# MMLAPipeline-Resources
`ChimeraPyOrchestrator` configs, posters and other resources related to the `ChimeraPy` ecosystem for AIInstitute Evaluation Meeting 2023.

## Posters
Please add posters


## Demos
1. [multi-camera.json](./demos/multi-camera.json): [`ChimeraPyOrchestrator`](https://github.com/oele-isis-vanderbilt/ChimeraPyOrchestrator.git) config streaming multiple web cameras. This requires 2 external webcams (along with the native webcams) connected to a `linux` and `windows` machine. In the manager, we also run a [`webrtc-chimerapy-node`](https://github.com/oele-isis-vanderbilt/webrtc-chimerapy-node.git).

The architecture is as follows:
 ![multicamera.png](./images/multicamera.png)

 2. [gaze-camera-screen.json](./demos/gaze-camera-screen.json): [`ChimeraPyOrchestrator`](https://github.com/oele-isis-vanderbilt/ChimeraPyOrchestrator.git) configuration for capturing screen and webcam images on a remote machine, feeding it to a gaze detection network ([L2CS-Net](https://github.com/Ahmednull/L2CS-Net)) and displaying results in a local machine. The architecture is as follows:

![gaze-detection.png](./images/gaze-detection.png)

## Useful Links
- [`ChimeraPy`](https://github.com/oele-isis-vanderbilt/ChimeraPy): Distributed computing framework for Multimodal data written in Python

- [`ChimeraPyOrchestrator`](https://github.com/oele-isis-vanderbilt/ChimeraPyOrchestrator): Reusable Nodes and Orchestration Scheme/ Dashboard Application for ChimeraPy with JSON configuration

- [`MMLAPIPE`](https://github.com/oele-isis-vanderbilt/MMLAPIPE): Repository of shareable `ChimeraPy` pipelines
