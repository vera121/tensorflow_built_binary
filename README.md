# Usage
1. Please use command `pip uninstall tensorflow` to uninstall the existing tensorflow in the system first to avoid possible errors
2. Then reinstall using `pip install tensorflow-2.5.0-cp36-cp36m-linux_x86_64.whl` (the path to the provided whl file)
3. Using `export TF_QUANTIZED_ROUND=EV` to enable the EV style rounding for tflite inference; using `unset TF_QUANTIZED_ROUND` to disable it and use the original tflite rounding
