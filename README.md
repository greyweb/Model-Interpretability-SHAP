# SHAP(SHapley Additive exPlaination)

SHAP Values helps us to stop with the notion to think of ML/DL algorithms as a complete black box and brings out a notion that it's more of a grey box rather white box if causality is determined.

## Description
This colab notebook uses the shap[https://shap.readthedocs.io/en/latest/image_examples.html] documentation to understand how model interpretability can work on images in specific (CNN's). This interpretability can be achieved at a global level( overall prediction) and at a local level( layer-wise prediction).

Also heads up( if your framework is TensorFlow, then  tf version 2.5.0 works best)

Positive SHAP values are contributions towards correct prediction and negative are contributions towards incorrect ones.
