# PyTorch Tensor Basics Summary

This notebook introduces fundamental PyTorch tensor concepts and operations.

## Topics Covered

- Checking PyTorch, NumPy, and CUDA versions
- Creating scalar, vector, matrix, and higher-dimensional tensors
- Inspecting tensor properties:
  - Dimensions (`ndim`)
  - Shape (`shape`)
  - Number of elements (`numel`)
  - Data type (`dtype`)
  - Device (`device`)
  - Elements using integer indices
- Creating tensors with:
  - Random values (`torch.rand`)
  - Zeros (`torch.zeros`)
  - Ones (`torch.ones`)
  - Ranges (`torch.arange`)
  - Matching shapes (`torch.zeros_like`)
- Specifying tensor data types, including `float16`, `float32`, and `int32`
- Moving tensors between CPU and GPU devices
- Enabling gradient tracking with `requires_grad=True`
- Performing tensor arithmetic and element-wise multiplication
- Multiplying tensors with different data types

## Key Concepts

PyTorch tensors are multidimensional arrays designed for efficient numerical computation. They can be stored on either the CPU or GPU and may track gradients for use in neural network training.

The notebook also demonstrates CUDA tensor operations, provided a compatible GPU is available.
