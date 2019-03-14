# Infertense

Infer sizes of tensors in python code of `tensorflow/torch/keras/numpy` and
emit warnings statically.

# To read
- [pyre](https://github.com/facebook/pyre-check)
- [DataShape](https://github.com/blaze/datashape)
- [numpy-stubs](https://github.com/numpy/numpy-stubs)
- [plugin to support numpy thread](https://github.com/python/mypy/issues/3540)


# Examples of fuck ups

try calling `torch.F.binary_cross_entropy(...)` with incorrect sized mats. It dies within thrust.
