# What this is

A two-minute webcam pupil test used for a small research pilot. It measures the pupil
light reflex in the browser; nothing is recorded or uploaded — results exist only as a
file the participant downloads.

# Components and licenses

| Component | License | Source |
| --- | --- | --- |
| mEye pupil-segmentation model (weights) | GPLv3 | Mazziotti, Carrara et al. 2021, eNeuro — https://github.com/fabiocarrara/meye |
| biometrics-pupil-meye engine (compiled) | GPLv3 | corresponding source available on request from the repository owner |
| biometrics-core (compiled) | MIT | source available on request from the repository owner |
| TensorFlow.js (vendored tf.min.js) | Apache-2.0 | https://github.com/tensorflow/tfjs |
| MediaPipe tasks-vision (loaded from CDN at run time) | Apache-2.0 | https://github.com/google-ai-edge/mediapipe |

This bundle as a whole is distributed under GPLv3 (see LICENSE).
