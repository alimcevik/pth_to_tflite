# PyTorch to Tensorflow Lite

This notebook allows you to convert your PyTorch (.pth) model to TensorFlowLite (.tflite) with the help of ONNX (.onnx)


```mermaid
graph LR
A[PyTorch] -- convert --> B[ONNX] -- convert -->  C[TensorFlowLite]
```